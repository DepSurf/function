# Function: <code>perf_remove_from_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, bool detach_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117dda0)
Location: kernel/events/core.c:1673
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:orphans_remove_work
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff8117dda0-ffffffff8117deb3: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811900dd)
Location: kernel/events/core.c:1892
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119ff80)
Location: kernel/events/core.c:1904
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff8119ff80-ffffffff811a0013: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a7ba0)
Location: kernel/events/core.c:1917
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811a7ba0-ffffffff811a7c11: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bb310)
Location: kernel/events/core.c:1907
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811bb310-ffffffff811bb381: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811db230)
Location: kernel/events/core.c:2104
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811db230-ffffffff811db2a1: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811eb570)
Location: kernel/events/core.c:2104
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811eb570-ffffffff811eb5e1: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812022c0)
Location: kernel/events/core.c:2106
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff812022c0-ffffffff81202333: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81212290)
Location: kernel/events/core.c:2191
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff81212290-ffffffff81212303: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123c296)
Location: kernel/events/core.c:2337
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff8123e4c0-ffffffff8123e531: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81246536)
Location: kernel/events/core.c:2377
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
Direct callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff812488b0-ffffffff81248921: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124c960)
Location: kernel/events/core.c:2383
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff8124c960-ffffffff8124c9f5: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81288450)
Location: kernel/events/core.c:2454
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff81288450-ffffffff812884e8: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dcca0)
Location: kernel/events/core.c:2367
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff812dcca0-ffffffff812dcd39: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81345090)
Location: kernel/events/core.c:2372
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff81345090-ffffffff81345125: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81376130)
Location: kernel/events/core.c:2372
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff81376130-ffffffff813761c5: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139f430)
Location: kernel/events/core.c:2410
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:perf_event_exit_event
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff8139f430-ffffffff8139f4c5: perf_remove_from_context (STB_LOCAL)
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
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029c728)
Location: kernel/events/core.c:2191
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffff80001029c728-ffff80001029c7b4: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cbcd4)
Location: kernel/events/core.c:2191
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
c04cbcd4-c04cbd80: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034cc70)
Location: kernel/events/core.c:2191
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
c00000000034cc70-c00000000034cd80: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cb05c)
Location: kernel/events/core.c:2191
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffe0001cb05c-ffffffe0001cb110: perf_remove_from_context (STB_LOCAL)
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
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a8e0)
Location: kernel/events/core.c:2191
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff8120a8e0-ffffffff8120a953: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd6d0)
Location: kernel/events/core.c:2191
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811fd6d0-ffffffff811fd73d: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208680)
Location: kernel/events/core.c:2191
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff81208680-ffffffff812086f3: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_remove_from_context(struct perf_event *event, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81217420)
Location: kernel/events/core.c:2191
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff81217420-ffffffff81217488: perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
