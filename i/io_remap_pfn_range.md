# Function: <code>io_remap_pfn_range</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129e649)
Location: include/linux/mm.h:2802
Inline: True
Inline callers:
  - mm/memory.c:vm_iomap_memory
```
```
In drivers/pci/mmap.c (ffffffff8165cb96)
Location: include/linux/mm.h:2802
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b1d16)
Location: include/linux/mm.h:2802
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault
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
In mm/memory.c (ffffffff812a3ee7)
Location: include/linux/mm.h:2800
Inline: True
Inline callers:
  - mm/memory.c:vm_iomap_memory
```
```
In drivers/pci/mmap.c (ffffffff8163f136)
Location: include/linux/mm.h:2800
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895107)
Location: include/linux/mm.h:2800
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap_fault
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
In mm/memory.c (ffffffff812e5207)
Location: include/linux/mm.h:2858
Inline: True
Inline callers:
  - mm/memory.c:vm_iomap_memory
```
```
In drivers/pci/mmap.c (ffffffff816afe38)
Location: include/linux/mm.h:2858
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81928b67)
Location: include/linux/mm.h:2858
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault
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
In mm/memory.c (ffffffff81346bd0)
Location: include/linux/mm.h:2933
Inline: True
Inline callers:
  - mm/memory.c:vm_iomap_memory
```
```
In drivers/pci/mmap.c (ffffffff817d336a)
Location: include/linux/mm.h:2933
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a7eaef)
Location: include/linux/mm.h:2933
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_mmap_fault
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
In mm/memory.c (ffffffff813befcd)
Location: include/linux/mm.h:3084
Inline: True
Inline callers:
  - mm/memory.c:vm_iomap_memory
```
```
In drivers/pci/mmap.c (ffffffff818f3d0e)
Location: include/linux/mm.h:3084
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
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
In mm/memory.c (ffffffff813f3c40)
Location: include/linux/mm.h:3389
Inline: True
Inline callers:
  - mm/memory.c:vm_iomap_memory
```
```
In drivers/pci/mmap.c (ffffffff81937167)
Location: include/linux/mm.h:3389
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
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
In mm/memory.c (ffffffff8141e8d0)
Location: include/linux/mm.h:3577
Inline: True
Inline callers:
  - mm/memory.c:vm_iomap_memory
```
```
In drivers/pci/mmap.c (ffffffff8197ffc7)
Location: include/linux/mm.h:3577
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
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
