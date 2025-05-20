# Function: <code>cma_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff81206f60)
Location: mm/cma.c:364
Inline: False
```
**Symbols:**

```
ffffffff81206f60-ffffffff8120723f: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff8122c930)
Location: mm/cma.c:365
Inline: False
```
**Symbols:**

```
ffffffff8122c930-ffffffff8122cbec: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff8123ee60)
Location: mm/cma.c:365
Inline: False
```
**Symbols:**

```
ffffffff8123ee60-ffffffff8123f119: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff8124a720)
Location: mm/cma.c:397
Inline: False
```
**Symbols:**

```
ffffffff8124a720-ffffffff8124aa07: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffff8126a920)
Location: mm/cma.c:397
Inline: False
```
**Symbols:**

```
ffffffff8126a920-ffffffff8126ac13: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/cma.c (0)
Location: mm/cma.c:403
Inline: False
```
**Symbols:**

```
ffffffff8128f78c-ffffffff8128f7ab: cma_alloc.cold.11 (STB_LOCAL)
ffffffff8128f310-ffffffff8128f5e1: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, bool no_warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/cma.c (0)
Location: mm/cma.c:403
Inline: False
```
**Symbols:**

```
ffffffff812a46ac-ffffffff812a46cb: cma_alloc.cold.13 (STB_LOCAL)
ffffffff812a4210-ffffffff812a450d: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, bool no_warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/cma.c (0)
Location: mm/cma.c:417
Inline: False
```
**Symbols:**

```
ffffffff812bfaef-ffffffff812bfb0e: cma_alloc.cold (STB_LOCAL)
ffffffff812bf610-ffffffff812bf921: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, bool no_warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/cma.c (0)
Location: mm/cma.c:417
Inline: False
```
**Symbols:**

```
ffffffff812d1a3f-ffffffff812d1a5e: cma_alloc.cold (STB_LOCAL)
ffffffff812d1560-ffffffff812d1871: cma_alloc (STB_GLOBAL)
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
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, bool no_warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffff800010376eb8)
Location: mm/cma.c:417
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:dma_alloc_contiguous
  - kernel/dma/contiguous.c:dma_alloc_contiguous
  - kernel/dma/contiguous.c:dma_alloc_from_contiguous
  - kernel/dma/contiguous.c:dma_alloc_from_contiguous
```
**Symbols:**

```
ffff800010376eb8-ffff800010377234: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, bool no_warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (c0562aec)
Location: mm/cma.c:417
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:dma_alloc_contiguous
  - kernel/dma/contiguous.c:dma_alloc_from_contiguous
  - kernel/dma/contiguous.c:dma_alloc_from_contiguous
```
**Symbols:**

```
c0562aec-c0562e98: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, bool no_warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (c0000000004692d0)
Location: mm/cma.c:417
Inline: False
Direct callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvm_alloc_hpt_cma
```
**Symbols:**

```
c0000000004692d0-c000000000469778: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, bool no_warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/cma.c (ffffffe00024f01a)
Location: mm/cma.c:417
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:dma_alloc_contiguous
  - kernel/dma/contiguous.c:dma_alloc_from_contiguous
```
**Symbols:**

```
ffffffe00024f01a-ffffffe00024f336: cma_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, bool no_warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/cma.c (0)
Location: mm/cma.c:417
Inline: False
Direct callers:
  - kernel/dma/contiguous.c:dma_alloc_contiguous
  - kernel/dma/contiguous.c:dma_alloc_from_contiguous
  - kernel/dma/contiguous.c:dma_alloc_from_contiguous
```
**Symbols:**

```
ffffffff812ca01f-ffffffff812ca03e: cma_alloc.cold (STB_LOCAL)
ffffffff812c9b40-ffffffff812c9e51: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, bool no_warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/cma.c (0)
Location: mm/cma.c:417
Inline: False
```
**Symbols:**

```
ffffffff812bb05f-ffffffff812bb07e: cma_alloc.cold (STB_LOCAL)
ffffffff812bab80-ffffffff812bae91: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, bool no_warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/cma.c (0)
Location: mm/cma.c:417
Inline: False
```
**Symbols:**

```
ffffffff812c7e2f-ffffffff812c7e4e: cma_alloc.cold (STB_LOCAL)
ffffffff812c7950-ffffffff812c7c61: cma_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct page *cma_alloc(struct cma *cma, size_t count, unsigned int align, bool no_warn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/cma.c (0)
Location: mm/cma.c:417
Inline: False
```
**Symbols:**

```
ffffffff812d8b3f-ffffffff812d8b5e: cma_alloc.cold (STB_LOCAL)
ffffffff812d8640-ffffffff812d8967: cma_alloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool no_warn</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
