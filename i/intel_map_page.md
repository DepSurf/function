# Function: <code>intel_map_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153af70)
Location: drivers/iommu/intel-iommu.c:3491
Inline: False
```
**Symbols:**

```
ffffffff8153af70-ffffffff8153afab: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158fa40)
Location: drivers/iommu/intel-iommu.c:3552
Inline: False
```
**Symbols:**

```
ffffffff8158fa40-ffffffff8158fa7b: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bd280)
Location: drivers/iommu/intel-iommu.c:3643
Inline: False
```
**Symbols:**

```
ffffffff815bd280-ffffffff815bd2b5: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d2eb0)
Location: drivers/iommu/intel-iommu.c:3639
Inline: False
```
**Symbols:**

```
ffffffff815d2eb0-ffffffff815d2ee5: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81639bb0)
Location: drivers/iommu/intel-iommu.c:3647
Inline: False
```
**Symbols:**

```
ffffffff81639bb0-ffffffff81639be5: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81674d20)
Location: drivers/iommu/intel-iommu.c:3695
Inline: False
```
**Symbols:**

```
ffffffff81674d20-ffffffff81674d55: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81693370)
Location: drivers/iommu/intel-iommu.c:3713
Inline: False
```
**Symbols:**

```
ffffffff81693370-ffffffff8169338a: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816cb620)
Location: drivers/iommu/intel-iommu.c:3547
Inline: True
```
**Symbols:**

```
ffffffff816cb620-ffffffff816cb6b5: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ef110)
Location: drivers/iommu/intel-iommu.c:3562
Inline: True
```
**Symbols:**

```
ffffffff816ef110-ffffffff816ef1a5: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a6160)
Location: drivers/iommu/intel/iommu.c:3448
Inline: False
```
**Symbols:**

```
ffffffff817a6160-ffffffff817a6195: intel_map_page (STB_LOCAL)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
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
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b4900)
Location: drivers/iommu/intel-iommu.c:3562
Inline: True
```
**Symbols:**

```
ffffffff816b4900-ffffffff816b4995: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81692540)
Location: drivers/iommu/intel-iommu.c:3562
Inline: True
```
**Symbols:**

```
ffffffff81692540-ffffffff816925d5: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e2dd0)
Location: drivers/iommu/intel-iommu.c:3562
Inline: True
```
**Symbols:**

```
ffffffff816e2dd0-ffffffff816e2e65: intel_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
dma_addr_t intel_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fd450)
Location: drivers/iommu/intel-iommu.c:3562
Inline: True
```
**Symbols:**

```
ffffffff816fd450-ffffffff816fd4e5: intel_map_page (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
