# Function: <code>pci_iommu</code>

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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067b12)
Location: arch/x86/include/asm/pci_64.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
```
```
In arch/x86/kernel/tce_64.c (ffffffff81f770a2)
Location: arch/x86/include/asm/pci_64.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9f112)
Location: arch/x86/include/asm/pci_64.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff81f9f7e4)
Location: arch/x86/include/asm/pci_64.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fda674)
Location: arch/x86/include/asm/pci_64.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff81fdad46)
Location: arch/x86/include/asm/pci_64.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff820bb983)
Location: arch/x86/include/asm/pci_64.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_watchdog
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff820bbbd8)
Location: arch/x86/include/asm/pci_64.h:7
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c2365)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff826c25be)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff826ebc13)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff826ec7ae)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a2815)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff828a339f)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828ba888)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff828bb6c8)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c0d4a)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff828c1b86)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828abd20)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff828acb5c)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a3fe7)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff828a4e23)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bec1f)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff828bfa5b)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c1d6c)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_fixup_tce_spaces
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_page
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
  - arch/x86/kernel/pci-calgary_64.c:calgary_unmap_sg
```
```
In arch/x86/kernel/tce_64.c (ffffffff828c2ba8)
Location: arch/x86/include/asm/pci_64.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
```
</details>
</li>
</ul>

## Differences
