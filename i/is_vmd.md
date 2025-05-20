# Function: <code>is_vmd</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff8178bb37)
Location: arch/x86/include/asm/pci.h:62
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff817aaab3)
Location: arch/x86/include/asm/pci.h:63
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/pci.h:64
Inline: True
```
```
In arch/x86/pci/fixup.c (ffffffff8181f72d)
Location: arch/x86/include/asm/pci.h:64
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff81821f8d)
Location: arch/x86/include/asm/pci.h:64
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In drivers/iommu/intel-iommu.c (ffffffff8166f7d8)
Location: arch/x86/include/asm/pci.h:64
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/fixup.c (ffffffff81869969)
Location: arch/x86/include/asm/pci.h:64
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff8186c248)
Location: arch/x86/include/asm/pci.h:64
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In drivers/iommu/intel-iommu.c (ffffffff8168dd38)
Location: arch/x86/include/asm/pci.h:64
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/fixup.c (ffffffff818899e9)
Location: arch/x86/include/asm/pci.h:64
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff8188c328)
Location: arch/x86/include/asm/pci.h:64
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In drivers/iommu/intel-iommu.c (ffffffff816c669f)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/fixup.c (ffffffff818d427a)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff818d6c7f)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In drivers/iommu/intel-iommu.c (ffffffff816e960f)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/fixup.c (ffffffff819065fa)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff81908fff)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In arch/x86/pci/fixup.c (ffffffff81bb6c6a)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff81bb99c5)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_add_device
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
In arch/x86/pci/fixup.c (ffffffff81bcbcfa)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff81bce2d5)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_add_device
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
In arch/x86/pci/fixup.c (ffffffff81bbf67a)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff81bc1c95)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_add_device
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
In arch/x86/pci/fixup.c (ffffffff81c8f5ea)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff81c922a5)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_add_device
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
In arch/x86/pci/fixup.c (ffffffff81e3e57a)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff81e41925)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_device_add
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
In arch/x86/pci/fixup.c (ffffffff82017d4a)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff8201bfa5)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_device_add
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
In arch/x86/pci/fixup.c (ffffffff8209813a)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff8209c645)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_device_add
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
In arch/x86/pci/fixup.c (ffffffff8216f61a)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff82173e25)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pci_real_dma_dev
  - arch/x86/pci/common.c:pcibios_device_add
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
In drivers/iommu/intel-iommu.c (ffffffff816af0ef)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/fixup.c (ffffffff818a59ba)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff818a83bf)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/pci.h:65
Inline: True
```
```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/include/asm/pci.h:65
Inline: True
```
```
In arch/x86/pci/common.c (0)
Location: arch/x86/include/asm/pci.h:65
Inline: True
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
In drivers/iommu/intel-iommu.c (ffffffff816dd2cf)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/fixup.c (ffffffff818f701a)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff818f9a1f)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In drivers/iommu/intel-iommu.c (ffffffff816f77ca)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In arch/x86/pci/fixup.c (ffffffff8191811a)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:quirk_no_aersid
```
```
In arch/x86/pci/common.c (ffffffff8191ab7d)
Location: arch/x86/include/asm/pci.h:65
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
```
</details>
</li>
</ul>

## Differences
