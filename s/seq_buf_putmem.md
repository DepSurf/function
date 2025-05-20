# Function: <code>seq_buf_putmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff813f0220)
Location: lib/seq_buf.c:188
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff813f0220-ffffffff813f0297: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81436b90)
Location: lib/seq_buf.c:188
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff81436b90-ffffffff81436c07: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81453b80)
Location: lib/seq_buf.c:188
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff81453b80-ffffffff81453bf7: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff818f3d20)
Location: lib/seq_buf.c:188
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff818f3d20-ffffffff818f3d6f: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8197a720)
Location: lib/seq_buf.c:189
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff8197a720-ffffffff8197a76f: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff819d6cc0)
Location: lib/seq_buf.c:189
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff819d6cc0-ffffffff819d6d0f: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a0ef00)
Location: lib/seq_buf.c:193
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff81a0ef00-ffffffff81a0ef4f: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/seq_buf.c (0)
Location: lib/seq_buf.c:193
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff81a7e6a8-ffffffff81a7e6cd: seq_buf_putmem.cold (STB_LOCAL)
ffffffff81a7e350-ffffffff81a7e3a4: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81ab5650)
Location: lib/seq_buf.c:193
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff81ab5650-ffffffff81ab569f: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff815eff80)
Location: lib/seq_buf.c:194
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff815eff80-ffffffff815effd2: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff816146e0)
Location: lib/seq_buf.c:194
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff816146e0-ffffffff81614732: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff815f7d70)
Location: lib/seq_buf.c:194
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff815f7d70-ffffffff815f7dc7: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81665500)
Location: lib/seq_buf.c:194
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff81665500-ffffffff81665557: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8177fae0)
Location: lib/seq_buf.c:194
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff8177fae0-ffffffff8177fb39: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff8203c890)
Location: lib/seq_buf.c:194
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff8203c890-ffffffff8203c8e9: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff820baea0)
Location: lib/seq_buf.c:226
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff820baea0-ffffffff820baef9: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff821957b0)
Location: lib/seq_buf.c:236
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff821957b0-ffffffff82195809: seq_buf_putmem (STB_GLOBAL)
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
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffff800010d8fcd0)
Location: lib/seq_buf.c:193
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffff800010d8fcd0-ffff800010d8fd44: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (c0e8a550)
Location: lib/seq_buf.c:193
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
c0e8a550-c0e8a5d8: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (c000000000ed3000)
Location: lib/seq_buf.c:193
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
c000000000ed3000-c000000000ed3090: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffe0008b8150)
Location: lib/seq_buf.c:193
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffe0008b8150-ffffffe0008b81aa: seq_buf_putmem (STB_GLOBAL)
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
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a544a0)
Location: lib/seq_buf.c:193
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff81a544a0-ffffffff81a544ef: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81a11580)
Location: lib/seq_buf.c:193
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff81a11580-ffffffff81a115cf: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81ac0890)
Location: lib/seq_buf.c:193
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff81ac0890-ffffffff81ac08df: seq_buf_putmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seq_buf_putmem(struct seq_buf *s, const void *mem, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/seq_buf.c (ffffffff81accd60)
Location: lib/seq_buf.c:193
Inline: False
Direct callers:
  - kernel/trace/trace_seq.c:trace_seq_puts
  - lib/seq_buf.c:seq_buf_putmem_hex
```
**Symbols:**

```
ffffffff81accd60-ffffffff81accdaf: seq_buf_putmem (STB_GLOBAL)
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
