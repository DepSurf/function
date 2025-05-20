# Function: <code>is_swiotlb_active</code>

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
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81119d60)
Location: kernel/dma/swiotlb.c:671
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff81119d60-ffffffff81119d76: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81124760)
Location: kernel/dma/swiotlb.c:688
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff81124760-ffffffff81124776: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811306e0)
Location: kernel/dma/swiotlb.c:695
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff811306e0-ffffffff811306f6: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113f4f0)
Location: kernel/dma/swiotlb.c:699
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff8113f4f0-ffffffff8113f506: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113ac30)
Location: kernel/dma/swiotlb.c:713
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff8113ac30-ffffffff8113ac46: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113aee0)
Location: kernel/dma/swiotlb.c:665
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff8113aee0-ffffffff8113aef6: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool is_swiotlb_active(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8115de10)
Location: kernel/dma/swiotlb.c:712
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff8115de10-ffffffff8115de31: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool is_swiotlb_active(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81187e40)
Location: kernel/dma/swiotlb.c:751
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_max_mapping_size
  - kernel/dma/direct.c:dma_direct_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff81187e40-ffffffff81187e69: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_swiotlb_active(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811c3bb0)
Location: kernel/dma/swiotlb.c:928
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_max_mapping_size
  - kernel/dma/direct.c:dma_direct_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff811c3bb0-ffffffff811c3bd9: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_swiotlb_active(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811d66d0)
Location: kernel/dma/swiotlb.c:953
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_max_mapping_size
  - kernel/dma/direct.c:dma_direct_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff811d66d0-ffffffff811d66f9: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_swiotlb_active(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811edcd0)
Location: kernel/dma/swiotlb.c:1525
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_direct_map_page
  - kernel/dma/direct.c:dma_direct_max_mapping_size
  - kernel/dma/direct.c:dma_direct_map_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff811edcd0-ffffffff811edcf9: is_swiotlb_active (STB_GLOBAL)
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
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffff800010197060)
Location: kernel/dma/swiotlb.c:695
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffff800010197060-ffff800010197088: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (0)
Location: include/linux/swiotlb.h:106
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c0000000001f7660)
Location: kernel/dma/swiotlb.c:695
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
c0000000001f7660-c0000000001f7684: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffe00012889c)
Location: kernel/dma/swiotlb.c:695
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffe00012889c-ffffffe0001288c2: is_swiotlb_active (STB_GLOBAL)
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
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81128e90)
Location: kernel/dma/swiotlb.c:695
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff81128e90-ffffffff81128ea6: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8111b720)
Location: kernel/dma/swiotlb.c:695
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff8111b720-ffffffff8111b736: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81126bb0)
Location: kernel/dma/swiotlb.c:695
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff81126bb0-ffffffff81126bc6: is_swiotlb_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool is_swiotlb_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81133200)
Location: kernel/dma/swiotlb.c:695
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff81133200-ffffffff81133216: is_swiotlb_active (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
</ul>
</details>
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
