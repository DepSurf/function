# Function: <code>fetch_stack_u32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void fetch_stack_u32(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811670a0)
Location: kernel/trace/trace_kprobe.c:143
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116e9b0)
Location: kernel/trace/trace_uprobe.c:117
Inline: False
```
**Symbols:**

```
ffffffff811670a0-ffffffff811670c4: fetch_stack_u32 (STB_LOCAL)
ffffffff8116e9b0-ffffffff8116ea0c: fetch_stack_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void fetch_stack_u32(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81174660)
Location: kernel/trace/trace_kprobe.c:143
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117bfe0)
Location: kernel/trace/trace_uprobe.c:117
Inline: False
```
**Symbols:**

```
ffffffff81174660-ffffffff81174685: fetch_stack_u32 (STB_LOCAL)
ffffffff8117bfe0-ffffffff8117c040: fetch_stack_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void fetch_stack_u32(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811800e0)
Location: kernel/trace/trace_kprobe.c:154
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff81187bf0)
Location: kernel/trace/trace_uprobe.c:117
Inline: False
```
**Symbols:**

```
ffffffff811800e0-ffffffff81180105: fetch_stack_u32 (STB_LOCAL)
ffffffff81187bf0-ffffffff81187c50: fetch_stack_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void fetch_stack_u32(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81182f60)
Location: kernel/trace/trace_kprobe.c:157
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118a880)
Location: kernel/trace/trace_uprobe.c:119
Inline: False
```
**Symbols:**

```
ffffffff81182f60-ffffffff81182f84: fetch_stack_u32 (STB_LOCAL)
ffffffff8118a880-ffffffff8118a8dd: fetch_stack_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void fetch_stack_u32(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81190bc0)
Location: kernel/trace/trace_kprobe.c:157
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198330)
Location: kernel/trace/trace_uprobe.c:119
Inline: False
```
**Symbols:**

```
ffffffff81190bc0-ffffffff81190be4: fetch_stack_u32 (STB_LOCAL)
ffffffff81198330-ffffffff8119838d: fetch_stack_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void fetch_stack_u32(struct pt_regs *regs, void *offset, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a60f0)
Location: kernel/trace/trace_kprobe.c:181
Inline: False
```
```
In kernel/trace/trace_uprobe.c (ffffffff811addf0)
Location: kernel/trace/trace_uprobe.c:120
Inline: False
```
**Symbols:**

```
ffffffff811a60f0-ffffffff811a610f: fetch_stack_u32 (STB_LOCAL)
ffffffff811addf0-ffffffff811ade4d: fetch_stack_u32 (STB_LOCAL)
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
