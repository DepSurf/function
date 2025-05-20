# Function: <code>xen_swiotlb_map_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff814d5090)
Location: drivers/xen/swiotlb-xen.c:378
Inline: False
```
**Symbols:**

```
ffffffff814d5090-ffffffff814d52ee: xen_swiotlb_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81525500)
Location: drivers/xen/swiotlb-xen.c:378
Inline: False
```
**Symbols:**

```
ffffffff81525500-ffffffff8152575d: xen_swiotlb_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815519c0)
Location: drivers/xen/swiotlb-xen.c:382
Inline: False
```
**Symbols:**

```
ffffffff815519c0-ffffffff81551c20: xen_swiotlb_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81566130)
Location: drivers/xen/swiotlb-xen.c:382
Inline: False
```
**Symbols:**

```
ffffffff81566130-ffffffff815663b5: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815ca2d0)
Location: drivers/xen/swiotlb-xen.c:382
Inline: False
```
**Symbols:**

```
ffffffff815ca2d0-ffffffff815ca557: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81602b60)
Location: drivers/xen/swiotlb-xen.c:368
Inline: False
```
**Symbols:**

```
ffffffff81602b60-ffffffff81602ddf: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff8161dc10)
Location: drivers/xen/swiotlb-xen.c:374
Inline: False
```
**Symbols:**

```
ffffffff8161dc10-ffffffff8161df09: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81650ab0)
Location: drivers/xen/swiotlb-xen.c:364
Inline: False
```
**Symbols:**

```
ffffffff81650ab0-ffffffff81650f48: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81673030)
Location: drivers/xen/swiotlb-xen.c:364
Inline: False
```
**Symbols:**

```
ffffffff81673030-ffffffff816734ed: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81724200)
Location: drivers/xen/swiotlb-xen.c:370
Inline: False
```
**Symbols:**

```
ffffffff81724200-ffffffff8172469b: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81740e70)
Location: drivers/xen/swiotlb-xen.c:373
Inline: False
```
**Symbols:**

```
ffffffff81740e70-ffffffff817413ee: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81724810)
Location: drivers/xen/swiotlb-xen.c:360
Inline: False
```
**Symbols:**

```
ffffffff81724810-ffffffff81724d9d: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:358
Inline: False
```
**Symbols:**

```
ffffffff817a3660-ffffffff817a3bf2: xen_swiotlb_map_page (STB_LOCAL)
ffffffff81cf672d-ffffffff81cf6751: xen_swiotlb_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:194
Inline: False
```
**Symbols:**

```
ffffffff818dd9f0-ffffffff818ddf43: xen_swiotlb_map_page (STB_LOCAL)
ffffffff81ebe89e-ffffffff81ebe8c1: xen_swiotlb_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:194
Inline: False
```
**Symbols:**

```
ffffffff81a30ee0-ffffffff81a31430: xen_swiotlb_map_page (STB_LOCAL)
ffffffff820949ff-ffffffff82094a22: xen_swiotlb_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:194
Inline: False
```
**Symbols:**

```
ffffffff81a7a6f0-ffffffff81a7ac40: xen_swiotlb_map_page (STB_LOCAL)
ffffffff82115823-ffffffff82115846: xen_swiotlb_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (0)
Location: drivers/xen/swiotlb-xen.c:194
Inline: False
```
**Symbols:**

```
ffffffff81acc860-ffffffff81accda9: xen_swiotlb_map_page (STB_LOCAL)
ffffffff821f348f-ffffffff821f34b2: xen_swiotlb_map_page.cold (STB_LOCAL)
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
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffff80001083dbe0)
Location: drivers/xen/swiotlb-xen.c:364
Inline: False
```
**Symbols:**

```
ffff80001083dbe0-ffff80001083df24: xen_swiotlb_map_page (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81638d20)
Location: drivers/xen/swiotlb-xen.c:364
Inline: False
```
**Symbols:**

```
ffffffff81638d20-ffffffff816391dd: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81666e70)
Location: drivers/xen/swiotlb-xen.c:364
Inline: False
```
**Symbols:**

```
ffffffff81666e70-ffffffff8166732d: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
dma_addr_t xen_swiotlb_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81681420)
Location: drivers/xen/swiotlb-xen.c:364
Inline: False
```
**Symbols:**

```
ffffffff81681420-ffffffff816818e2: xen_swiotlb_map_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_attrs *attrs</code> ➡️ <code>long unsigned int attrs</code>
</li>
</ul>
</details>
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
