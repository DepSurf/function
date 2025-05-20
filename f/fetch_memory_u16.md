# Function: <code>fetch_memory_u16</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u16(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811671c0)
Location: kernel/trace/trace_kprobe.c:160
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116ebb0)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u16
```
**Symbols:**

```
ffffffff811671c0-ffffffff81167217: fetch_memory_u16 (STB_LOCAL)
ffffffff8116ebb0-ffffffff8116ec07: fetch_memory_u16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u16(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8117481f)
Location: kernel/trace/trace_kprobe.c:160
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117c2b8)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u16
```
**Symbols:**

```
ffffffff81174780-ffffffff811747d7: fetch_memory_u16 (STB_LOCAL)
ffffffff8117c110-ffffffff8117c167: fetch_memory_u16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u16(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8118029f)
Location: kernel/trace/trace_kprobe.c:171
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
```
```
In kernel/trace/trace_uprobe.c (ffffffff81187ec8)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u16
```
**Symbols:**

```
ffffffff81180200-ffffffff81180257: fetch_memory_u16 (STB_LOCAL)
ffffffff81187d20-ffffffff81187d77: fetch_memory_u16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u16(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811831bf)
Location: kernel/trace/trace_kprobe.c:174
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118ab48)
Location: kernel/trace/trace_uprobe.c:136
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u16
```
**Symbols:**

```
ffffffff81183120-ffffffff81183177: fetch_memory_u16 (STB_LOCAL)
ffffffff8118a9a0-ffffffff8118a9f7: fetch_memory_u16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u16(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81190e2f)
Location: kernel/trace/trace_kprobe.c:174
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
```
```
In kernel/trace/trace_uprobe.c (ffffffff811985f8)
Location: kernel/trace/trace_uprobe.c:136
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u16
```
**Symbols:**

```
ffffffff81190d90-ffffffff81190de7: fetch_memory_u16 (STB_LOCAL)
ffffffff81198450-ffffffff811984a7: fetch_memory_u16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u16(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a635f)
Location: kernel/trace/trace_kprobe.c:198
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae0c8)
Location: kernel/trace/trace_uprobe.c:137
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u16
```
**Symbols:**

```
ffffffff811a62c0-ffffffff811a6312: fetch_memory_u16 (STB_LOCAL)
ffffffff811adf10-ffffffff811adf62: fetch_memory_u16 (STB_LOCAL)
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
