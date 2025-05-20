# Function: <code>iommu_num_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810669d8)
Location: include/linux/iommu-helper.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/iommu-helper.h:25
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152f4d5)
Location: include/linux/iommu-helper.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:alloc_new_range
  - drivers/iommu/amd_iommu.c:__map_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106647a)
Location: include/linux/iommu-helper.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff810679fa)
Location: include/linux/iommu-helper.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff81584a5a)
Location: include/linux/iommu-helper.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a10a)
Location: include/linux/iommu-helper.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b64a)
Location: include/linux/iommu-helper.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b1b41)
Location: include/linux/iommu-helper.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106945a)
Location: include/linux/iommu-helper.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106a9d7)
Location: include/linux/iommu-helper.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c77ce)
Location: include/linux/iommu-helper.h:25
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:build_inv_iotlb_pages
  - drivers/iommu/amd_iommu.c:build_inv_iommu_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106dd0a)
Location: include/linux/iommu-helper.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106f2d7)
Location: include/linux/iommu-helper.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162e49e)
Location: include/linux/iommu-helper.h:26
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:build_inv_iotlb_pages
  - drivers/iommu/amd_iommu.c:build_inv_iommu_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81070c24)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81071e97)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff81669206)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:build_inv_iotlb_pages
  - drivers/iommu/amd_iommu.c:build_inv_iommu_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81076c17)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81077ed5)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff81687a67)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:build_inv_iotlb_pages
  - drivers/iommu/amd_iommu.c:build_inv_iommu_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a7b7)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107ba65)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bf1f1)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:build_inv_iotlb_pages
  - drivers/iommu/amd_iommu.c:build_inv_iommu_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b8a7)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107cb55)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e2591)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:build_inv_iotlb_pages
  - drivers/iommu/amd_iommu.c:build_inv_iommu_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81082ba7)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/amd/iommu.c (ffffffff81794ea5)
Location: include/linux/iommu-helper.h:33
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81084500)
Location: include/linux/iommu-helper.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a3365)
Location: include/linux/iommu-helper.h:35
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81085260)
Location: include/linux/iommu-helper.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/amd/iommu.c (ffffffff8178744a)
Location: include/linux/iommu-helper.h:35
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81094c0d)
Location: include/linux/iommu-helper.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180d675)
Location: include/linux/iommu-helper.h:35
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810a6ec8)
Location: include/linux/iommu-helper.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/amd/iommu.c (ffffffff8194f738)
Location: include/linux/iommu-helper.h:35
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c0138)
Location: include/linux/iommu-helper.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab4924)
Location: include/linux/iommu-helper.h:35
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:device_flush_iotlb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c381b)
Location: include/linux/iommu-helper.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b00f94)
Location: include/linux/iommu-helper.h:35
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:device_flush_iotlb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810cbc5b)
Location: include/linux/iommu-helper.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b512a5)
Location: include/linux/iommu-helper.h:35
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:build_inv_iotlb_pages
  - drivers/iommu/amd/iommu.c:build_inv_iommu_pages
```
</details>
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/iommu.c (c000000000052e58)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_unmap_page
  - arch/powerpc/kernel/iommu.c:iommu_map_page
  - arch/powerpc/kernel/iommu.c:ppc_iommu_unmap_sg
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a8a7)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107bb55)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a7fe1)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:build_inv_iotlb_pages
  - drivers/iommu/amd_iommu.c:build_inv_iommu_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069fd7)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b285)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816859d1)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:build_inv_iotlb_pages
  - drivers/iommu/amd_iommu.c:build_inv_iommu_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a857)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107bb05)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d6251)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:build_inv_iotlb_pages
  - drivers/iommu/amd_iommu.c:build_inv_iommu_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c957)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107dc05)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f0801)
Location: include/linux/iommu-helper.h:33
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
  - drivers/iommu/amd_iommu.c:build_inv_iotlb_pages
  - drivers/iommu/amd_iommu.c:build_inv_iommu_pages
```
</details>
</li>
</ul>

## Differences
