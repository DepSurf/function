# Function: <code>ctx_resched</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118f3e0)
Location: kernel/events/core.c:2219
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8118f3e0-ffffffff8118f466: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119e990)
Location: kernel/events/core.c:2257
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8119e990-ffffffff8119ea16: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a70e0)
Location: kernel/events/core.c:2316
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811a70e0-ffffffff811a71b5: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ba750)
Location: kernel/events/core.c:2250
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811ba750-ffffffff811ba813: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d5aa0)
Location: kernel/events/core.c:2447
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811d5aa0-ffffffff811d5b5b: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e6140)
Location: kernel/events/core.c:2447
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811e6140-ffffffff811e61fb: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd950)
Location: kernel/events/core.c:2450
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff811fd950-ffffffff811fda0b: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ac00)
Location: kernel/events/core.c:2535
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff8120ac00-ffffffff8120acbb: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123b490)
Location: kernel/events/core.c:2684
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff8123b490-ffffffff8123b569: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81245ab0)
Location: kernel/events/core.c:2719
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff81245ab0-ffffffff81245b89: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812498d0)
Location: kernel/events/core.c:2721
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff812498d0-ffffffff812499a9: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81285940)
Location: kernel/events/core.c:2760
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff81285940-ffffffff81285a19: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d9f00)
Location: kernel/events/core.c:2671
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff812d9f00-ffffffff812d9fe3: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81342c30)
Location: kernel/events/core.c:2670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff81342c30-ffffffff81342d64: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81373c90)
Location: kernel/events/core.c:2670
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff81373c90-ffffffff81373dc4: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139cb30)
Location: kernel/events/core.c:2708
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff8139cb30-ffffffff8139cc6e: ctx_resched (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102998c8)
Location: kernel/events/core.c:2535
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffff8000102998c8-ffff800010299968: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c8d18)
Location: kernel/events/core.c:2535
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
c04c8d18-c04c8dbc: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000348ea0)
Location: kernel/events/core.c:2535
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
c000000000348ea0-c000000000348fe4: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cc408)
Location: kernel/events/core.c:2535
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffe0001cc408-ffffffe0001cc4a0: ctx_resched (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81203220)
Location: kernel/events/core.c:2535
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff81203220-ffffffff812032db: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f5f70)
Location: kernel/events/core.c:2535
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff811f5f70-ffffffff811f602b: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200ff0)
Location: kernel/events/core.c:2535
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff81200ff0-ffffffff812010ab: ctx_resched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ctx_resched(struct perf_cpu_context *cpuctx, struct perf_event_context *task_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812101a0)
Location: kernel/events/core.c:2535
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_pmu_resched
```
**Symbols:**

```
ffffffff812101a0-ffffffff8121025b: ctx_resched (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum event_type_t event_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
