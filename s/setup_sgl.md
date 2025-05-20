# Function: <code>setup_sgl</code>

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
In lib/kfifo.c (ffffffff813fec80)
Location: lib/kfifo.c:347
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_dma_in_prepare
  - lib/kfifo.c:__kfifo_dma_out_prepare
```
**Symbols:**

```
ffffffff813fec80-ffffffff813fed2f: setup_sgl.isra.12 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81445ee0)
Location: lib/kfifo.c:347
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff81445ee0-ffffffff81445f91: setup_sgl.isra.14 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff814646d0)
Location: lib/kfifo.c:347
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff814646d0-ffffffff81464781: setup_sgl.isra.14 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81469740)
Location: lib/kfifo.c:347
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff81469740-ffffffff814697f4: setup_sgl.isra.12 (STB_LOCAL)
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
In lib/kfifo.c (ffffffff81495a10)
Location: lib/kfifo.c:347
Inline: True
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff81495a10-ffffffff81495ac4: setup_sgl.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff814cad60)
Location: lib/kfifo.c:347
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff814cad60-ffffffff814cae11: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff814dfa90)
Location: lib/kfifo.c:347
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff814dfa90-ffffffff814dfb41: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8150b9b0)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff8150b9b0-ffffffff8150ba61: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815297d0)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff815297d0-ffffffff81529881: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8158ce40)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_in_prepare_r
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff8158ce40-ffffffff8158cef1: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815a9850)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_in_prepare_r
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff815a9850-ffffffff815a9901: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815b4450)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_in_prepare_r
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff815b4450-ffffffff815b450b: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8161a6c0)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare_r
  - lib/kfifo.c:__kfifo_dma_in_prepare_r
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff8161a6c0-ffffffff8161a77b: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff816e8150)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare_r
  - lib/kfifo.c:__kfifo_dma_in_prepare_r
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff816e8150-ffffffff816e81f7: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff817d8080)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare_r
  - lib/kfifo.c:__kfifo_dma_in_prepare_r
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff817d8080-ffffffff817d8127: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81817290)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare_r
  - lib/kfifo.c:__kfifo_dma_in_prepare_r
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff81817290-ffffffff81817337: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8185c570)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare_r
  - lib/kfifo.c:__kfifo_dma_in_prepare_r
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff8185c570-ffffffff8185c617: setup_sgl (STB_LOCAL)
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
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffff800010634248)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffff800010634248-ffff800010634304: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (c07da570)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
c07da570-c07da620: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (c0000000007d99a0)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare_r
  - lib/kfifo.c:__kfifo_dma_in_prepare_r
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
c0000000007d99a0-c0000000007d9afc: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffe000462128)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffe000462128-ffffffe0004621e4: setup_sgl (STB_LOCAL)
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
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff81521db0)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff81521db0-ffffffff81521e61: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815120a0)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff815120a0-ffffffff81512151: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff8151de40)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff8151de40-ffffffff8151def1: setup_sgl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int setup_sgl(struct __kfifo *fifo, struct scatterlist *sgl, int nents, unsigned int len, unsigned int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kfifo.c (ffffffff815376b0)
Location: lib/kfifo.c:334
Inline: False
Direct callers:
  - lib/kfifo.c:__kfifo_dma_out_prepare
  - lib/kfifo.c:__kfifo_dma_in_prepare
```
**Symbols:**

```
ffffffff815376b0-ffffffff81537761: setup_sgl (STB_LOCAL)
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
