# Function: <code>perf_iterate_ctx</code>

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
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118c840)
Location: kernel/events/core.c:6034
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff8118c840-ffffffff8118c997: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119bff0)
Location: kernel/events/core.c:6132
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff8119bff0-ffffffff8119c147: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a4490)
Location: kernel/events/core.c:6228
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff811a4490-ffffffff811a45d7: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b8450)
Location: kernel/events/core.c:6216
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff811b8450-ffffffff811b859f: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d7db0)
Location: kernel/events/core.c:6590
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff811d7db0-ffffffff811d7f10: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e79f0)
Location: kernel/events/core.c:6599
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff811e79f0-ffffffff811e7b50: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fee60)
Location: kernel/events/core.c:6680
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff811fee60-ffffffff811fefc0: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120c0a0)
Location: kernel/events/core.c:6796
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff8120c0a0-ffffffff8120c200: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81233075)
Location: kernel/events/core.c:7241
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff81232ec0-ffffffff81233026: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ce45)
Location: kernel/events/core.c:7423
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff8123cc20-ffffffff8123cd86: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812418c5)
Location: kernel/events/core.c:7534
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff81241710-ffffffff81241876: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127c2b5)
Location: kernel/events/core.c:7658
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff8127c100-ffffffff8127c266: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e03e2)
Location: kernel/events/core.c:7563
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
Direct callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff812d0a80-ffffffff812d0c04: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81337c80)
Location: kernel/events/core.c:7852
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff81337c80-ffffffff81337d87: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81368bb0)
Location: kernel/events/core.c:7880
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff81368bb0-ffffffff81368cb8: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813919e0)
Location: kernel/events/core.c:7961
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff813919e0-ffffffff81391ae8: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffff80001029fe64)
Location: kernel/events/core.c:6796
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
Direct callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffff800010294f40-ffff8000102950a8: perf_iterate_ctx.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (c04cfd40)
Location: kernel/events/core.c:6796
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
Direct callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
c04c5198-c04c52f8: perf_iterate_ctx.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (c0000000003514dc)
Location: kernel/events/core.c:6796
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
Direct callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
c000000000343c90-c000000000343e70: perf_iterate_ctx.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffe0001cf562)
Location: kernel/events/core.c:6796
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
Direct callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffe0001c6d80-ffffffe0001c6e7e: perf_iterate_ctx.constprop.0 (STB_LOCAL)
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
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812046c0)
Location: kernel/events/core.c:6796
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff812046c0-ffffffff81204820: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f7450)
Location: kernel/events/core.c:6796
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff811f7450-ffffffff811f75b0: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202490)
Location: kernel/events/core.c:6796
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff81202490-ffffffff812025f0: perf_iterate_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_iterate_ctx(struct perf_event_context *ctx, perf_iterate_f *output, void *data, bool all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81212040)
Location: kernel/events/core.c:6796
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_sb
```
**Symbols:**

```
ffffffff81212040-ffffffff812121a0: perf_iterate_ctx (STB_LOCAL)
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
