# Function: <code>fetch_memory_u32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u32(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81167280)
Location: kernel/trace/trace_kprobe.c:160
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116ead0)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u32
```
**Symbols:**

```
ffffffff81167280-ffffffff811672d6: fetch_memory_u32 (STB_LOCAL)
ffffffff8116ead0-ffffffff8116eb26: fetch_memory_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u32(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811748e0)
Location: kernel/trace/trace_kprobe.c:160
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117c338)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u32
```
**Symbols:**

```
ffffffff81174840-ffffffff81174896: fetch_memory_u32 (STB_LOCAL)
ffffffff8117c170-ffffffff8117c1c6: fetch_memory_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u32(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81180360)
Location: kernel/trace/trace_kprobe.c:171
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
```
```
In kernel/trace/trace_uprobe.c (ffffffff81187f48)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u32
```
**Symbols:**

```
ffffffff811802c0-ffffffff81180316: fetch_memory_u32 (STB_LOCAL)
ffffffff81187d80-ffffffff81187dd6: fetch_memory_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u32(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81183280)
Location: kernel/trace/trace_kprobe.c:174
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118abc8)
Location: kernel/trace/trace_uprobe.c:136
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u32
```
**Symbols:**

```
ffffffff811831e0-ffffffff81183236: fetch_memory_u32 (STB_LOCAL)
ffffffff8118aa00-ffffffff8118aa56: fetch_memory_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u32(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81190ef0)
Location: kernel/trace/trace_kprobe.c:174
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198678)
Location: kernel/trace/trace_uprobe.c:136
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u32
```
**Symbols:**

```
ffffffff81190e50-ffffffff81190ea6: fetch_memory_u32 (STB_LOCAL)
ffffffff811984b0-ffffffff81198506: fetch_memory_u32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u32(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a6420)
Location: kernel/trace/trace_kprobe.c:198
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae148)
Location: kernel/trace/trace_uprobe.c:137
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u32
```
**Symbols:**

```
ffffffff811a6390-ffffffff811a63e0: fetch_memory_u32 (STB_LOCAL)
ffffffff811adf70-ffffffff811adfc0: fetch_memory_u32 (STB_LOCAL)
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
