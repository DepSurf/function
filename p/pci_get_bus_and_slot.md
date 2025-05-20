# Function: <code>pci_get_bus_and_slot</code>

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
In drivers/pci/quirks.c (ffffffff814464f6)
Location: include/linux/pci.h:874
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81fa9e96)
Location: include/linux/pci.h:874
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
```
```
In drivers/firmware/edd.c (ffffffff81fb5df0)
Location: include/linux/pci.h:874
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In arch/x86/pci/irq.c (ffffffff81fb9b27)
Location: include/linux/pci.h:874
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In drivers/pci/quirks.c (ffffffff81492676)
Location: include/linux/pci.h:885
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81fd696d)
Location: include/linux/pci.h:885
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
```
```
In drivers/firmware/edd.c (ffffffff81fe3300)
Location: include/linux/pci.h:885
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In arch/x86/pci/irq.c (ffffffff81fe770a)
Location: include/linux/pci.h:885
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In drivers/pci/quirks.c (ffffffff814b3ee6)
Location: include/linux/pci.h:915
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff82012a21)
Location: include/linux/pci.h:915
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/firmware/edd.c (ffffffff820210cf)
Location: include/linux/pci.h:915
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In arch/x86/pci/irq.c (ffffffff82025f45)
Location: include/linux/pci.h:915
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In drivers/pci/quirks.c (ffffffff814be3e6)
Location: include/linux/pci.h:936
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c998b)
Location: include/linux/pci.h:936
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff820f5f92)
Location: include/linux/pci.h:936
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/firmware/edd.c (ffffffff82103c5f)
Location: include/linux/pci.h:936
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff8210949f)
Location: include/linux/pci.h:936
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
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
In drivers/pci/quirks.c (ffffffff814fe776)
Location: include/linux/pci.h:961
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8163033b)
Location: include/linux/pci.h:961
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff826ff6db)
Location: include/linux/pci.h:961
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/firmware/edd.c (ffffffff8270d340)
Location: include/linux/pci.h:961
Inline: True
```
```
In arch/x86/pci/irq.c (ffffffff82712dfd)
Location: include/linux/pci.h:961
Inline: True
Inline callers:
  - arch/x86/pci/irq.c:pcibios_irq_init
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
