# Function: <code>seq_buf_putc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff813f01c0)
Location: lib/seq_buf.c:164
Inline: False
```
**Symbols:**

```
ffffffff813f01c0-ffffffff813f021b: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81436b30)
Location: lib/seq_buf.c:164
Inline: False
```
**Symbols:**

```
ffffffff81436b30-ffffffff81436b8b: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81453b20)
Location: lib/seq_buf.c:164
Inline: False
```
**Symbols:**

```
ffffffff81453b20-ffffffff81453b7b: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff818f3ce0)
Location: lib/seq_buf.c:164
Inline: False
```
**Symbols:**

```
ffffffff818f3ce0-ffffffff818f3d1c: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8197a6e0)
Location: lib/seq_buf.c:165
Inline: False
```
**Symbols:**

```
ffffffff8197a6e0-ffffffff8197a71c: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff819d6c80)
Location: lib/seq_buf.c:165
Inline: False
```
**Symbols:**

```
ffffffff819d6c80-ffffffff819d6cbc: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a0eec0)
Location: lib/seq_buf.c:169
Inline: False
```
**Symbols:**

```
ffffffff81a0eec0-ffffffff81a0eefc: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/seq_buf.c (0)
Location: lib/seq_buf.c:169
Inline: False
```
**Symbols:**

```
ffffffff81a7e68b-ffffffff81a7e6a8: seq_buf_putc.cold (STB_LOCAL)
ffffffff81a7e300-ffffffff81a7e349: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81ab5610)
Location: lib/seq_buf.c:169
Inline: False
```
**Symbols:**

```
ffffffff81ab5610-ffffffff81ab5646: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff815eff40)
Location: lib/seq_buf.c:170
Inline: False
```
**Symbols:**

```
ffffffff815eff40-ffffffff815eff76: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff816146a0)
Location: lib/seq_buf.c:170
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:save_cmdstr
```
**Symbols:**

```
ffffffff816146a0-ffffffff816146d6: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff815f7d30)
Location: lib/seq_buf.c:170
Inline: False
```
**Symbols:**

```
ffffffff815f7d30-ffffffff815f7d66: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff816654c0)
Location: lib/seq_buf.c:170
Inline: False
```
**Symbols:**

```
ffffffff816654c0-ffffffff816654f6: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8177fa90)
Location: lib/seq_buf.c:170
Inline: False
```
**Symbols:**

```
ffffffff8177fa90-ffffffff8177fade: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8203c830)
Location: lib/seq_buf.c:170
Inline: False
```
**Symbols:**

```
ffffffff8203c830-ffffffff8203c87e: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff820bae40)
Location: lib/seq_buf.c:202
Inline: False
```
**Symbols:**

```
ffffffff820bae40-ffffffff820bae8e: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff821953b0)
Location: lib/seq_buf.c:211
Inline: False
```
**Symbols:**

```
ffffffff821953b0-ffffffff821953fe: seq_buf_putc (STB_GLOBAL)
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
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffff800010d8fc80)
Location: lib/seq_buf.c:169
Inline: False
```
**Symbols:**

```
ffff800010d8fc80-ffff800010d8fcd0: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (c0e8a4e8)
Location: lib/seq_buf.c:169
Inline: False
```
**Symbols:**

```
c0e8a4e8-c0e8a550: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (c000000000ed2fb0)
Location: lib/seq_buf.c:169
Inline: False
```
**Symbols:**

```
c000000000ed2fb0-c000000000ed3000: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffe0008b811e)
Location: lib/seq_buf.c:169
Inline: False
```
**Symbols:**

```
ffffffe0008b811e-ffffffe0008b8150: seq_buf_putc (STB_GLOBAL)
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
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a54460)
Location: lib/seq_buf.c:169
Inline: False
```
**Symbols:**

```
ffffffff81a54460-ffffffff81a54496: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a11540)
Location: lib/seq_buf.c:169
Inline: False
```
**Symbols:**

```
ffffffff81a11540-ffffffff81a11576: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81ac0850)
Location: lib/seq_buf.c:169
Inline: False
```
**Symbols:**

```
ffffffff81ac0850-ffffffff81ac0886: seq_buf_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seq_buf_putc(struct seq_buf *s, unsigned char c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81accd20)
Location: lib/seq_buf.c:169
Inline: False
```
**Symbols:**

```
ffffffff81accd20-ffffffff81accd56: seq_buf_putc (STB_GLOBAL)
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
