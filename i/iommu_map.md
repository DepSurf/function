# Function: <code>iommu_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152a900)
Location: drivers/iommu/iommu.c:1311
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff8152a900-ffffffff8152aae0: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157dd10)
Location: drivers/iommu/iommu.c:1301
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff8157dd10-ffffffff8157df0c: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aa2b0)
Location: drivers/iommu/iommu.c:1452
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff815aa2b0-ffffffff815aa4ac: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815bff50)
Location: drivers/iommu/iommu.c:1502
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff815bff50-ffffffff815c0140: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81626600)
Location: drivers/iommu/iommu.c:1503
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff81626600-ffffffff816267fe: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1509
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff81662cd5-ffffffff81662cfa: iommu_map.cold.21 (STB_LOCAL)
ffffffff81661230-ffffffff81661415: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1585
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff816812b7-ffffffff816812dc: iommu_map.cold.23 (STB_LOCAL)
ffffffff8167faf0-ffffffff8167fcd5: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1802
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
**Symbols:**

```
ffffffff816b899e-ffffffff816b89c1: iommu_map.cold (STB_LOCAL)
ffffffff816b6ee0-ffffffff816b70ff: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1858
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffffffff816db81e-ffffffff816db841: iommu_map.cold (STB_LOCAL)
ffffffff816d9a90-ffffffff816d9caa: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178fb10)
Location: drivers/iommu/iommu.c:2231
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page
  - drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffffffff8178fb10-ffffffff8178fb5b: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bb940)
Location: drivers/iommu/iommu.c:2451
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page
  - drivers/vfio/vfio_iommu_type1.c:vfio_test_domain_fgsp
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffffffff817bb940-ffffffff817bb9b5: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179e030)
Location: drivers/iommu/iommu.c:2482
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffffffff8179e030-ffffffff8179e0ab: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81826f30)
Location: drivers/iommu/iommu.c:2555
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffffffff81826f30-ffffffff81826fab: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81966ac0)
Location: drivers/iommu/iommu.c:2332
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffffffff81966ac0-ffffffff81966b4c: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad0230)
Location: drivers/iommu/iommu.c:2396
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffffffff81ad0230-ffffffff81ad02bc: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b20038)
Location: drivers/iommu/iommu.c:2402
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffffffff81b1fb60-ffffffff81b1fc15: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b75bb0)
Location: drivers/iommu/iommu.c:2670
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffffffff81b75bb0-ffffffff81b75c78: iommu_map (STB_GLOBAL)
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
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c5ec8)
Location: drivers/iommu/iommu.c:1858
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffff8000108c5ec8-ffff8000108c6170: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bc73c)
Location: drivers/iommu/iommu.c:1858
Inline: False
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_map_resource
  - arch/arm/mm/dma-mapping.c:arm_coherent_iommu_map_page
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
  - arch/arm/mm/dma-mapping.c:__iommu_create_mapping
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_group_create_direct_mappings
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
c09bc73c-c09bc9bc: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096b510)
Location: drivers/iommu/iommu.c:1858
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/iommu/iommu.c:iommu_group_create_direct_mappings
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
c00000000096b510-c00000000096b854: iommu_map (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1858
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffffffff816a126e-ffffffff816a1291: iommu_map.cold (STB_LOCAL)
ffffffff8169f4e0-ffffffff8169f6fa: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1858
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff8167ec5e-ffffffff8167ec81: iommu_map.cold (STB_LOCAL)
ffffffff8167ced0-ffffffff8167d0ea: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1858
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff816cf4de-ffffffff816cf501: iommu_map.cold (STB_LOCAL)
ffffffff816cd750-ffffffff816cd96a: iommu_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int iommu_map(struct iommu_domain *domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1858
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_map_sg
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
```
**Symbols:**

```
ffffffff816e9a65-ffffffff816e9a88: iommu_map.cold (STB_LOCAL)
ffffffff816e7c80-ffffffff816e7eaf: iommu_map (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
