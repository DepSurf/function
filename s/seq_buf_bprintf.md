# Function: <code>seq_buf_bprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff813f0080)
Location: lib/seq_buf.c:112
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff813f0080-ffffffff813f0123: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff814369f0)
Location: lib/seq_buf.c:112
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff814369f0-ffffffff81436a93: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff814539e0)
Location: lib/seq_buf.c:112
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff814539e0-ffffffff81453a83: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff818f3c10)
Location: lib/seq_buf.c:112
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff818f3c10-ffffffff818f3c78: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8197a610)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff8197a610-ffffffff8197a678: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff819d6bb0)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff819d6bb0-ffffffff819d6c18: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a0ede0)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff81a0ede0-ffffffff81a0ee48: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/seq_buf.c (0)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff81a7e651-ffffffff81a7e674: seq_buf_bprintf.cold (STB_LOCAL)
ffffffff81a7e210-ffffffff81a7e28b: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81ab5530)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff81ab5530-ffffffff81ab5596: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff815efe50)
Location: lib/seq_buf.c:114
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff815efe50-ffffffff815efeb9: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff816145b0)
Location: lib/seq_buf.c:114
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff816145b0-ffffffff81614619: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff815f7c40)
Location: lib/seq_buf.c:114
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff815f7c40-ffffffff815f7ca7: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff816653d0)
Location: lib/seq_buf.c:114
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff816653d0-ffffffff81665437: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8177f9a0)
Location: lib/seq_buf.c:114
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff8177f9a0-ffffffff8177fa15: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8203c720)
Location: lib/seq_buf.c:114
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff8203c720-ffffffff8203c795: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff820bad30)
Location: lib/seq_buf.c:146
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff820bad30-ffffffff820bada8: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff82195720)
Location: lib/seq_buf.c:154
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff82195720-ffffffff82195798: seq_buf_bprintf (STB_GLOBAL)
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
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffff800010d8fb68)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffff800010d8fb68-ffff800010d8fbec: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (c0e8a3ac)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
c0e8a3ac-c0e8a450: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (c000000000ed2e40)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
c000000000ed2e40-c000000000ed2ef8: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffe0008b8058)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffe0008b8058-ffffffe0008b80b0: seq_buf_bprintf (STB_GLOBAL)
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
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a54380)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff81a54380-ffffffff81a543e6: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a11460)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff81a11460-ffffffff81a114c6: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81ac0770)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff81ac0770-ffffffff81ac07d6: seq_buf_bprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seq_buf_bprintf(struct seq_buf *s, const char *fmt, const u32 *binary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81accc40)
Location: lib/seq_buf.c:113
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_bprintf
```
**Symbols:**

```
ffffffff81accc40-ffffffff81accca6: seq_buf_bprintf (STB_GLOBAL)
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
