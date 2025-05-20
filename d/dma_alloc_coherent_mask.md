# Function: <code>dma_alloc_coherent_mask</code>

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
In arch/x86/kernel/pci-dma.c (ffffffff81034cd0)
Location: arch/x86/include/asm/dma-mapping.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/dma-mapping.h:91
Inline: True
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
In arch/x86/kernel/pci-dma.c (ffffffff81033eb0)
Location: arch/x86/include/asm/dma-mapping.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/dma-mapping.h:88
Inline: True
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
In arch/x86/kernel/pci-dma.c (ffffffff81033ae0)
Location: arch/x86/include/asm/dma-mapping.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/dma-mapping.h:88
Inline: True
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
In arch/x86/kernel/pci-dma.c (ffffffff81031c60)
Location: arch/x86/include/asm/dma-mapping.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/dma-mapping.h:76
Inline: True
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
In arch/x86/kernel/pci-dma.c (ffffffff81033f80)
Location: arch/x86/include/asm/dma-mapping.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff81080361)
Location: arch/x86/include/asm/dma-mapping.h:70
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sev_alloc
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: arch/x86/include/asm/dma-mapping.h:70
Inline: True
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
