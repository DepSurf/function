# Function: <code>fetch_stack_u64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void fetch_stack_u64(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811670d0)
Location: kernel/trace/trace_kprobe.c:143
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116e950)
Location: kernel/trace/trace_uprobe.c:117
Inline: False
```
**Symbols:**

```
ffffffff811670d0-ffffffff811670f6: fetch_stack_u64 (STB_LOCAL)
ffffffff8116e950-ffffffff8116e9ae: fetch_stack_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void fetch_stack_u64(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81174690)
Location: kernel/trace/trace_kprobe.c:143
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117c040)
Location: kernel/trace/trace_uprobe.c:117
Inline: False
```
**Symbols:**

```
ffffffff81174690-ffffffff811746b6: fetch_stack_u64 (STB_LOCAL)
ffffffff8117c040-ffffffff8117c0a1: fetch_stack_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void fetch_stack_u64(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81180110)
Location: kernel/trace/trace_kprobe.c:154
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff81187c50)
Location: kernel/trace/trace_uprobe.c:117
Inline: False
```
**Symbols:**

```
ffffffff81180110-ffffffff81180136: fetch_stack_u64 (STB_LOCAL)
ffffffff81187c50-ffffffff81187cb1: fetch_stack_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void fetch_stack_u64(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81182f90)
Location: kernel/trace/trace_kprobe.c:157
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118a8e0)
Location: kernel/trace/trace_uprobe.c:119
Inline: False
```
**Symbols:**

```
ffffffff81182f90-ffffffff81182fb6: fetch_stack_u64 (STB_LOCAL)
ffffffff8118a8e0-ffffffff8118a93f: fetch_stack_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void fetch_stack_u64(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81190bf0)
Location: kernel/trace/trace_kprobe.c:157
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198390)
Location: kernel/trace/trace_uprobe.c:119
Inline: False
```
**Symbols:**

```
ffffffff81190bf0-ffffffff81190c16: fetch_stack_u64 (STB_LOCAL)
ffffffff81198390-ffffffff811983ef: fetch_stack_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void fetch_stack_u64(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a6110)
Location: kernel/trace/trace_kprobe.c:181
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ade50)
Location: kernel/trace/trace_uprobe.c:120
Inline: False
```
**Symbols:**

```
ffffffff811a6110-ffffffff811a6131: fetch_stack_u64 (STB_LOCAL)
ffffffff811ade50-ffffffff811adeaf: fetch_stack_u64 (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
</ul>
