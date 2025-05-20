# Function: <code>__uprobe_perf_func</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8116f310)
Location: kernel/trace/trace_uprobe.c:1107
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff8116f310-ffffffff8116f4ef: __uprobe_perf_func.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8117c9e0)
Location: kernel/trace/trace_uprobe.c:1107
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff8117c9e0-ffffffff8117cbc8: __uprobe_perf_func.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811885f0)
Location: kernel/trace/trace_uprobe.c:1107
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811885f0-ffffffff811887d8: __uprobe_perf_func.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff8118b180)
Location: kernel/trace/trace_uprobe.c:1110
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff8118b180-ffffffff8118b366: __uprobe_perf_func.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81198c40)
Location: kernel/trace/trace_uprobe.c:1110
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff81198c40-ffffffff81198e34: __uprobe_perf_func.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811ae320)
Location: kernel/trace/trace_uprobe.c:1093
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811ae320-ffffffff811ae511: __uprobe_perf_func.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811bca30)
Location: kernel/trace/trace_uprobe.c:1095
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811bca30-ffffffff811bcc21: __uprobe_perf_func.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811cc180)
Location: kernel/trace/trace_uprobe.c:1117
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811cc180-ffffffff811cc36a: __uprobe_perf_func.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d8690)
Location: kernel/trace/trace_uprobe.c:1325
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811d8690-ffffffff811d889f: __uprobe_perf_func.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __uprobe_perf_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f4710)
Location: kernel/trace/trace_uprobe.c:1325
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811f4710-ffffffff811f48e6: __uprobe_perf_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __uprobe_perf_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f30a0)
Location: kernel/trace/trace_uprobe.c:1338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811f30a0-ffffffff811f3276: __uprobe_perf_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __uprobe_perf_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f3fd0)
Location: kernel/trace/trace_uprobe.c:1343
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811f3fd0-ffffffff811f41a3: __uprobe_perf_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __uprobe_perf_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1344
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff812254b0-ffffffff8122568f: __uprobe_perf_func (STB_LOCAL)
ffffffff81cb7667-ffffffff81cb767b: __uprobe_perf_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __uprobe_perf_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1334
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff812656b0-ffffffff812658f6: __uprobe_perf_func (STB_LOCAL)
ffffffff81e6874d-ffffffff81e68761: __uprobe_perf_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __uprobe_perf_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1340
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff812b7ed0-ffffffff812b829f: __uprobe_perf_func (STB_LOCAL)
ffffffff8205f293-ffffffff8205f2d7: __uprobe_perf_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __uprobe_perf_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1340
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff812db500-ffffffff812db8c6: __uprobe_perf_func (STB_LOCAL)
ffffffff820dde39-ffffffff820dde7d: __uprobe_perf_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __uprobe_perf_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:1336
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff812f95d0-ffffffff812f99ae: __uprobe_perf_func (STB_LOCAL)
ffffffff821b9c57-ffffffff821b9c9b: __uprobe_perf_func.cold (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffff8000102597f0)
Location: kernel/trace/trace_uprobe.c:1325
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffff8000102597f0-ffff8000102599b4: __uprobe_perf_func.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __uprobe_perf_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c048b200)
Location: kernel/trace/trace_uprobe.c:1325
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
c048b200-c048b3c0: __uprobe_perf_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __uprobe_perf_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c0000000002fb150)
Location: kernel/trace/trace_uprobe.c:1325
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
c0000000002fb150-c0000000002fb3f4: __uprobe_perf_func (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d0cb0)
Location: kernel/trace/trace_uprobe.c:1325
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811d0cb0-ffffffff811d0ebf: __uprobe_perf_func.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811c3a80)
Location: kernel/trace/trace_uprobe.c:1325
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811c3a80-ffffffff811c3c8f: __uprobe_perf_func.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811cea80)
Location: kernel/trace/trace_uprobe.c:1325
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811cea80-ffffffff811cec8f: __uprobe_perf_func.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811dccf0)
Location: kernel/trace/trace_uprobe.c:1325
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811dccf0-ffffffff811dcf1d: __uprobe_perf_func.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
