# Function: <code>fprobe_kprobe_handler</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fprobe_kprobe_handler(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff81268b60)
Location: kernel/trace/fprobe.c:59
Inline: True
```
**Symbols:**

```
ffffffff81268b60-ffffffff81268bd9: fprobe_kprobe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fprobe_kprobe_handler(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812bae00)
Location: kernel/trace/fprobe.c:59
Inline: True
```
**Symbols:**

```
ffffffff812bae00-ffffffff812bae79: fprobe_kprobe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fprobe_kprobe_handler(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812de1a0)
Location: kernel/trace/fprobe.c:84
Inline: True
```
**Symbols:**

```
ffffffff812ddec0-ffffffff812de190: fprobe_kprobe_handler.part.0 (STB_LOCAL)
ffffffff820ddf5f-ffffffff820ddf73: fprobe_kprobe_handler.part.0.cold (STB_LOCAL)
ffffffff812de1a0-ffffffff812de1d2: fprobe_kprobe_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fprobe_kprobe_handler(long unsigned int ip, long unsigned int parent_ip, struct ftrace_ops *ops, struct ftrace_regs *fregs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/fprobe.c (ffffffff812fc290)
Location: kernel/trace/fprobe.c:84
Inline: True
```
**Symbols:**

```
ffffffff812fbfb0-ffffffff812fc280: fprobe_kprobe_handler.part.0 (STB_LOCAL)
ffffffff821b9d7d-ffffffff821b9d91: fprobe_kprobe_handler.part.0.cold (STB_LOCAL)
ffffffff812fc290-ffffffff812fc2c2: fprobe_kprobe_handler (STB_LOCAL)
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
