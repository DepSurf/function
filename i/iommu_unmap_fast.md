# Function: <code>iommu_unmap_fast</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816265e0)
Location: drivers/iommu/iommu.c:1627
Inline: False
```
**Symbols:**

```
ffffffff816265e0-ffffffff816265f2: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81661210)
Location: drivers/iommu/iommu.c:1633
Inline: False
```
**Symbols:**

```
ffffffff81661210-ffffffff81661222: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167fad0)
Location: drivers/iommu/iommu.c:1709
Inline: False
```
**Symbols:**

```
ffffffff8167fad0-ffffffff8167fae2: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b6ec0)
Location: drivers/iommu/iommu.c:1930
Inline: False
```
**Symbols:**

```
ffffffff816b6ec0-ffffffff816b6ed2: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d9a80)
Location: drivers/iommu/iommu.c:1987
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff816d9a80-ffffffff816d9a90: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178ea10)
Location: drivers/iommu/iommu.c:2314
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/vfio/vfio_iommu_type1.c:unmap_unpin_fast
```
**Symbols:**

```
ffffffff8178ea10-ffffffff8178ea20: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bac40)
Location: drivers/iommu/iommu.c:2534
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/vfio/vfio_iommu_type1.c:unmap_unpin_fast
```
**Symbols:**

```
ffffffff817bac40-ffffffff817bac50: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179d550)
Location: drivers/iommu/iommu.c:2565
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff8179d550-ffffffff8179d560: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff818262a0)
Location: drivers/iommu/iommu.c:2651
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff818262a0-ffffffff818262b0: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81966580)
Location: drivers/iommu/iommu.c:2428
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff81966580-ffffffff8196659c: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acff50)
Location: drivers/iommu/iommu.c:2492
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff81acff50-ffffffff81acff6c: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1f200)
Location: drivers/iommu/iommu.c:2504
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff81b1f200-ffffffff81b1f21c: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b75640)
Location: drivers/iommu/iommu.c:2768
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffffffff81b75640-ffffffff81b7565c: iommu_unmap_fast (STB_GLOBAL)
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
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c5960)
Location: drivers/iommu/iommu.c:1987
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap
```
**Symbols:**

```
ffff8000108c5960-ffff8000108c59ac: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bc720)
Location: drivers/iommu/iommu.c:1987
Inline: False
```
**Symbols:**

```
c09bc720-c09bc73c: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096b4f0)
Location: drivers/iommu/iommu.c:1987
Inline: False
```
**Symbols:**

```
c00000000096b4f0-c00000000096b504: iommu_unmap_fast (STB_GLOBAL)
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
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169f4d0)
Location: drivers/iommu/iommu.c:1987
Inline: False
```
**Symbols:**

```
ffffffff8169f4d0-ffffffff8169f4e0: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167cec0)
Location: drivers/iommu/iommu.c:1987
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff8167cec0-ffffffff8167ced0: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cd740)
Location: drivers/iommu/iommu.c:1987
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff816cd740-ffffffff816cd750: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t iommu_unmap_fast(struct iommu_domain *domain, long unsigned int iova, size_t size, struct iommu_iotlb_gather *iotlb_gather);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e7c70)
Location: drivers/iommu/iommu.c:1987
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff816e7c70-ffffffff816e7c80: iommu_unmap_fast (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_iotlb_gather *iotlb_gather</code>
</li>
</ul>
</details>
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
