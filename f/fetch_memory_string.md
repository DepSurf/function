# Function: <code>fetch_memory_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void fetch_memory_string(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81167410)
Location: kernel/trace/trace_kprobe.c:165
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116edf0)
Location: kernel/trace/trace_uprobe.c:139
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string
```
**Symbols:**

```
ffffffff81167410-ffffffff81167452: fetch_memory_string (STB_LOCAL)
ffffffff8116edf0-ffffffff8116ee39: fetch_memory_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void fetch_memory_string(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811749d0)
Location: kernel/trace/trace_kprobe.c:165
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117c4b0)
Location: kernel/trace/trace_uprobe.c:139
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string
```
**Symbols:**

```
ffffffff811749d0-ffffffff81174a12: fetch_memory_string (STB_LOCAL)
ffffffff8117c4b0-ffffffff8117c4f9: fetch_memory_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void fetch_memory_string(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81180450)
Location: kernel/trace/trace_kprobe.c:176
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811880c0)
Location: kernel/trace/trace_uprobe.c:139
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string
```
**Symbols:**

```
ffffffff81180450-ffffffff81180492: fetch_memory_string (STB_LOCAL)
ffffffff811880c0-ffffffff81188109: fetch_memory_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void fetch_memory_string(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81183370)
Location: kernel/trace/trace_kprobe.c:179
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118ad40)
Location: kernel/trace/trace_uprobe.c:141
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string
```
**Symbols:**

```
ffffffff81183370-ffffffff811833b6: fetch_memory_string (STB_LOCAL)
ffffffff8118ad40-ffffffff8118ad8d: fetch_memory_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void fetch_memory_string(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81190fe0)
Location: kernel/trace/trace_kprobe.c:179
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811987f0)
Location: kernel/trace/trace_uprobe.c:141
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string
```
**Symbols:**

```
ffffffff81190fe0-ffffffff81191026: fetch_memory_string (STB_LOCAL)
ffffffff811987f0-ffffffff8119883d: fetch_memory_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void fetch_memory_string(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a6520)
Location: kernel/trace/trace_kprobe.c:203
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae280)
Location: kernel/trace/trace_uprobe.c:142
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string
```
**Symbols:**

```
ffffffff811a6520-ffffffff811a6565: fetch_memory_string (STB_LOCAL)
ffffffff811ae280-ffffffff811ae2ed: fetch_memory_string (STB_LOCAL)
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
