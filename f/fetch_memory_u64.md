# Function: <code>fetch_memory_u64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u64(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81167340)
Location: kernel/trace/trace_kprobe.c:160
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116e870)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u64
```
**Symbols:**

```
ffffffff81167340-ffffffff81167399: fetch_memory_u64 (STB_LOCAL)
ffffffff8116e870-ffffffff8116e8c9: fetch_memory_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u64(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811749a1)
Location: kernel/trace/trace_kprobe.c:160
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117c3b8)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u64
```
**Symbols:**

```
ffffffff81174900-ffffffff81174959: fetch_memory_u64 (STB_LOCAL)
ffffffff8117c1d0-ffffffff8117c229: fetch_memory_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u64(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81180421)
Location: kernel/trace/trace_kprobe.c:171
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
```
```
In kernel/trace/trace_uprobe.c (ffffffff81187fc8)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u64
```
**Symbols:**

```
ffffffff81180380-ffffffff811803d9: fetch_memory_u64 (STB_LOCAL)
ffffffff81187de0-ffffffff81187e39: fetch_memory_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u64(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81183341)
Location: kernel/trace/trace_kprobe.c:174
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118ac48)
Location: kernel/trace/trace_uprobe.c:136
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u64
```
**Symbols:**

```
ffffffff811832a0-ffffffff811832f9: fetch_memory_u64 (STB_LOCAL)
ffffffff8118aa60-ffffffff8118aab9: fetch_memory_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u64(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81190fb1)
Location: kernel/trace/trace_kprobe.c:174
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
```
```
In kernel/trace/trace_uprobe.c (ffffffff811986f8)
Location: kernel/trace/trace_uprobe.c:136
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u64
```
**Symbols:**

```
ffffffff81190f10-ffffffff81190f69: fetch_memory_u64 (STB_LOCAL)
ffffffff81198510-ffffffff81198569: fetch_memory_u64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u64(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a64f1)
Location: kernel/trace/trace_kprobe.c:198
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae1b8)
Location: kernel/trace/trace_uprobe.c:137
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u64
```
**Symbols:**

```
ffffffff811a6450-ffffffff811a64a2: fetch_memory_u64 (STB_LOCAL)
ffffffff811adfc0-ffffffff811ae012: fetch_memory_u64 (STB_LOCAL)
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
