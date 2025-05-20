# Function: <code>iommu_iova_to_phys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81529fd0)
Location: drivers/iommu/iommu.c:1270
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff81529fd0-ffffffff81529fed: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157e72a)
Location: drivers/iommu/iommu.c:1260
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff8157d4d0-ffffffff8157d4ed: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aace2)
Location: drivers/iommu/iommu.c:1411
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff815a9a40-ffffffff815a9a5d: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c085d)
Location: drivers/iommu/iommu.c:1461
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff815bf780-ffffffff815bf79d: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81626f2e)
Location: drivers/iommu/iommu.c:1462
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff81625bd0-ffffffff81625bf0: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81661b6c)
Location: drivers/iommu/iommu.c:1468
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff816608f0-ffffffff81660910: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8168022c)
Location: drivers/iommu/iommu.c:1544
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff8167eda0-ffffffff8167edc0: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b5c50)
Location: drivers/iommu/iommu.c:1761
Inline: True
```
**Symbols:**

```
ffffffff816b5c50-ffffffff816b5c70: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d8950)
Location: drivers/iommu/iommu.c:1817
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff816d8950-ffffffff816d8970: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178d120)
Location: drivers/iommu/iommu.c:2130
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff8178d120-ffffffff8178d140: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b8ae0)
Location: drivers/iommu/iommu.c:2340
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff817b8ae0-ffffffff817b8b00: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179bd50)
Location: drivers/iommu/iommu.c:2371
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff8179bd50-ffffffff8179bd70: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff818256d0)
Location: drivers/iommu/iommu.c:2392
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:__iommu_dma_unmap_swiotlb
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff818256d0-ffffffff818256f9: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81965560)
Location: drivers/iommu/iommu.c:2169
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff81965560-ffffffff8196559d: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81aced50)
Location: drivers/iommu/iommu.c:2233
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
```
**Symbols:**

```
ffffffff81aced50-ffffffff81aced8d: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1ffff)
Location: drivers/iommu/iommu.c:2252
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
```
**Symbols:**

```
ffffffff81b1d6c0-ffffffff81b1d6fd: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b765d2)
Location: drivers/iommu/iommu.c:2541
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
```
**Symbols:**

```
ffffffff81b73eb0-ffffffff81b73eed: iommu_iova_to_phys (STB_GLOBAL)
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
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c4048)
Location: drivers/iommu/iommu.c:1817
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
```
**Symbols:**

```
ffff8000108c4048-ffff8000108c4098: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bcc40)
Location: drivers/iommu/iommu.c:1817
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_create_direct_mappings
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_sync_single_for_device
  - arch/arm/mm/dma-mapping.c:arm_iommu_sync_single_for_cpu
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_page
```
**Symbols:**

```
c09bb528-c09bb55c: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096bb80)
Location: drivers/iommu/iommu.c:1817
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_create_direct_mappings
```
**Symbols:**

```
c000000000969cc0-c000000000969d18: iommu_iova_to_phys (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169e3a0)
Location: drivers/iommu/iommu.c:1817
Inline: True
```
**Symbols:**

```
ffffffff8169e3a0-ffffffff8169e3c0: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167bd90)
Location: drivers/iommu/iommu.c:1817
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff8167bd90-ffffffff8167bdb0: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cc610)
Location: drivers/iommu/iommu.c:1817
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff816cc610-ffffffff816cc630: iommu_iova_to_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
phys_addr_t iommu_iova_to_phys(struct iommu_domain *domain, dma_addr_t iova);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e6ae0)
Location: drivers/iommu/iommu.c:1817
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff816e6ae0-ffffffff816e6b00: iommu_iova_to_phys (STB_GLOBAL)
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
