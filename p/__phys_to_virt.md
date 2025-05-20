# Function: <code>__phys_to_virt</code>

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
In init/initramfs.c (c1503660)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
  - init/initramfs.c:populate_rootfs
```
```
In arch/arm/kernel/setup.c (c15048bc)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/kernel/atags_parse.c (c1505450)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/kernel/atags_parse.c:setup_machine_tags
```
```
In arch/arm/kernel/devtree.c (c1506488)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/kernel/devtree.c:setup_machine_fdt
```
```
In arch/arm/mm/fault.c (c0e9fc64)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_translation_fault
```
```
In arch/arm/mm/init.c (c15076d8)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/mm/init.c:arm_memblock_init
```
```
In arch/arm/mm/dma-mapping.c (c1507cd4)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:dma_contiguous_remap
  - arch/arm/mm/dma-mapping.c:dma_contiguous_remap
  - arch/arm/mm/dma-mapping.c:dma_contiguous_remap
  - arch/arm/mm/dma-mapping.c:dma_contiguous_remap
  - arch/arm/mm/dma-mapping.c:dma_contiguous_remap
```
```
In arch/arm/mm/flush.c (c031edcc)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/mm/flush.c:__flush_anon_page
  - arch/arm/mm/flush.c:flush_icache_alias
```
```
In arch/arm/mm/mmu.c (c1509310)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:adjust_lowmem_bounds
  - arch/arm/mm/mmu.c:arm_pte_alloc
  - arch/arm/mm/mmu.c:pte_offset_late_fixmap
```
```
In arch/arm/mm/dump.c (c0320420)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/mm/dump.c:walk_pmd
```
```
In arch/arm/mm/highmem.c (c0321d5c)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/mm/highmem.c:kmap_atomic_pfn
```
```
In arch/arm/mm/copypage-v6.c (0)
Location: arch/arm/include/asm/memory.h:228
Inline: True
```
```
In arch/arm/mach-hisi/platsmp.c (c032f8fc)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platsmp.c:hip01_boot_secondary
```
```
In arch/arm/mach-hisi/hotplug.c (c032fdf8)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - arch/arm/mach-hisi/hotplug.c:hi3xxx_cpu_die
```
```
In arch/arm/mach-mvebu/pm.c (c033162c)
Location: arch/arm/include/asm/memory.h:228
Inline: True
```
```
In arch/arm/mach-mediatek/platsmp.c (c1510b64)
Location: arch/arm/include/asm/memory.h:228
Inline: True
```
```
In kernel/kexec_core.c (c040f9a8)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_free
```
```
In kernel/iomem.c (c04d8fcc)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - kernel/iomem.c:memremap
```
```
In mm/highmem.c (c0515d58)
Location: arch/arm/include/asm/memory.h:228
Inline: True
```
```
In mm/memory.c (c0518388)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
```
In mm/vmalloc.c (c05282c8)
Location: arch/arm/include/asm/memory.h:228
Inline: True
```
```
In mm/memblock.c (c15325cc)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_internal
  - mm/memblock.c:memblock_double_array
```
```
In mm/memtest.c (c1533e00)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In mm/usercopy.c (c0565244)
Location: arch/arm/include/asm/memory.h:228
Inline: True
```
```
In drivers/pci/rom.c (c088a20c)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - drivers/pci/rom.c:pci_platform_rom
```
```
In drivers/char/mem.c (c09a76c0)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - drivers/char/mem.c:write_mem
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/tpm/eventlog/of.c (c09b8e8c)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/of.c:tpm_read_log_of
```
```
In drivers/iommu/io-pgtable-arm.c (c09bfaa0)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_iova_to_phys
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_unmap
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_free_pgtable
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_map
```
```
In drivers/iommu/omap-iommu.c (c09c2f84)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_iova_to_phys
  - drivers/iommu/omap-iommu.c:_omap_iommu_detach_dev
  - drivers/iommu/omap-iommu.c:iommu_fault_handler
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopgtable_clear_entry
  - drivers/iommu/omap-iommu.c:iopte_alloc
```
```
In drivers/iommu/rockchip-iommu.c (c09c66b4)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_unmap
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_iova_to_phys
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
```
In drivers/iommu/exynos-iommu.c (c09c8ed8)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_iova_to_phys
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_irq
```
```
In drivers/of/fdt.c (c15af028)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen
  - drivers/of/fdt.c:early_init_dt_scan_chosen
```
```
In net/core/xdp.c (c0d202cc)
Location: arch/arm/include/asm/memory.h:228
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In lib/ioremap.c (c0e84324)
Location: arch/arm/include/asm/memory.h:228
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
