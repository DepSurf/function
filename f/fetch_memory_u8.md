# Function: <code>fetch_memory_u8</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u8(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81167100)
Location: kernel/trace/trace_kprobe.c:160
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116ec90)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u8
```
**Symbols:**

```
ffffffff81167100-ffffffff81167154: fetch_memory_u8 (STB_LOCAL)
ffffffff8116ec90-ffffffff8116ece4: fetch_memory_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u8(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8117475d)
Location: kernel/trace/trace_kprobe.c:160
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117c238)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u8
```
**Symbols:**

```
ffffffff811746c0-ffffffff81174714: fetch_memory_u8 (STB_LOCAL)
ffffffff8117c0b0-ffffffff8117c104: fetch_memory_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u8(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811801dd)
Location: kernel/trace/trace_kprobe.c:171
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff81187e48)
Location: kernel/trace/trace_uprobe.c:134
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u8
```
**Symbols:**

```
ffffffff81180140-ffffffff81180194: fetch_memory_u8 (STB_LOCAL)
ffffffff81187cc0-ffffffff81187d14: fetch_memory_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u8(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811830fd)
Location: kernel/trace/trace_kprobe.c:174
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118aac8)
Location: kernel/trace/trace_uprobe.c:136
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u8
```
**Symbols:**

```
ffffffff81183060-ffffffff811830b4: fetch_memory_u8 (STB_LOCAL)
ffffffff8118a940-ffffffff8118a994: fetch_memory_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u8(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81190d6d)
Location: kernel/trace/trace_kprobe.c:174
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff81198578)
Location: kernel/trace/trace_uprobe.c:136
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u8
```
**Symbols:**

```
ffffffff81190cd0-ffffffff81190d24: fetch_memory_u8 (STB_LOCAL)
ffffffff811983f0-ffffffff81198444: fetch_memory_u8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_u8(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a628d)
Location: kernel/trace/trace_kprobe.c:198
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae058)
Location: kernel/trace/trace_uprobe.c:137
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_u8
```
**Symbols:**

```
ffffffff811a61f0-ffffffff811a6241: fetch_memory_u8 (STB_LOCAL)
ffffffff811adeb0-ffffffff811adf01: fetch_memory_u8 (STB_LOCAL)
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
