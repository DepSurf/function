# Function: <code>__uprobe_trace_func</code>

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
In kernel/trace/trace_uprobe.c (ffffffff8116f9b0)
Location: kernel/trace/trace_uprobe.c:785
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff8116f9b0-ffffffff8116fbf7: __uprobe_trace_func.isra.9 (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff8117d0a0)
Location: kernel/trace/trace_uprobe.c:785
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff8117d0a0-ffffffff8117d313: __uprobe_trace_func.isra.10 (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff81188cb0)
Location: kernel/trace/trace_uprobe.c:785
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff81188cb0-ffffffff81188f23: __uprobe_trace_func.isra.12 (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff8118b8c0)
Location: kernel/trace/trace_uprobe.c:788
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff8118b8c0-ffffffff8118bb0c: __uprobe_trace_func.isra.8 (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff81199360)
Location: kernel/trace/trace_uprobe.c:788
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff81199360-ffffffff811995ac: __uprobe_trace_func.isra.8 (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff811aeb70)
Location: kernel/trace/trace_uprobe.c:769
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811aeb70-ffffffff811aeda6: __uprobe_trace_func.isra.11 (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff811bd0f0)
Location: kernel/trace/trace_uprobe.c:781
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811bd0f0-ffffffff811bd326: __uprobe_trace_func.isra.18 (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:819
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811cc950-ffffffff811ccb75: __uprobe_trace_func.isra.0 (STB_LOCAL)
ffffffff811ce1cb-ffffffff811ce1de: __uprobe_trace_func.isra.0.cold (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff811d8ef0)
Location: kernel/trace/trace_uprobe.c:928
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811d8ef0-ffffffff811d912f: __uprobe_trace_func.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __uprobe_trace_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize, struct trace_event_file *trace_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f4bf0)
Location: kernel/trace/trace_uprobe.c:928
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811f4bf0-ffffffff811f4e3b: __uprobe_trace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __uprobe_trace_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize, struct trace_event_file *trace_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f3580)
Location: kernel/trace/trace_uprobe.c:941
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811f3580-ffffffff811f37cb: __uprobe_trace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __uprobe_trace_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize, struct trace_event_file *trace_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f44f0)
Location: kernel/trace/trace_uprobe.c:946
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811f44f0-ffffffff811f4744: __uprobe_trace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __uprobe_trace_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize, struct trace_event_file *trace_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81225860)
Location: kernel/trace/trace_uprobe.c:946
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff81225860-ffffffff81225acd: __uprobe_trace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __uprobe_trace_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize, struct trace_event_file *trace_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81265360)
Location: kernel/trace/trace_uprobe.c:944
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff81265360-ffffffff812654bc: __uprobe_trace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __uprobe_trace_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize, struct trace_event_file *trace_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812b71c0)
Location: kernel/trace/trace_uprobe.c:950
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff812b71c0-ffffffff812b731c: __uprobe_trace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __uprobe_trace_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize, struct trace_event_file *trace_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812da820)
Location: kernel/trace/trace_uprobe.c:950
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff812da820-ffffffff812da97c: __uprobe_trace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __uprobe_trace_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize, struct trace_event_file *trace_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812f8a70)
Location: kernel/trace/trace_uprobe.c:946
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff812f8a70-ffffffff812f8bcc: __uprobe_trace_func (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffff80001025a550)
Location: kernel/trace/trace_uprobe.c:928
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffff80001025a550-ffff80001025a7ac: __uprobe_trace_func.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __uprobe_trace_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize, struct trace_event_file *trace_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c048bfe0)
Location: kernel/trace/trace_uprobe.c:928
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
c048bfe0-c048c260: __uprobe_trace_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __uprobe_trace_func(struct trace_uprobe *tu, long unsigned int func, struct pt_regs *regs, struct uprobe_cpu_buffer *ucb, int dsize, struct trace_event_file *trace_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c0000000002fc040)
Location: kernel/trace/trace_uprobe.c:928
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
c0000000002fc040-c0000000002fc398: __uprobe_trace_func (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff811d1510)
Location: kernel/trace/trace_uprobe.c:928
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811d1510-ffffffff811d174f: __uprobe_trace_func.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff811c42e0)
Location: kernel/trace/trace_uprobe.c:928
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811c42e0-ffffffff811c451f: __uprobe_trace_func.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff811cf2e0)
Location: kernel/trace/trace_uprobe.c:928
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811cf2e0-ffffffff811cf51f: __uprobe_trace_func.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff811dd580)
Location: kernel/trace/trace_uprobe.c:928
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811dd580-ffffffff811dd7bf: __uprobe_trace_func.isra.0 (STB_LOCAL)
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
