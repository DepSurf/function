# Function: <code>cma_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff81207240)
Location: mm/cma.c:439
Inline: False
```
**Symbols:**

```
ffffffff81207240-ffffffff8120733f: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff8122cbf0)
Location: mm/cma.c:440
Inline: False
```
**Symbols:**

```
ffffffff8122cbf0-ffffffff8122cce6: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff8123f120)
Location: mm/cma.c:443
Inline: False
```
**Symbols:**

```
ffffffff8123f120-ffffffff8123f210: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff8124aa10)
Location: mm/cma.c:483
Inline: False
```
**Symbols:**

```
ffffffff8124aa10-ffffffff8124aafe: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff8126ac20)
Location: mm/cma.c:483
Inline: False
```
**Symbols:**

```
ffffffff8126ac20-ffffffff8126ad10: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff8128f5f0)
Location: mm/cma.c:489
Inline: False
```
**Symbols:**

```
ffffffff8128f5f0-ffffffff8128f6e4: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff812a4510)
Location: mm/cma.c:500
Inline: False
```
**Symbols:**

```
ffffffff812a4510-ffffffff812a4604: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff812bf930)
Location: mm/cma.c:514
Inline: False
```
**Symbols:**

```
ffffffff812bf930-ffffffff812bfa29: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff812d1880)
Location: mm/cma.c:514
Inline: False
```
**Symbols:**

```
ffffffff812d1880-ffffffff812d1979: cma_release (STB_GLOBAL)
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
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffff800010377238)
Location: mm/cma.c:514
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/contiguous.c:dma_release_from_contiguous
  - kernel/dma/contiguous.c:dma_release_from_contiguous
```
**Symbols:**

```
ffff800010377238-ffff800010377384: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (c0562e98)
Location: mm/cma.c:514
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/contiguous.c:dma_release_from_contiguous
  - kernel/dma/contiguous.c:dma_release_from_contiguous
```
**Symbols:**

```
c0562e98-c0562ff4: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (c000000000469780)
Location: mm/cma.c:514
Inline: False
Direct callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_free_hpt_cma
```
**Symbols:**

```
c000000000469780-c000000000469940: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffe00024f336)
Location: mm/cma.c:514
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/contiguous.c:dma_release_from_contiguous
```
**Symbols:**

```
ffffffe00024f336-ffffffe00024f438: cma_release (STB_GLOBAL)
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
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff812c9e60)
Location: mm/cma.c:514
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/contiguous.c:dma_free_contiguous
  - kernel/dma/contiguous.c:dma_release_from_contiguous
  - kernel/dma/contiguous.c:dma_release_from_contiguous
```
**Symbols:**

```
ffffffff812c9e60-ffffffff812c9f59: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff812baea0)
Location: mm/cma.c:514
Inline: False
```
**Symbols:**

```
ffffffff812baea0-ffffffff812baf99: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff812c7c70)
Location: mm/cma.c:514
Inline: False
```
**Symbols:**

```
ffffffff812c7c70-ffffffff812c7d69: cma_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool cma_release(struct cma *cma, const struct page *pages, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff812d8970)
Location: mm/cma.c:514
Inline: False
```
**Symbols:**

```
ffffffff812d8970-ffffffff812d8a7a: cma_release (STB_GLOBAL)
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
