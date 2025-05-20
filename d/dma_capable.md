# Function: <code>dma_capable</code>

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
In arch/x86/kernel/pci-nommu.c (ffffffff81036da1)
Location: arch/x86/include/asm/dma-mapping.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/pci-nommu.c:check_addr
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066bb3)
Location: arch/x86/include/asm/dma-mapping.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In lib/swiotlb.c (ffffffff81412712)
Location: arch/x86/include/asm/dma-mapping.h:65
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_sg_attrs
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d4c5e)
Location: arch/x86/include/asm/dma-mapping.h:65
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/pci-nommu.c (ffffffff81035fa1)
Location: arch/x86/include/asm/dma-mapping.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/pci-nommu.c:check_addr
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066a03)
Location: arch/x86/include/asm/dma-mapping.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In lib/swiotlb.c (ffffffff8145a9bd)
Location: arch/x86/include/asm/dma-mapping.h:62
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_page
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81525bae)
Location: arch/x86/include/asm/dma-mapping.h:62
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/pci-nommu.c (ffffffff81035cd1)
Location: arch/x86/include/asm/dma-mapping.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/pci-nommu.c:check_addr
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a680)
Location: arch/x86/include/asm/dma-mapping.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In lib/swiotlb.c (ffffffff81479196)
Location: arch/x86/include/asm/dma-mapping.h:62
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_page
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815520b3)
Location: arch/x86/include/asm/dma-mapping.h:62
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/pci-nommu.c (ffffffff81033ca6)
Location: arch/x86/include/asm/dma-mapping.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/pci-nommu.c:check_addr
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069c72)
Location: arch/x86/include/asm/dma-mapping.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In lib/swiotlb.c (ffffffff814822be)
Location: arch/x86/include/asm/dma-mapping.h:50
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_page
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815661a2)
Location: arch/x86/include/asm/dma-mapping.h:50
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/pci-nommu.c (ffffffff81035fe6)
Location: arch/x86/include/asm/dma-mapping.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/pci-nommu.c:check_addr
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106e522)
Location: arch/x86/include/asm/dma-mapping.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In lib/swiotlb.c (ffffffff814be246)
Location: arch/x86/include/asm/dma-mapping.h:51
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_page
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815ca342)
Location: arch/x86/include/asm/dma-mapping.h:51
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81071242)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In kernel/dma/direct.c (ffffffff8110cfe7)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - kernel/dma/direct.c:check_addr
```
```
In kernel/dma/swiotlb.c (ffffffff8110e074)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map_page
  - kernel/dma/swiotlb.c:swiotlb_map_page
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81602bd2)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107714f)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/direct.c (ffffffff811187dc)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff81119bf3)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161dc83)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b0d4)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/direct.c (ffffffff81122dc5)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff81124626)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81650b21)
Location: include/linux/dma-direct.h:25
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c1c4)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/direct.c (ffffffff8112f1fc)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811305a4)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff816730a0)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810832cd)
Location: include/linux/dma-direct.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/direct.c (ffffffff8113dc18)
Location: include/linux/dma-direct.h:54
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff8113f382)
Location: include/linux/dma-direct.h:54
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8172426b)
Location: include/linux/dma-direct.h:54
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81084ab6)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/mapping.c (ffffffff81137df6)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811395b5)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/swiotlb.c (ffffffff8113aa52)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81740ef3)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81085712)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/mapping.c (ffffffff81138eb8)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff8113a685)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/swiotlb.c (ffffffff8113bdb2)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81724893)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81094b3b)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/mapping.c (ffffffff8115bd32)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff8115d5a0)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff8115eeb2)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a36e3)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810a6dfa)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/mapping.c (ffffffff81185926)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff81187490)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff8118904f)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dda77)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810c006a)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/mapping.c (ffffffff811c128f)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811c302e)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811c5436)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30f67)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810c3747)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/mapping.c (ffffffff811d3d0f)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811d5b6e)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811d8004)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a7a777)
Location: include/linux/dma-direct.h:99
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810cbb87)
Location: include/linux/dma-direct.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/mapping.c (ffffffff811e89af)
Location: include/linux/dma-direct.h:104
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811eaaee)
Location: include/linux/dma-direct.h:104
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811eda42)
Location: include/linux/dma-direct.h:104
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc8e6)
Location: include/linux/dma-direct.h:104
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194c10)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffff800010196ef8)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffff80001083dc64)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In kernel/dma/direct.c (c03e18c8)
Location: arch/arm/include/asm/dma-direct.h:17
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f4f30)
Location: arch/powerpc/include/asm/dma-direct.h:5
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (c0000000001f7454)
Location: arch/powerpc/include/asm/dma-direct.h:5
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126aa6)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffe00012878e)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
</details>
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b1c4)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/direct.c (ffffffff811277dc)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff81128d54)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81638d90)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a8f4)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/direct.c (ffffffff8111a23c)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff8111b5e4)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b174)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/direct.c (ffffffff811256cc)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff81126a74)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81666ee0)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107d274)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
```
In kernel/dma/direct.c (ffffffff81131d0c)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_resource
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811330b4)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_map
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81681490)
Location: include/linux/dma-direct.h:28
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
</details>
</li>
</ul>

## Differences
