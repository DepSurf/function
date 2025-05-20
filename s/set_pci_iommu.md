# Function: <code>set_pci_iommu</code>

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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f76a69)
Location: arch/x86/include/asm/pci_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff81f77191)
Location: arch/x86/include/asm/pci_64.h:13
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9f1cc)
Location: arch/x86/include/asm/pci_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff81f9f8d1)
Location: arch/x86/include/asm/pci_64.h:13
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fda72e)
Location: arch/x86/include/asm/pci_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff81fdae33)
Location: arch/x86/include/asm/pci_64.h:13
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff820bb566)
Location: arch/x86/include/asm/pci_64.h:13
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff820bbcc2)
Location: arch/x86/include/asm/pci_64.h:13
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c1f48)
Location: arch/x86/include/asm/pci_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff826c26a4)
Location: arch/x86/include/asm/pci_64.h:14
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff826ec170)
Location: arch/x86/include/asm/pci_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff826ec8a6)
Location: arch/x86/include/asm/pci_64.h:14
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a2d72)
Location: arch/x86/include/asm/pci_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff828a3497)
Location: arch/x86/include/asm/pci_64.h:14
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bb086)
Location: arch/x86/include/asm/pci_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff828bb7c6)
Location: arch/x86/include/asm/pci_64.h:14
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c1548)
Location: arch/x86/include/asm/pci_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff828c1c84)
Location: arch/x86/include/asm/pci_64.h:14
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828ac51e)
Location: arch/x86/include/asm/pci_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff828acc5a)
Location: arch/x86/include/asm/pci_64.h:14
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a47e5)
Location: arch/x86/include/asm/pci_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff828a4f21)
Location: arch/x86/include/asm/pci_64.h:14
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bf41d)
Location: arch/x86/include/asm/pci_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff828bfb59)
Location: arch/x86/include/asm/pci_64.h:14
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c256a)
Location: arch/x86/include/asm/pci_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In arch/x86/kernel/tce_64.c (ffffffff828c2ca6)
Location: arch/x86/include/asm/pci_64.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/tce_64.c:build_tce_table
```
</details>
</li>
</ul>

## Differences
