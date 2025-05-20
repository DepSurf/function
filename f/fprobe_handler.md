# Function: <code>fprobe_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fprobe_handler(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff81268560)
Location: kernel/trace/fprobe.c:22
Inline: True
```
**Symbols:**

```
ffffffff812686d0-ffffffff81268708: fprobe_handler (STB_LOCAL)
ffffffff81268560-ffffffff812686c3: fprobe_handler.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fprobe_handler(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812ba7a0)
Location: kernel/trace/fprobe.c:22
Inline: True
```
**Symbols:**

```
ffffffff812ba920-ffffffff812ba958: fprobe_handler (STB_LOCAL)
ffffffff812ba7a0-ffffffff812ba903: fprobe_handler.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fprobe_handler(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812de9f0)
Location: kernel/trace/fprobe.c:60
Inline: True
```
**Symbols:**

```
ffffffff812de9f0-ffffffff812dea22: fprobe_handler (STB_LOCAL)
ffffffff812de740-ffffffff812de9df: fprobe_handler.part.0 (STB_LOCAL)
ffffffff820ddf73-ffffffff820ddf87: fprobe_handler.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fprobe_handler(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812fcae0)
Location: kernel/trace/fprobe.c:60
Inline: True
```
**Symbols:**

```
ffffffff812fcae0-ffffffff812fcb12: fprobe_handler (STB_LOCAL)
ffffffff812fc830-ffffffff812fcacf: fprobe_handler.part.0 (STB_LOCAL)
ffffffff821b9d91-ffffffff821b9da5: fprobe_handler.part.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
