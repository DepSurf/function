# Function: <code>cacheid_is</code>

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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/setup.c (c1504318)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/setup.c:setup_processor
```
```
In arch/arm/kernel/fiq.c (c031055c)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
Inline callers:
  - arch/arm/kernel/fiq.c:set_fiq_handler
```
```
In arch/arm/kernel/patch.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In arch/arm/mm/dma-mapping.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In arch/arm/mm/flush.c (c031ed5c)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
Inline callers:
  - arch/arm/mm/flush.c:__flush_anon_page
  - arch/arm/mm/flush.c:__sync_icache_dcache
  - arch/arm/mm/flush.c:copy_to_user_page
  - arch/arm/mm/flush.c:copy_to_user_page
  - arch/arm/mm/flush.c:flush_uprobe_xol_access
  - arch/arm/mm/flush.c:flush_uprobe_xol_access
```
```
In arch/arm/mm/ioremap.c (c031f074)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
Inline callers:
  - arch/arm/mm/ioremap.c:__arm_ioremap_pfn_caller
```
```
In arch/arm/mm/mmap.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In arch/arm/mm/mmu.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In arch/arm/mm/highmem.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In arch/arm/mm/copypage-v6.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In arch/arm/mm/context.c (c032274c)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In kernel/sched/core.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In mm/mmu_context.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In mm/percpu.c (c0506edc)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/highmem.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In mm/vmalloc.c (c052894c)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
Inline callers:
  - mm/vmalloc.c:map_vm_area
  - mm/vmalloc.c:unmap_kernel_range
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:free_unmap_vmap_area
```
```
In fs/exec.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In block/bio.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
```
```
In lib/ioremap.c (c0e8440c)
Location: arch/arm/include/asm/cachetype.h:54
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
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
