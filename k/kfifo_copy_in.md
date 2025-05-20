# Function: <code>kfifo_copy_in</code>

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
In lib/kfifo.c (ffffffff813fe3c0)
Location: lib/kfifo.c:102
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff813fe3c0-ffffffff813fe42a: kfifo_copy_in.isra.2 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81445a30)
Location: lib/kfifo.c:102
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff81445a30-ffffffff81445a95: kfifo_copy_in.isra.4 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81464220)
Location: lib/kfifo.c:102
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff81464220-ffffffff81464285: kfifo_copy_in.isra.4 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81469290)
Location: lib/kfifo.c:102
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff81469290-ffffffff814692f5: kfifo_copy_in.isra.1 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81495560)
Location: lib/kfifo.c:102
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff81495560-ffffffff814955c5: kfifo_copy_in.isra.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff814ca920)
Location: lib/kfifo.c:102
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff814ca920-ffffffff814ca98e: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff814df650)
Location: lib/kfifo.c:102
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff814df650-ffffffff814df6be: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8150b4e0)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff8150b4e0-ffffffff8150b54b: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81529300)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff81529300-ffffffff8152936b: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8158cad0)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff8158cad0-ffffffff8158cb3a: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815a9520)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff815a9520-ffffffff815a958a: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815b4110)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff815b4110-ffffffff815b4175: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8161a370)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff8161a370-ffffffff8161a3d5: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff816e79a0)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff816e79a0-ffffffff816e7a13: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff817d7820)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff817d7820-ffffffff817d7893: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81816a30)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff81816a30-ffffffff81816aa3: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8185bd10)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff8185bd10-ffffffff8185bd83: kfifo_copy_in (STB_LOCAL)
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
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffff800010633cd8)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffff800010633cd8-ffff800010633d64: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (c07da040)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in_r
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
c07da040-c07da0ac: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (c0000000007d91b0)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
c0000000007d91b0-c0000000007d928c: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffe000461c7c)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffe000461c7c-ffffffe000461d0e: kfifo_copy_in (STB_LOCAL)
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
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815218e0)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff815218e0-ffffffff8152194b: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81511bd0)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff81511bd0-ffffffff81511c3b: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8151d970)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff8151d970-ffffffff8151d9db: kfifo_copy_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kfifo_copy_in(struct __kfifo *fifo, const void *src, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815371e0)
Location: lib/kfifo.c:89
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_in
```
**Symbols:**

```
ffffffff815371e0-ffffffff8153724b: kfifo_copy_in (STB_LOCAL)
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
