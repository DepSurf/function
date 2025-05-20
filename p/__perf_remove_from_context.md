# Function: <code>__perf_remove_from_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __perf_remove_from_context(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117c8d0)
Location: kernel/events/core.c:1638
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff8117c8d0-ffffffff8117c97e: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118e700)
Location: kernel/events/core.c:1861
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff8118e700-ffffffff8118e7af: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119e150)
Location: kernel/events/core.c:1873
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff8119e150-ffffffff8119e1f9: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a5480)
Location: kernel/events/core.c:1886
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff811a5480-ffffffff811a550a: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b79f0)
Location: kernel/events/core.c:1871
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff811b79f0-ffffffff811b7afd: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d6da0)
Location: kernel/events/core.c:2068
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff811d6da0-ffffffff811d6ec9: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e71c0)
Location: kernel/events/core.c:2068
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff811e71c0-ffffffff811e72e9: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe7f0)
Location: kernel/events/core.c:2070
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff811fe7f0-ffffffff811fe919: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812125a0)
Location: kernel/events/core.c:2155
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff812125a0-ffffffff812126c9: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123e930)
Location: kernel/events/core.c:2300
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff8123e930-ffffffff8123ea84: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81248d20)
Location: kernel/events/core.c:2340
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff81248d20-ffffffff81248e74: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124c760)
Location: kernel/events/core.c:2344
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff8124c760-ffffffff8124c958: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812881a0)
Location: kernel/events/core.c:2412
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff812881a0-ffffffff81288441: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dc9e0)
Location: kernel/events/core.c:2325
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff812dc9e0-ffffffff812dcc98: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81344d80)
Location: kernel/events/core.c:2310
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff81344d80-ffffffff81345080: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81375e30)
Location: kernel/events/core.c:2310
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff81375e30-ffffffff8137611b: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139f130)
Location: kernel/events/core.c:2348
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_remove_from_context
```
**Symbols:**

```
ffffffff8139f130-ffffffff8139f41b: __perf_remove_from_context (STB_LOCAL)
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
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029ca68)
Location: kernel/events/core.c:2155
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffff80001029ca68-ffff80001029cb64: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cc000)
Location: kernel/events/core.c:2155
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
c04cc000-c04cc178: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034d150)
Location: kernel/events/core.c:2155
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
c00000000034d150-c00000000034d298: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cbf08)
Location: kernel/events/core.c:2155
Inline: False
```
**Symbols:**

```
ffffffe0001cbf08-ffffffe0001cbff4: __perf_remove_from_context (STB_LOCAL)
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
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120abf0)
Location: kernel/events/core.c:2155
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff8120abf0-ffffffff8120ad19: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd9d0)
Location: kernel/events/core.c:2155
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff811fd9d0-ffffffff811fdaf9: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208990)
Location: kernel/events/core.c:2155
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff81208990-ffffffff81208ab9: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __perf_remove_from_context(struct perf_event *event, struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81217720)
Location: kernel/events/core.c:2155
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
```
**Symbols:**

```
ffffffff81217720-ffffffff81217849: __perf_remove_from_context (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_event *event</code>
</li>
<li>
<b>Param added. </b>
<code>struct perf_cpu_context *cpuctx</code>
</li>
<li>
<b>Param added. </b>
<code>struct perf_event_context *ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>info</code> ➡️ <code>event, cpuctx, ctx, info</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
