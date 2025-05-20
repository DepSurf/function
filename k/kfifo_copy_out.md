# Function: <code>kfifo_copy_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kfifo.c (ffffffff813fe510)
Location: lib/kfifo.c:141
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_out
  - lib/kfifo.c:kfifo_out_copy_r
```
**Symbols:**

```
ffffffff813fe510-ffffffff813fe572: kfifo_copy_out.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kfifo.c (ffffffff81445b80)
Location: lib/kfifo.c:141
Inline: True
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff81445b80-ffffffff81445be2: kfifo_copy_out.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kfifo.c (ffffffff81464370)
Location: lib/kfifo.c:141
Inline: True
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff81464370-ffffffff814643d2: kfifo_copy_out.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kfifo.c (ffffffff81469350)
Location: lib/kfifo.c:141
Inline: True
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff81469350-ffffffff814693b2: kfifo_copy_out.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kfifo.c (ffffffff81495620)
Location: lib/kfifo.c:141
Inline: True
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff81495620-ffffffff81495682: kfifo_copy_out.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff814ca9c0)
Location: lib/kfifo.c:141
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff814ca9c0-ffffffff814caa28: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff814df6f0)
Location: lib/kfifo.c:141
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff814df6f0-ffffffff814df758: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8150b590)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff8150b590-ffffffff8150b5f8: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815293b0)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff815293b0-ffffffff81529418: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8158cb80)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff8158cb80-ffffffff8158cbe7: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815a95d0)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff815a95d0-ffffffff815a9637: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815b41c0)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff815b41c0-ffffffff815b4221: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8161a420)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff8161a420-ffffffff8161a481: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff816e7a60)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff816e7a60-ffffffff816e7acf: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff817d7900)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff817d7900-ffffffff817d796f: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81816b10)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff81816b10-ffffffff81816b7f: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8185bdf0)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff8185bdf0-ffffffff8185be5f: kfifo_copy_out (STB_LOCAL)
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
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffff800010633db8)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffff800010633db8-ffff800010633e3c: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (c07da180)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
c07da180-c07da1f0: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (c0000000007d9320)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
c0000000007d9320-c0000000007d93fc: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffe000461d5e)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffe000461d5e-ffffffe000461dea: kfifo_copy_out (STB_LOCAL)
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
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81521990)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff81521990-ffffffff815219f8: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81511c80)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff81511c80-ffffffff81511ce8: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8151da20)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff8151da20-ffffffff8151da88: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kfifo_copy_out(struct __kfifo *fifo, void *dst, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81537290)
Location: lib/kfifo.c:128
Inline: False
Direct callers:
  - lib/kfifo.c:kfifo_out_copy_r
  - lib/kfifo.c:__kfifo_out
```
**Symbols:**

```
ffffffff81537290-ffffffff815372f8: kfifo_copy_out (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
