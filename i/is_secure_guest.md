# Function: <code>is_secure_guest</code>

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
In arch/powerpc/kernel/sysfs.c (c00000000002985c)
Location: arch/powerpc/include/asm/svm.h:13
Inline: True
Inline callers:
  - arch/powerpc/kernel/sysfs.c:show_svm
```
```
In arch/powerpc/kernel/paca.c (c00000000134bbb0)
Location: arch/powerpc/include/asm/svm.h:13
Inline: True
Inline callers:
  - arch/powerpc/kernel/paca.c:allocate_paca
```
```
In arch/powerpc/kernel/machine_kexec_64.c (c00000000007181c)
Location: arch/powerpc/include/asm/svm.h:13
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec
```
```
In arch/powerpc/platforms/pseries/setup.c (c000000001361f5c)
Location: arch/powerpc/include/asm/svm.h:13
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:__machine_initcall_pseries_alloc_dispatch_log_kmem_cache
```
```
In arch/powerpc/platforms/pseries/smp.c (c000000001363828)
Location: arch/powerpc/include/asm/svm.h:13
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/smp.c:pSeries_smp_probe
```
```
In arch/powerpc/platforms/pseries/svm.c (c000000001364490)
Location: arch/powerpc/include/asm/svm.h:13
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/svm.c:__machine_initcall_pseries_init_svm
```
```
In kernel/dma/direct.c (c0000000001f5414)
Location: arch/powerpc/include/asm/svm.h:13
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/swiotlb.c (c0000000001f6be4)
Location: arch/powerpc/include/asm/svm.h:13
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (c000000000567308)
Location: arch/powerpc/include/asm/svm.h:13
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
```
In drivers/iommu/iommu.c (0)
Location: arch/powerpc/include/asm/svm.h:13
Inline: True
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
