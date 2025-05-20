# Function: <code>__dma_direct_alloc_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118a20)
Location: kernel/dma/direct.c:96
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff81118a20-ffffffff81118bcf: __dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81122e70)
Location: kernel/dma/direct.c:85
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff81122e70-ffffffff81123057: __dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f2b0)
Location: kernel/dma/direct.c:85
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff8112f2b0-ffffffff8112f497: __dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113dd10)
Location: kernel/dma/direct.c:112
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff8113dd10-ffffffff8113de11: __dma_direct_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811384c0)
Location: kernel/dma/direct.c:78
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff811384c0-ffffffff81138749: __dma_direct_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811395e0)
Location: kernel/dma/direct.c:78
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff811395e0-ffffffff8113984a: __dma_direct_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8115c630)
Location: kernel/dma/direct.c:87
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff8115c630-ffffffff8115c823: __dma_direct_alloc_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (ffffffff811863b0)
Location: kernel/dma/direct.c:117
Inline: True
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff811863b0-ffffffff811865c2: __dma_direct_alloc_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c1db0)
Location: kernel/dma/direct.c:117
Inline: True
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff811c1db0-ffffffff811c2013: __dma_direct_alloc_pages.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d48f0)
Location: kernel/dma/direct.c:118
Inline: True
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff811d48f0-ffffffff811d4b5f: __dma_direct_alloc_pages.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (ffffffff811e97e0)
Location: kernel/dma/direct.c:118
Inline: True
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
```
**Symbols:**

```
ffffffff811e97e0-ffffffff811e9a52: __dma_direct_alloc_pages.isra.0 (STB_LOCAL)
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
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194cf8)
Location: kernel/dma/direct.c:85
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/remap.c:arch_dma_alloc
```
**Symbols:**

```
ffff800010194cf8-ffff800010194f08: __dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e1a50)
Location: kernel/dma/direct.c:85
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
c03e1a50-c03e1c9c: __dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f5010)
Location: kernel/dma/direct.c:85
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
c0000000001f5010-c0000000001f51dc: __dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126bd6)
Location: kernel/dma/direct.c:85
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
ffffffe000126bd6-ffffffe000126d4a: __dma_direct_alloc_pages (STB_GLOBAL)
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
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127920)
Location: kernel/dma/direct.c:85
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff81127920-ffffffff81127ad7: __dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a2f0)
Location: kernel/dma/direct.c:85
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff8111a2f0-ffffffff8111a4d7: __dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125780)
Location: kernel/dma/direct.c:85
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff81125780-ffffffff81125967: __dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *__dma_direct_alloc_pages(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t gfp, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131dc0)
Location: kernel/dma/direct.c:85
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
ffffffff81131dc0-ffffffff81131fa7: __dma_direct_alloc_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>dma_addr_t *dma_handle</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, size, dma_handle, gfp, attrs</code> ➡️ <code>dev, size, gfp, attrs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
