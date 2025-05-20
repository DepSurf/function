# Function: <code>pgprot_noncached_wc</code>

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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/pci-common.c (c00000000006d894)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:833
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pci_phys_mem_access_prot
```
```
In arch/powerpc/mm/ioremap.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:833
Inline: True
```
```
In mm/mmap.c (c0000000003cac70)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:833
Inline: True
Inline callers:
  - mm/mmap.c:vm_pgprot_modify
```
```
In drivers/pci/mmap.c (c0000000008745a0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:833
Inline: True
Inline callers:
  - drivers/pci/mmap.c:pci_mmap_resource_range
```
```
In drivers/char/agp/frontend.c (c000000000952bf0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:833
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_mmap
  - drivers/char/agp/frontend.c:agp_mmap
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
