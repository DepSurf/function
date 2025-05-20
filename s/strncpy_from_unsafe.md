# Function: <code>strncpy_from_unsafe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81191620)
Location: mm/maccess.c:86
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:fetch_memory_string
```
**Symbols:**

```
ffffffff81191620-ffffffff81191701: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff811a5e40)
Location: mm/maccess.c:86
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:fetch_memory_string
```
**Symbols:**

```
ffffffff811a5e40-ffffffff811a5f25: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff811b61c0)
Location: mm/maccess.c:86
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:fetch_memory_string
```
**Symbols:**

```
ffffffff811b61c0-ffffffff811b62a5: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff811be0e0)
Location: mm/maccess.c:86
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:fetch_memory_string
```
**Symbols:**

```
ffffffff811be0e0-ffffffff811be17c: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff811d2da0)
Location: mm/maccess.c:86
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:fetch_memory_string
```
**Symbols:**

```
ffffffff811d2da0-ffffffff811d2e49: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff811f4120)
Location: mm/maccess.c:86
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:fetch_memory_string
```
**Symbols:**

```
ffffffff811f4120-ffffffff811f41d2: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812064b0)
Location: mm/maccess.c:86
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff812064b0-ffffffff81206562: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff8121d8f0)
Location: mm/maccess.c:124
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff8121d8f0-ffffffff8121d9a2: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff8122b390)
Location: mm/maccess.c:161
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff8122b390-ffffffff8122b442: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffff8000102b9be8)
Location: mm/maccess.c:161
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffff8000102b9be8-ffff8000102b9e38: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (c04e5ec8)
Location: mm/maccess.c:161
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
c04e5ec8-c04e5fe0: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (c000000000371cf0)
Location: mm/maccess.c:161
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
c000000000371cf0-c000000000371e30: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffe0001dd15c)
Location: mm/maccess.c:161
Inline: False
```
**Symbols:**

```
ffffffe0001dd15c-ffffffe0001dd208: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812239e0)
Location: mm/maccess.c:161
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff812239e0-ffffffff81223a92: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81216b90)
Location: mm/maccess.c:161
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81216b90-ffffffff81216c42: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81221780)
Location: mm/maccess.c:161
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81221780-ffffffff81221832: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int strncpy_from_unsafe(char *dst, const void *unsafe_addr, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81230940)
Location: mm/maccess.c:161
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
**Symbols:**

```
ffffffff81230940-ffffffff812309f2: strncpy_from_unsafe (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
