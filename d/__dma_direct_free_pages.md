# Function: <code>__dma_direct_free_pages</code>

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
void __dma_direct_free_pages(struct device *dev, size_t size, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118cc0)
Location: kernel/dma/direct.c:178
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff81118cc0-ffffffff81118ce7: __dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __dma_direct_free_pages(struct device *dev, size_t size, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112321e)
Location: kernel/dma/direct.c:178
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff81123190-ffffffff811231b7: __dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __dma_direct_free_pages(struct device *dev, size_t size, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f65e)
Location: kernel/dma/direct.c:178
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff8112f5d0-ffffffff8112f5f7: __dma_direct_free_pages (STB_GLOBAL)
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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8115d16d)
Location: kernel/dma/direct.c:78
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81186f9a)
Location: kernel/dma/direct.c:97
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c2a6a)
Location: kernel/dma/direct.c:97
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d55aa)
Location: kernel/dma/direct.c:98
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811ea49a)
Location: kernel/dma/direct.c:98
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __dma_direct_free_pages(struct device *dev, size_t size, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010195010)
Location: kernel/dma/direct.c:178
Inline: True
Direct callers:
  - kernel/dma/remap.c:arch_dma_free
  - kernel/dma/remap.c:arch_dma_alloc
```
**Symbols:**

```
ffff800010195010-ffff800010195054: __dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __dma_direct_free_pages(struct device *dev, size_t size, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e1dc4)
Location: kernel/dma/direct.c:178
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc_pages
```
**Symbols:**

```
c03e1dd8-c03e1e00: __dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __dma_direct_free_pages(struct device *dev, size_t size, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f542c)
Location: kernel/dma/direct.c:178
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
c0000000001f5380-c0000000001f53cc: __dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __dma_direct_free_pages(struct device *dev, size_t size, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126dd8)
Location: kernel/dma/direct.c:178
Inline: True
```
**Symbols:**

```
ffffffe000126dd8-ffffffe000126e12: __dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __dma_direct_free_pages(struct device *dev, size_t size, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127c8d)
Location: kernel/dma/direct.c:178
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff81127c10-ffffffff81127c29: __dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __dma_direct_free_pages(struct device *dev, size_t size, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a69e)
Location: kernel/dma/direct.c:178
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff8111a610-ffffffff8111a637: __dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __dma_direct_free_pages(struct device *dev, size_t size, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125b2e)
Location: kernel/dma/direct.c:178
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff81125aa0-ffffffff81125ac7: __dma_direct_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __dma_direct_free_pages(struct device *dev, size_t size, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113216e)
Location: kernel/dma/direct.c:178
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff811320e0-ffffffff81132107: __dma_direct_free_pages (STB_GLOBAL)
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
