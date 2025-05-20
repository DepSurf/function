# Function: <code>fetch_memory_string_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_string_size(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81167480)
Location: kernel/trace/trace_kprobe.c:191
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string_size
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116ed70)
Location: kernel/trace/trace_uprobe.c:161
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
```
**Symbols:**

```
ffffffff81167480-ffffffff81167540: fetch_memory_string_size (STB_LOCAL)
ffffffff8116ed70-ffffffff8116ed9e: fetch_memory_string_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_string_size(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81174a40)
Location: kernel/trace/trace_kprobe.c:191
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string_size
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117c48a)
Location: kernel/trace/trace_uprobe.c:161
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
```
**Symbols:**

```
ffffffff81174a40-ffffffff81174af7: fetch_memory_string_size (STB_LOCAL)
ffffffff8117c430-ffffffff8117c45e: fetch_memory_string_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_string_size(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811804c0)
Location: kernel/trace/trace_kprobe.c:202
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string_size
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118809a)
Location: kernel/trace/trace_uprobe.c:161
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
```
**Symbols:**

```
ffffffff811804c0-ffffffff81180577: fetch_memory_string_size (STB_LOCAL)
ffffffff81188040-ffffffff8118806e: fetch_memory_string_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_string_size(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81182fc0)
Location: kernel/trace/trace_kprobe.c:205
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string_size
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118ad1a)
Location: kernel/trace/trace_uprobe.c:163
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
```
**Symbols:**

```
ffffffff81182fc0-ffffffff81183036: fetch_memory_string_size (STB_LOCAL)
ffffffff8118acc0-ffffffff8118acee: fetch_memory_string_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_string_size(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81190c20)
Location: kernel/trace/trace_kprobe.c:205
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string_size
```
```
In kernel/trace/trace_uprobe.c (ffffffff811987ca)
Location: kernel/trace/trace_uprobe.c:163
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
```
**Symbols:**

```
ffffffff81190c20-ffffffff81190ca3: fetch_memory_string_size (STB_LOCAL)
ffffffff81198770-ffffffff8119879e: fetch_memory_string_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void fetch_memory_string_size(struct pt_regs *regs, void *addr, void *dest);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a6140)
Location: kernel/trace/trace_kprobe.c:229
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:fetch_symbol_string_size
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae24c)
Location: kernel/trace/trace_uprobe.c:166
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:fetch_file_offset_string_size
```
**Symbols:**

```
ffffffff811a6140-ffffffff811a61c3: fetch_memory_string_size (STB_LOCAL)
ffffffff811ae200-ffffffff811ae22c: fetch_memory_string_size (STB_LOCAL)
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
