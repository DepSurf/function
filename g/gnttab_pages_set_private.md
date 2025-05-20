# Function: <code>gnttab_pages_set_private</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160cd90)
Location: drivers/xen/grant-table.c:776
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff8160c550-ffffffff8160c57d: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81641a34)
Location: drivers/xen/grant-table.c:776
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff816400c0-ffffffff816400ea: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81663044)
Location: drivers/xen/grant-table.c:776
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff81662680-ffffffff816626aa: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817135e6)
Location: drivers/xen/grant-table.c:774
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff81712600-ffffffff8171262a: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817304d6)
Location: drivers/xen/grant-table.c:774
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff8172f390-ffffffff8172f3ba: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81714064)
Location: drivers/xen/grant-table.c:774
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff81712dd0-ffffffff81712dfd: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81790a9c)
Location: drivers/xen/grant-table.c:781
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff8178f890-ffffffff8178f8bd: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c996b)
Location: drivers/xen/grant-table.c:847
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_get
```
**Symbols:**

```
ffffffff818c6f50-ffffffff818c6f86: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a1a734)
Location: drivers/xen/grant-table.c:847
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_get
```
**Symbols:**

```
ffffffff81a179d0-ffffffff81a17a06: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a635b4)
Location: drivers/xen/grant-table.c:865
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_get
```
**Symbols:**

```
ffffffff81a60a60-ffffffff81a60a96: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab5dd4)
Location: drivers/xen/grant-table.c:863
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/grant-table.c:gnttab_page_cache_get
```
**Symbols:**

```
ffffffff81ab3230-ffffffff81ab3266: gnttab_pages_set_private (STB_GLOBAL)
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
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082cd84)
Location: drivers/xen/grant-table.c:776
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffff80001082c2c0-ffff80001082c328: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81628eb4)
Location: drivers/xen/grant-table.c:776
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff816284f0-ffffffff8162851a: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81656e84)
Location: drivers/xen/grant-table.c:776
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff816564c0-ffffffff816564ea: gnttab_pages_set_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int gnttab_pages_set_private(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81671480)
Location: drivers/xen/grant-table.c:776
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
**Symbols:**

```
ffffffff81670aa0-ffffffff81670aca: gnttab_pages_set_private (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
