# Function: <code>seq_buf_vprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff813eff80)
Location: lib/seq_buf.c:56
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/nmi_backtrace.c:nmi_vprintk
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff813eff80-ffffffff813f0007: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff814368f0)
Location: lib/seq_buf.c:56
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff814368f0-ffffffff81436977: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff814538e0)
Location: lib/seq_buf.c:56
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff814538e0-ffffffff81453967: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff818f3b40)
Location: lib/seq_buf.c:56
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff818f3b40-ffffffff818f3b97: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8197a540)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff8197a540-ffffffff8197a597: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff819d6ae0)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff819d6ae0-ffffffff819d6b37: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a0ed10)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff81a0ed10-ffffffff81a0ed67: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/seq_buf.c (0)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff81a7e632-ffffffff81a7e651: seq_buf_vprintf.cold (STB_LOCAL)
ffffffff81a7e130-ffffffff81a7e195: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81ab5460)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff81ab5460-ffffffff81ab54b7: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff815efd61)
Location: lib/seq_buf.c:57
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_printf
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
```
**Symbols:**

```
ffffffff815efdf0-ffffffff815efe4b: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff816144c1)
Location: lib/seq_buf.c:57
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_printf
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
```
**Symbols:**

```
ffffffff81614550-ffffffff816145ab: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff815f7b4e)
Location: lib/seq_buf.c:57
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_printf
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
```
**Symbols:**

```
ffffffff815f7be0-ffffffff815f7c3e: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff816652de)
Location: lib/seq_buf.c:57
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_printf
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
```
**Symbols:**

```
ffffffff81665370-ffffffff816653ce: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8177f87f)
Location: lib/seq_buf.c:57
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_printf
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
```
**Symbols:**

```
ffffffff8177f930-ffffffff8177f99a: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8203c5cf)
Location: lib/seq_buf.c:57
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_printf
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
```
**Symbols:**

```
ffffffff8203c6a0-ffffffff8203c70a: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff820babdf)
Location: lib/seq_buf.c:57
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_printf
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
```
**Symbols:**

```
ffffffff820bacb0-ffffffff820bad1a: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff821955cf)
Location: lib/seq_buf.c:67
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_printf
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
```
**Symbols:**

```
ffffffff821956a0-ffffffff8219570a: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffff800010d8fa60)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffff800010d8fa60-ffff800010d8faf0: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (c0e8a2bc)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
c0e8a2bc-c0e8a350: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (c000000000ed2d40)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
c000000000ed2d40-c000000000ed2de8: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, va_list args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffe0008b7fda)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffe0008b7fda-ffffffe0008b802a: seq_buf_vprintf (STB_GLOBAL)
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
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a542b0)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff81a542b0-ffffffff81a54307: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a11390)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff81a11390-ffffffff81a113e7: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81ac06a0)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff81ac06a0-ffffffff81ac06f7: seq_buf_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seq_buf_vprintf(struct seq_buf *s, const char *fmt, struct __va_list_tag *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81accb70)
Location: lib/seq_buf.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_last_cmd_printf
  - kernel/trace/trace_seq.c:trace_seq_vprintf
  - kernel/trace/trace_seq.c:trace_seq_printf
  - lib/seq_buf.c:seq_buf_printf
```
**Symbols:**

```
ffffffff81accb70-ffffffff81accbc7: seq_buf_vprintf (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
