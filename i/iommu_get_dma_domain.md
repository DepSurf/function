# Function: <code>iommu_get_dma_domain</code>

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
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81680b30)
Location: drivers/iommu/iommu.c:1453
Inline: False
```
**Symbols:**

```
ffffffff81680b30-ffffffff81680b49: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b8380)
Location: drivers/iommu/iommu.c:1670
Inline: False
```
**Symbols:**

```
ffffffff816b8380-ffffffff816b8399: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816db0e0)
Location: drivers/iommu/iommu.c:1726
Inline: False
```
**Symbols:**

```
ffffffff816db0e0-ffffffff816db0f9: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178f8c0)
Location: drivers/iommu/iommu.c:2039
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/iommu/amd/iommu.c:attach_device
```
**Symbols:**

```
ffffffff8178f8c0-ffffffff8178f8d9: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bc620)
Location: drivers/iommu/iommu.c:2249
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff817bc620-ffffffff817bc639: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179f8b0)
Location: drivers/iommu/iommu.c:2280
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff8179f8b0-ffffffff8179f8c9: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff818288a0)
Location: drivers/iommu/iommu.c:2301
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff818288a0-ffffffff818288b9: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81968830)
Location: drivers/iommu/iommu.c:2062
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff81968830-ffffffff8196884f: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad25b0)
Location: drivers/iommu/iommu.c:2100
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff81ad25b0-ffffffff81ad25cf: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b20d60)
Location: drivers/iommu/iommu.c:2078
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff81b20d60-ffffffff81b20d7f: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b77990)
Location: drivers/iommu/iommu.c:2337
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff81b77990-ffffffff81b779af: iommu_get_dma_domain (STB_GLOBAL)
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
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c7030)
Location: drivers/iommu/iommu.c:1726
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_merge_boundary
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffff8000108c7030-ffff8000108c705c: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09be02c)
Location: drivers/iommu/iommu.c:1726
Inline: False
```
**Symbols:**

```
c09be02c-c09be04c: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096e3e0)
Location: drivers/iommu/iommu.c:1726
Inline: False
```
**Symbols:**

```
c00000000096e3e0-c00000000096e3f4: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
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
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a0b30)
Location: drivers/iommu/iommu.c:1726
Inline: False
```
**Symbols:**

```
ffffffff816a0b30-ffffffff816a0b49: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167e520)
Location: drivers/iommu/iommu.c:1726
Inline: False
```
**Symbols:**

```
ffffffff8167e520-ffffffff8167e539: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ceda0)
Location: drivers/iommu/iommu.c:1726
Inline: False
```
**Symbols:**

```
ffffffff816ceda0-ffffffff816cedb9: iommu_get_dma_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_dma_domain(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e9310)
Location: drivers/iommu/iommu.c:1726
Inline: False
```
**Symbols:**

```
ffffffff816e9310-ffffffff816e9329: iommu_get_dma_domain (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
