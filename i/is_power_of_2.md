# Function: <code>is_power_of_2</code>

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
In arch/x86/kernel/hw_breakpoint.c (ffffffff81037517)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
```
In kernel/events/core.c (ffffffff8118137a)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmalloc.c (ffffffff811cd29a)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/sparse.c (0)
Location: include/linux/log2.h:52
Inline: True
```
```
In mm/cma.c (0)
Location: include/linux/log2.h:52
Inline: True
```
```
In fs/namespace.c (ffffffff8122f1ee)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff81247419)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/ext4/super.c (ffffffff812b987c)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/ext4/sysfs.c (0)
Location: include/linux/log2.h:52
Inline: True
```
```
In fs/jbd2/revoke.c (ffffffff812ed812)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff812fcfed)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff813a969e)
Location: include/linux/log2.h:52
Inline: True
```
```
In block/blk-settings.c (ffffffff813beb38)
Location: include/linux/log2.h:52
Inline: True
```
```
In lib/hexdump.c (ffffffff81401643)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff81413141)
Location: include/linux/log2.h:52
Inline: True
```
```
In drivers/pci/pci.c (ffffffff814345ae)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/iommu/iova.c (ffffffff8152d0b5)
Location: include/linux/log2.h:52
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152ee25)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
  - drivers/iommu/amd_iommu.c:amd_iommu_unmap
```
```
In drivers/ata/libata-core.c (ffffffff815cd62d)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/bitmap.c (ffffffff8169c587)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
```
In drivers/mmc/core/core.c (ffffffff816c0c7f)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In drivers/clk/clk-divider.c (ffffffff816e8ef0)
Location: include/linux/log2.h:52
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff81712f51)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff81036737)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
```
In kernel/events/core.c (ffffffff8119315b)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmalloc.c (ffffffff811eb708)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/sparse.c (0)
Location: include/linux/log2.h:52
Inline: True
```
```
In mm/cma.c (ffffffff81fb8c24)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff81257989)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff8126fcd9)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/ext4/super.c (ffffffff812eb835)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff813138bd)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff8131b162)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff81330cb8)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff813e7662)
Location: include/linux/log2.h:52
Inline: True
```
```
In block/blk-settings.c (ffffffff81402a08)
Location: include/linux/log2.h:52
Inline: True
```
```
In lib/hexdump.c (ffffffff81449033)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff8145ae41)
Location: include/linux/log2.h:52
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8147ffd2)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/iommu/iova.c (ffffffff81580ba5)
Location: include/linux/log2.h:52
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81582a65)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_unmap_page
  - drivers/iommu/amd_iommu.c:iommu_unmap_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/regmap/regmap.c (ffffffff815b8da9)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/bus.c (ffffffff815ed39c)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815f8b8b)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/ata/libata-core.c (ffffffff81625f54)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/bitmap.c (ffffffff817002d6)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
```
In drivers/mmc/core/core.c (ffffffff81723aaf)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In drivers/clk/clk-divider.c (ffffffff8174d3d5)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In net/core/sysctl_net_core.c (ffffffff8177abc1)
Location: include/linux/log2.h:52
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff81036457)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107e6bd)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/events/core.c (ffffffff811a293b)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff811da2e9)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/vmalloc.c (ffffffff811fc975)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/sparse.c (0)
Location: include/linux/log2.h:46
Inline: True
```
```
In mm/cma.c (ffffffff81ff5595)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff8126ae19)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff81282ed9)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/ext4/super.c (ffffffff813017fd)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff8132985d)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff81331142)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff81346a08)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff814000fb)
Location: include/linux/log2.h:46
Inline: True
```
```
In block/blk-settings.c (ffffffff8141c758)
Location: include/linux/log2.h:46
Inline: True
```
```
In block/partition-generic.c (ffffffff8142d194)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/hexdump.c (ffffffff81467a23)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff81479931)
Location: include/linux/log2.h:46
Inline: True
```
```
In drivers/pci/pci.c (ffffffff814a1622)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffff81535c45)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff815ad555)
Location: include/linux/log2.h:46
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815aed45)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_unmap_page
  - drivers/iommu/amd_iommu.c:iommu_unmap_page
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/regmap/regmap.c (ffffffff815e80d9)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/bus.c (ffffffff8161a196)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81626e0b)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81648be9)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/ata/libata-core.c (ffffffff81656b02)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/bitmap.c (ffffffff81732002)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
```
In drivers/mmc/core/core.c (ffffffff8175539e)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff817a81c1)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff81034467)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107ccc9)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/bpf/arraymap.c (ffffffff8119ca89)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/events/core.c (ffffffff811a9fae)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff811e398a)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/vmalloc.c (ffffffff81207655)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/sparse.c (0)
Location: include/linux/log2.h:46
Inline: True
```
```
In mm/cma.c (ffffffff820d7d90)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff812785a5)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff81291be5)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/ext4/super.c (ffffffff81336509)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff81339451)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff813460a2)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff8135b425)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff8140d427)
Location: include/linux/log2.h:46
Inline: True
```
```
In block/blk-settings.c (ffffffff8142a6b8)
Location: include/linux/log2.h:46
Inline: True
```
```
In block/partition-generic.c (ffffffff8143a509)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/hexdump.c (ffffffff8146d123)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff81482c91)
Location: include/linux/log2.h:46
Inline: True
```
```
In drivers/pci/pci.c (ffffffff814ab1a2)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffff81548f9e)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff815c3165)
Location: include/linux/log2.h:46
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c6850)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/regmap/regmap.c (ffffffff815fcaab)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/nvdimm/bus.c (ffffffff8162e289)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8163baab)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff8165d518)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/ata/libata-core.c (ffffffff8166af92)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/bitmap.c (ffffffff81747bd7)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/md/bitmap.c:chunksize_store
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
```
In drivers/md/dm-table.c (ffffffff817522fc)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff81772f19)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff817c67cf)
Location: include/linux/log2.h:46
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff810367c7)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81083bc6)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/bpf/arraymap.c (ffffffff811ac4f7)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/events/core.c (ffffffff811bd8a1)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff811fa46f)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/vmalloc.c (ffffffff81220745)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/sparse.c (0)
Location: include/linux/log2.h:49
Inline: True
```
```
In mm/cma.c (ffffffff826e0a24)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff8129aed8)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff812b4965)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/ext4/super.c (ffffffff8135abdf)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff8135d7c1)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff8136a739)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff81380128)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff81435e97)
Location: include/linux/log2.h:49
Inline: True
```
```
In block/blk-settings.c (ffffffff81455867)
Location: include/linux/log2.h:49
Inline: True
```
```
In block/partition-generic.c (ffffffff8146652c)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/hexdump.c (ffffffff81499453)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff814becd0)
Location: include/linux/log2.h:49
Inline: True
```
```
In drivers/pci/pci.c (ffffffff814ea3c2)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffff815ac51a)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff81629aa6)
Location: include/linux/log2.h:49
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162d5f0)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/regmap/regmap.c (ffffffff81664c4b)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff81670937)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (ffffffff81696a4e)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff816c6b6f)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/ata/libata-core.c (ffffffff816d45e5)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff817b9e67)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In drivers/md/dm-table.c (ffffffff817c44eb)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff817e8bb9)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff818403cf)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff81037813)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81086806)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/dma/swiotlb.c (ffffffff8110dc20)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/arraymap.c (ffffffff811c3b37)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/events/core.c (ffffffff811ddaef)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff8121b076)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/vmalloc.c (ffffffff81242535)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/sparse.c (0)
Location: include/linux/log2.h:49
Inline: True
```
```
In mm/cma.c (ffffffff8270af41)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff812c110b)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff812db209)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/ext4/super.c (ffffffff81389125)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff8138c006)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff81398eb9)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff813ae89c)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff81468a22)
Location: include/linux/log2.h:49
Inline: True
```
```
In block/blk-settings.c (ffffffff81488c97)
Location: include/linux/log2.h:49
Inline: True
```
```
In block/partition-generic.c (ffffffff81499e2b)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/hexdump.c (ffffffff814ce658)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff814eff41)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pci/pci.c (ffffffff81519c52)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffff815e4697)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff816647b5)
Location: include/linux/log2.h:49
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816680e3)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/regmap/regmap.c (ffffffff816a0581)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff816ac005)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (ffffffff816d2bb5)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81702fcc)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/ata/libata-core.c (ffffffff8171094c)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff81801f17)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In drivers/md/dm-table.c (ffffffff8180ceff)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff81831db4)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff8188a8cf)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (ffffffff819cb8c1)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (ffffffff819cd009)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff81038a2b)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108d94a)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/dma/swiotlb.c (ffffffff81119770)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/verifier.c (ffffffff811cc443)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
```
In kernel/bpf/arraymap.c (ffffffff811d56d7)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/events/core.c (ffffffff811edeef)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff8122e047)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/vmalloc.c (ffffffff81256c68)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/cma.c (ffffffff828c2125)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff812d63d4)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff812f0759)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/ext4/super.c (ffffffff813a19d8)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff813a4b96)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff813b1c29)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff813c7a96)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff81486698)
Location: include/linux/log2.h:49
Inline: True
```
```
In block/blk-settings.c (ffffffff814a2b97)
Location: include/linux/log2.h:49
Inline: True
```
```
In block/partition-generic.c (ffffffff814b413b)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/hexdump.c (ffffffff814e2f48)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff81503e61)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pci/pci.c (ffffffff8152f712)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: include/linux/log2.h:49
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff815fea87)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff81682db5)
Location: include/linux/log2.h:49
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff81686424)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/regmap/regmap.c (ffffffff816c0d2e)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff816ce03f)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (ffffffff816f4305)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81725a0c)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/ata/libata-core.c (ffffffff81732dff)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff8182e127)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/md/dm-table.c (ffffffff81838e2f)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff8185dd94)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff818ab8af)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (ffffffff81a04b11)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (ffffffff81a06259)
Location: include/linux/log2.h:49
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103afcf)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810917e9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
```
```
In kernel/dma/swiotlb.c (ffffffff811241fd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/verifier.c (ffffffff811d6e76)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
```
```
In kernel/bpf/arraymap.c (ffffffff811e9ef7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/events/core.c (ffffffff8120595c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff8123e8a3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/vmalloc.c (ffffffff8126aeb5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/cma.c (ffffffff828db4f4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff812f4b2b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff813120da)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff813cc4cf)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff813cecc2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff813dc27b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff813f2663)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff814b455e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-settings.c (ffffffff814d0c48)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/partition-generic.c (ffffffff814e2613)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/kfifo.c (ffffffff8150b3bd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff8150f2d4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff81531fd3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pci/pci.c (ffffffff8155ee72)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff81631166)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff816ba9f5)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bdcf8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/regmap/regmap.c (ffffffff816fbb2e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff81708e57)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (ffffffff8172d8ee)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff8176100c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/ata/libata-core.c (ffffffff8176eaac)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff818707a0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (ffffffff8187b9d5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff818a1a0a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff818f7160)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (ffffffff81a73fb9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (ffffffff81a75b80)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b79f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
```
In kernel/dma/swiotlb.c (ffffffff81130197)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/verifier.c (ffffffff811e34d6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
```
```
In kernel/bpf/arraymap.c (ffffffff811f6657)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/btf.c (ffffffff811fc836)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff81212cec)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff8124cd03)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff828dc97e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff81279de5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/cma.c (ffffffff828e392a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff813066d9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff8132503a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (ffffffff828e66fd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff81350a36)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff813e5857)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff813e8392)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff813f62cb)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff8140c566)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff814cd2ce)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-settings.c (ffffffff814ea008)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/partition-generic.c (ffffffff814fb9d3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/kfifo.c (ffffffff815291dd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff8152d2b4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff81552e13)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pci/pci.c (ffffffff8157ffb2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffff81652e96)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff816dd845)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e0eec)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/memory.c (ffffffff82908f80)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff8171fede)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff8172d137)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (ffffffff81751b8e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81784fcc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/ata/libata-core.c (ffffffff81792b1c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff818a2590)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (ffffffff818ad7b5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff818d3d0a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff81928ee0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (ffffffff81aaab99)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (ffffffff81aacb6a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103e0d3)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8113ef61)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/core.c (ffffffff811fa535)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff81204406)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
```
```
In kernel/bpf/arraymap.c (ffffffff81219c47)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/ringbuf.c (ffffffff8121e44d)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff812216ab)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff8123ed6d)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff8127afdf)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff82cfa4a9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff812aa5d3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In fs/namespace.c (ffffffff81340086)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff8136029a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (ffffffff82d01596)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff8139743c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff814329c0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff814353e5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff8144380b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff8145948a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/cbc.c (ffffffff8152c72a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-settings.c (ffffffff81548f08)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/blk-zoned.c (ffffffff81578b60)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
```
```
In block/blk-crypto.c (ffffffff81581cd4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/kfifo.c (ffffffff8158c9b0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff81590f05)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff815dc1f6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pci/pci.c (ffffffff81625472)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffff81702ad8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff81793e45)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/iommu/amd/iommu.c (ffffffff81795f25)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_unmap_page
  - drivers/iommu/amd/iommu.c:iommu_unmap_page
```
```
In drivers/base/swnode.c (ffffffff817c32af)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_read_int_array
```
```
In drivers/base/memory.c (ffffffff82d1f4fa)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff817dbfee)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff817e9f67)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
```
```
In drivers/nvdimm/bus.c (ffffffff818103ea)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/nvdimm/region_devs.c (ffffffff81815120)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/ata/libata-core.c (ffffffff818577d6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff81971fd0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
```
```
In drivers/md/dm-table.c (ffffffff8197da85)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff819a63b2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff819fce60)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (ffffffff81ba7ea5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ba84fa)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103e199)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8113a60f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/trace/ftrace.c (ffffffff811ab029)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_allocate_pages
```
```
In kernel/bpf/core.c (ffffffff811f9655)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff81204396)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
```
```
In kernel/bpf/arraymap.c (ffffffff8121c467)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/ringbuf.c (ffffffff812211d1)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff812248b1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff8124915d)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff812859f1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff82fe71e1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff812b5ca3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In fs/namespace.c (ffffffff8134bf6a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
```
```
In fs/block_dev.c (ffffffff8136d815)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (ffffffff82fee885)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff813a8eac)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/binfmt_elf.c (ffffffff813b268f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813b5489)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff8144b7c8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff8144de15)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff8145f8eb)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff814757da)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/cbc.c (ffffffff815496fa)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-merge.c (ffffffff8156779f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/blk-zoned.c (ffffffff81595489)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
```
```
In block/blk-crypto.c (ffffffff8159ecc4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/kfifo.c (ffffffff815a9400)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff815adaa5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff815f9e96)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pci/pci.c (ffffffff8164b5a2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffff8171fbbd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a4645)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_unmap_page
  - drivers/iommu/amd/iommu.c:iommu_unmap_page
```
```
In drivers/iommu/iova.c (ffffffff817c0b95)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/swnode.c (ffffffff817d81cf)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_read_int_array
```
```
In drivers/base/memory.c (ffffffff8300d2b2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff817f10c5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff817fe9d7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
```
```
In drivers/nvdimm/bus.c (ffffffff8181f32a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/nvdimm/region_devs.c (ffffffff81824310)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/ata/libata-core.c (ffffffff81867a56)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff81976ee0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
```
```
In drivers/md/dm.c (ffffffff8197c397)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm.c:max_io_len
```
```
In drivers/md/dm-table.c (ffffffff819820cf)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff819a9162)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff819fcaa0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/core/devlink.c (ffffffff81a59c90)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
```
```
In net/xdp/xsk.c (ffffffff81bb7aec)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8264)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103fae1)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8113b362)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811fa4f5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff8120535c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
```
```
In kernel/bpf/arraymap.c (ffffffff8121fe7a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/ringbuf.c (ffffffff81224cd3)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff812293f1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff8124d32d)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff8128a5c6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff831f191a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff812bb393)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In fs/namespace.c (ffffffff81352997)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
```
```
In fs/block_dev.c (ffffffff81374205)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (ffffffff831f9144)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff813aff1c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/binfmt_elf.c (ffffffff813b978a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813bc49c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff8145121a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff814538d5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff81464fdb)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff8147b24a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/cbc.c (ffffffff81551dea)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-merge.c (ffffffff8156fe2f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/blk-zoned.c (ffffffff8159c359)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
```
```
In block/blk-crypto.c (ffffffff815a5b29)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/kfifo.c (ffffffff815b4000)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff815b8747)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff815dca76)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pci/pci.c (ffffffff8162e182)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffff81700e0c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178c285)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
```
```
In drivers/iommu/iova.c (ffffffff817a3ab5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/swnode.c (ffffffff817bbb7c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_read_int_array
```
```
In drivers/base/memory.c (ffffffff8321810d)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff817d5962)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff817e36fc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
```
```
In drivers/nvdimm/bus.c (ffffffff8180264a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/nvdimm/region_devs.c (ffffffff81807540)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/ata/libata-core.c (ffffffff8184a29e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff8195b140)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
```
```
In drivers/md/dm.c (ffffffff81960027)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm.c:max_io_len
```
```
In drivers/md/dm-table.c (ffffffff8196648f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff8198de2a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff819e3310)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/core/devlink.c (ffffffff81a3ce75)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
```
```
In net/ethtool/linkmodes.c (ffffffff81a7c2e6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/xdp/xsk.c (ffffffff81ba6c6c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ba7426)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff81045916)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8115e473)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_find_slots
```
```
In kernel/bpf/core.c (ffffffff8122bc05)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff81237e8c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
```
```
In kernel/bpf/arraymap.c (ffffffff81258209)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/ringbuf.c (ffffffff8125cc13)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff812617f1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff81286f3d)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff812ca9e4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff832d728b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff812fd9c3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/namespace.c (ffffffff813a0da8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
```
```
In fs/verity/hash_algs.c (ffffffff832e0045)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff813ffb0c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/binfmt_elf.c (ffffffff8140949a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8140c19c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff814a4823)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff814a7945)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff814ba95b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff814d286a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/cbc.c (ffffffff815b2dea)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/bdev.c (ffffffff815c3f95)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/bdev.c:set_blocksize
```
```
In block/blk-merge.c (ffffffff815d44cf)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/blk-zoned.c (ffffffff8160495f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
```
```
In block/blk-crypto.c (ffffffff8160e617)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In lib/kfifo.c (ffffffff8161a1ec)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff8161ef97)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff816483d6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pci/pci.c (ffffffff8169cce2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffff8177b63f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81813585)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
```
```
In drivers/iommu/iova.c (ffffffff8182cd05)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/swnode.c (ffffffff81845e4c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_read_int_array
```
```
In drivers/base/memory.c (ffffffff8185cf00)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff81860ed3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff8186ef9f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
```
```
In drivers/nvdimm/bus.c (ffffffff8188cb2a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/nvdimm/region_devs.c (ffffffff81890600)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/ata/libata-core.c (ffffffff818d7388)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff81a00930)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
```
```
In drivers/md/dm.c (ffffffff81a07ff7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm.c:max_io_len
```
```
In drivers/md/dm-table.c (ffffffff81a0e69f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff81a394ba)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff81a93b10)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/core/devlink.c (ffffffff81af3d75)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
```
```
In net/ethtool/linkmodes.c (ffffffff81b36626)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/xdp/xsk.c (ffffffff81c747dc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81c75040)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8104e479)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811885a7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_find_slots
```
```
In kernel/bpf/core.c (ffffffff8126eae8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff8127c1c6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
```
```
In kernel/bpf/arraymap.c (ffffffff812a0ea1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/ringbuf.c (ffffffff812a6a85)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff812ad112)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff812db6c2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff813282c6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff8348be9b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff81364950)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/namespace.c (ffffffff81424775)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
```
```
In fs/verity/hash_algs.c (ffffffff83495e36)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff814738c6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/binfmt_elf.c (ffffffff8147e0f3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81480f87)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff8152c53e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/ext4/sysfs.c (ffffffff8152f220)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff815447fb)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff8155f898)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/cbc.c (ffffffff8165b979)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/bdev.c (ffffffff8166efe9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/bdev.c:set_blocksize
```
```
In block/blk-merge.c (ffffffff8168030f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/blk-zoned.c (ffffffff816b8107)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
```
```
In block/blk-crypto.c (ffffffff816c1cd1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In io_uring/io_uring.c (ffffffff816ce1a2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_register_pbuf_ring
```
```
In lib/kfifo.c (ffffffff816e77dc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff816ed1e0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff8175e7b4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b1bd5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_init
```
```
In drivers/pci/pci.c (ffffffff817bec46)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffff818b1f08)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81954595)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_page
```
```
In drivers/iommu/iova.c (ffffffff8196d645)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/swnode.c (ffffffff8198a1fc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_read_int_array
```
```
In drivers/base/memory.c (ffffffff819a41be)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff819a8b40)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff819b7fbc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
```
```
In drivers/nvdimm/bus.c (ffffffff819d6044)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/nvdimm/region_devs.c (ffffffff819da535)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a154e2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
```
```
In drivers/ata/libata-core.c (ffffffff81a282d8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff81b68239)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
```
```
In drivers/md/dm.c (ffffffff81b6fc00)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm.c:max_io_len
```
```
In drivers/md/dm-table.c (ffffffff81b76e0f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff81ba6585)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In drivers/mailbox/pcc.c (ffffffff81bca911)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
```
In net/core/sysctl_net_core.c (ffffffff81c09d81)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/core/devlink.c (ffffffff81c7305e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
```
```
In net/ethtool/linkmodes.c (ffffffff81cc1f74)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/xdp/xsk.c (ffffffff81e1896f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81e191cc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105b9b1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/x86/kernel/module.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811c462c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
  - kernel/dma/swiotlb.c:swiotlb_adjust_nareas
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812c42c8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff812d27e6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
```
```
In kernel/bpf/arraymap.c (ffffffff812fdc66)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/ringbuf.c (ffffffff81304f65)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8130c8b7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff8134398c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff8139d536)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff83ebcf02)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff813e04b0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/page_alloc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/namespace.c (ffffffff814b0ec7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
```
```
In fs/verity/hash_algs.c (ffffffff83ecab01)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff81505808)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/binfmt_elf.c (ffffffff81510e7a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81513f03)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff815cb3c1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/ext4/sysfs.c (ffffffff815ccf30)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff815e388b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff81601ba8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In crypto/cbc.c (ffffffff81715189)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/bdev.c (ffffffff8172a2e9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/bdev.c:set_blocksize
```
```
In block/blk-merge.c (ffffffff8173d6eb)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-zoned.c (ffffffff81777ddf)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_zone_cb
```
```
In block/blk-crypto.c (ffffffff81782ee1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In io_uring/kbuf.c (ffffffff8179fc32)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
```
```
In lib/kfifo.c (ffffffff817d761c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff817ddb80)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff8188bfd4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In lib/sbitmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cbb05)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_init
```
```
In drivers/pci/pci.c (ffffffff818dcbb6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff819fe548)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a0d939)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81a12b0b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81aba3d0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
```
```
In drivers/iommu/iova.c (ffffffff81ad7ee5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/swnode.c (ffffffff81af95cc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_read_int_array
```
```
In drivers/base/memory.c (ffffffff81b161ce)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1bc0e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff81b2d30c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
```
```
In drivers/nvdimm/bus.c (ffffffff81b50c44)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b558a7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b96412)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
```
```
In drivers/ata/libata-core.c (ffffffff81baaa3e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff81d03ca9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
```
```
In drivers/md/dm.c (ffffffff81d0c27a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm.c:max_io_len
```
```
In drivers/md/dm-table.c (ffffffff81d14204)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff81d48ac3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In drivers/mailbox/pcc.c (ffffffff81d73fdd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
```
In net/core/stream.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff81db9b31)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/core/neighbour.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/core/devlink.c (ffffffff81e2bb9e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_port_split_doit
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ethtool/linkmodes.c (ffffffff81e80d64)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
```
```
In net/ipv4/route.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_plb.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/xdp/xsk.c (ffffffff81fefbcf)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0422)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105cee6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/x86/kernel/module.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/workqueue.c (ffffffff8111e2e0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/sched/fair.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811d7058)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
  - kernel/dma/swiotlb.c:swiotlb_adjust_nareas
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/core.c (ffffffff812eb278)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff81307edc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
```
```
In kernel/bpf/arraymap.c (ffffffff8132c876)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/ringbuf.c (ffffffff813338f5)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8133bf80)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff813749ee)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmscan.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/percpu.c (ffffffff813d0666)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff836e5582)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff81415270)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/swapfile.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8149c9ba)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
```
In fs/namespace.c (ffffffff814e5f07)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
```
```
In fs/verity/enable.c (ffffffff8153bf70)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/verity/hash_algs.c (ffffffff836efb64)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff8153ca3f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/binfmt_elf.c (ffffffff815487be)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8154b974)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff816039a6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_block_group_meta_init
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/ext4/sysfs.c (ffffffff81604e73)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff8161b04b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff81639a9e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In crypto/cbc.c (ffffffff81750a39)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/bdev.c (ffffffff81766639)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/bdev.c:set_blocksize
```
```
In block/blk-merge.c (ffffffff81779c6b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-zoned.c (ffffffff817b7f51)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In block/blk-crypto.c (ffffffff817c3151)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In io_uring/kbuf.c (ffffffff817e0d2c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
```
```
In lib/kfifo.c (ffffffff8181682c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff8181d38e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff818ce444)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In lib/sbitmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190eb75)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_init
```
```
In drivers/pci/pci.c (ffffffff8191fe96)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff81a47208)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a56896)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06990)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
```
```
In drivers/iommu/iova.c (ffffffff81b25e25)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/swnode.c (ffffffff81b47b7c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_read_int_array
```
```
In drivers/base/memory.c (ffffffff81b64f3e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff81b6aca4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff81b7d63d)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
```
```
In drivers/block/virtio_blk.c (ffffffff81b8101c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
```
```
In drivers/nvdimm/bus.c (ffffffff81ba40e4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/nvdimm/region_devs.c (ffffffff81ba8df7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bec6ff)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
```
```
In drivers/ata/libata-core.c (ffffffff81c01b9c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff81d6cb59)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
```
```
In drivers/md/dm.c (ffffffff81d7549b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm.c:__max_io_len
```
```
In drivers/md/dm-table.c (ffffffff81d7d356)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff81db33c3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In drivers/mailbox/pcc.c (ffffffff81de1ffd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
```
In net/core/skbuff.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff81e2a1e1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/core/neighbour.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ethtool/linkmodes.c (ffffffff81edccec)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes_validate
```
```
In net/ipv4/route.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_plb.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/devlink/leftover.c (ffffffff8202fa9a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_port_split_doit
```
```
In net/xdp/xsk.c (ffffffff8206bd6f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff8206c5d0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/entry/vdso/vma.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81063fa6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
```
In arch/x86/kernel/process.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/x86/kernel/module.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/x86/mm/cpu_entry_area.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/workqueue.c (ffffffff81128010)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/sched/fair.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff811ec054)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
  - kernel/dma/swiotlb.c:swiotlb_adjust_nareas
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/core.c (ffffffff81309775)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
```
In kernel/bpf/verifier.c (ffffffff8132fb09)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:regs_refine_cond_op
```
```
In kernel/bpf/arraymap.c (ffffffff81350db6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/ringbuf.c (ffffffff81357fe5)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff81362140)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff8139dd1e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/vmscan.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/percpu.c (ffffffff813fb026)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff83917d72)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff81441d40)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/slub.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/zsmalloc.c (ffffffff814cc139)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
```
```
In fs/namespace.c (ffffffff81519d37)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
```
```
In fs/verity/enable.c (ffffffff81571250)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/verity/hash_algs.c (ffffffff83922bfe)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff81571e9f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/binfmt_elf.c (ffffffff8157dc47)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81580e48)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8160292e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/mmp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff8163be07)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_block_group_meta_init
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/ext4/sysfs.c (ffffffff8163db33)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff81653f6b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff81672f8e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_read_bpb
  - fs/fat/inode.c:fat_read_bpb
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In crypto/cbc.c (ffffffff817929ba)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/bdev.c (ffffffff817a8169)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/bdev.c:set_blocksize
```
```
In block/blk-merge.c (ffffffff817bc03b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-zoned.c (ffffffff817fc5f2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In block/blk-crypto.c (ffffffff81807de1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-crypto.c:blk_crypto_init_key
```
```
In io_uring/kbuf.c (ffffffff81825310)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
```
```
In lib/kfifo.c (ffffffff8185bb0c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff818631fe)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff819201f4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In lib/sbitmap.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (ffffffff819568e5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_init
```
```
In drivers/pci/pci.c (ffffffff81968076)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff81a92ca8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/virtio/virtio_ring.c (ffffffff81aa79b6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5a7b0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_unmap_pages
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79e13)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
```
In drivers/iommu/iova.c (ffffffff81b7cc55)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/iova.c:init_iova_domain
```
```
In drivers/base/swnode.c (ffffffff81b9ff0c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/swnode.c:property_entry_read_int_array
```
```
In drivers/base/memory.c (ffffffff81bb8c9e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register_dynamic
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbe993)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff81bd15bd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_configure
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4fb5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
```
```
In drivers/nvdimm/bus.c (ffffffff81bf82d4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bfd137)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:align_store
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c41dbf)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
```
```
In drivers/ata/libata-core.c (ffffffff81c57bdb)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7c9f3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:drm_atomic_plane_set_property
```
```
In drivers/gpu/drm/drm_blend.c (ffffffff81c7f24c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_blend.c:drm_plane_create_rotation_property
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca0b52)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:drm_mm_scan_init_with_range
  - drivers/gpu/drm/drm_mm.c:drm_mm_insert_node_in_range
```
```
In drivers/gpu/drm/drm_modes.c (ffffffff81ca7c77)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/gpu/drm/drm_property.c (ffffffff81cae0e6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_property_create
```
```
In drivers/md/md-bitmap.c (ffffffff81e23d89)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/md-bitmap.c:md_bitmap_new_disk_sb
```
```
In drivers/md/dm.c (ffffffff81e2c5ab)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm.c:__max_io_len
```
```
In drivers/md/dm-table.c (ffffffff81e332ee)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:validate_hardware_zoned
```
```
In drivers/mmc/core/core.c (ffffffff81e6b793)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In drivers/mailbox/pcc.c (ffffffff81e97fcd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_chan_reg_init
```
```
In net/core/skbuff.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/core/stream.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/core/sysctl_net_core.c (ffffffff81ee8261)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/core/neighbour.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ethtool/linkmodes.c (ffffffff81fa0abc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes_validate
```
```
In net/ipv4/route.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_plb.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/xfrm/xfrm_state.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/devlink/port.c (ffffffff82107e1a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_nl_port_split_doit
```
```
In net/xdp/xsk.c (ffffffff8213f93f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff821403ce)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffff800010196964)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/verifier.c (ffff80001026e8a0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
```
```
In kernel/bpf/arraymap.c (ffff80001027ada8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/btf.c (ffff800010283054)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffff80001029d1bc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffff8000102e32c8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffff800011455494)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffff8000103110dc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/cma.c (ffff80001145cec8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffff8000103b9cec)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffff8000103df614)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (ffff80001145ff8c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffff8000104129bc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffff8000104becf4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffff8000104c10a0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffff8000104d22f8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffff8000104ed3b8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffff8000105c9174)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-settings.c (ffff8000105e8390)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/partition-generic.c (ffff8000105fd99c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/kfifo.c (ffff800010633b90)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffff800010639380)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff8000106745bc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cca08)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_init
```
```
In drivers/pci/pci.c (ffff8000106e343c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffff8000107c3894)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/soc/fsl/qbman/bman_ccsr.c (ffff80001080f89c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
```
```
In drivers/soc/fsl/qbman/qman_ccsr.c (ffff80001081018c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_ccsr.c:qm_set_memory
```
```
In drivers/iommu/iova.c (ffff8000108ccf7c)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/base/memory.c (ffff800011497a10)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffff800010914678)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffff800010924a98)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (ffff8000109522b4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffff80001098b3a0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/ata/libata-core.c (ffff80001099cb0c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffff800010af6564)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (ffff800010b04374)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffff800010b2d33c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In drivers/mmc/host/mmci.c (ffff800010b44bf8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_validate_data
```
```
In net/core/sysctl_net_core.c (ffff800010bc52c0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (ffff800010d7e454)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (ffff800010d813e4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/vfp/vfpsingle.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/arm/vfp/vfpdouble.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/arm/kernel/smp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/arm/mm/cache-uniphier.c (c150b5fc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_init
  - arch/arm/mm/cache-uniphier.c:__uniphier_cache_init
```
```
In arch/arm/mach-omap2/timer.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/arm/mach-omap2/vc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/sched/pelt.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/power/main.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/power/hibernate.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/time/timer.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/time/hrtimer.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/time/timekeeping.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/time/ntp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/time/jiffies.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/time/alarmtimer.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/acct.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/cgroup/rstat.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/trace/trace_output.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/trace/trace_hwlat.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In kernel/bpf/verifier.c (c0498e14)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
```
```
In kernel/bpf/arraymap.c (c04acde8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/btf.c (c04b3ac8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (c04cc7d8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/page-writeback.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/percpu.c (c0507460)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (c1530468)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (c052a9e0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/page_alloc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In mm/cma.c (c15351b8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (c05977a8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/fs-writeback.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/block_dev.c (c05b7914)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (c153803c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (c05ded10)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/proc/uptime.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (c0682770)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (c0684dac)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (c0694a30)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/jbd2/journal.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/fat/inode.c (c06aaf84)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/pstore/ram.c (c06d6b68)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
```
```
In security/keys/proc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In crypto/cbc.c (c0776db4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-sysfs.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/blk-settings.c (c0794848)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/blk-lib.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/partition-generic.c (c07a8878)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In block/partitions/efi.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In lib/kfifo.c (c07d9efc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/string_helpers.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In lib/hexdump.c (c07decf8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/kstrtox.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In lib/math/div64.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In lib/math/reciprocal_div.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In lib/dim/dim.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081c150)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
```
```
In drivers/bus/mvebu-mbus.c (c0825728)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/bus/mvebu-mbus.c:mvebu_devs_debug_show
```
```
In drivers/phy/phy-core-mipi-dphy.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (c0867b50)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_init
```
```
In drivers/gpio/gpio-mvebu.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/pci/pci.c (c087f2a0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-divider.c (c08ef89c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-fractional-divider.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-hsdk-pll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-npcm7xx.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-qoriq.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/actions/owl-factor.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/berlin/berlin2-avpll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/berlin/berlin2-pll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/imx/clk-frac-pll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/imx/clk-pfd.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/imx/clk-pfdv2.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/imx/clk-pllv1.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/imx/clk-pllv2.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/imx/clk-pllv3.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/imx/clk-pllv4.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/imx/clk-sccg-pll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/imx/clk-pll14xx.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/mediatek/clk-pll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/meson/clk-mpll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/meson/clk-pll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/mvebu/common.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/renesas/clk-rcar-gen2.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/renesas/rcar-gen2-cpg.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/rockchip/clk-pll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/rockchip/clk-half-divider.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/samsung/clk-pll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/tegra/clk-divider.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/tegra/clk-periph-fixed.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/tegra/clk-pll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/tegra/clk-sdmmc-mux.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/tegra/clk-utils.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/ti/divider.c (c0916be0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/ti/divider.c:ti_clk_divider_round_rate
```
```
In drivers/clk/ti/clkt_dpll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/ti/clkctrl.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/ti/dpll3xxx.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/ti/fapll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/ti/adpll.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/versatile/icst.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/soc/amlogic/meson-clk-measure.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/soc/tegra/pmc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/tty/serial/imx.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/base/dd.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/base/power/main.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/base/regmap/regmap.c (c09fa5bc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (c0a08240)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/scsi/sd_zbc.c (c0a5d6dc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/ata/libata-core.c (c0a6cdf8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/ata/libata-transport.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/mtd/mtdcore.c (c0a908fc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/mtd/mtdcore.c:add_mtd_device
```
```
In drivers/mtd/mtdconcat.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/mtd/mtdpart.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/mtd/nand/core.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/mtd/nand/raw/nand_base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/net/ethernet/ti/cpts.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/usb/dwc2/core.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/rtc/rtc-s3c.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/i2c/busses/i2c-s3c2410.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/thermal/cpu_cooling.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/md/md-bitmap.c (c0bd8018)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/md/dm-table.c (c0be3464)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/cpuidle/governors/menu.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/cpuidle/governors/teo.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/mmc/core/core.c (c0c08680)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In drivers/mmc/host/mmci.c (c0c1e7c4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_validate_data
```
```
In drivers/mmc/host/sdhci.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/mmc/host/omap_hsmmc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/firmware/tegra/bpmp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clocksource/sh_cmt.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/devfreq/governor_simpleondemand.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/memory/tegra/mc.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In sound/core/pcm_lib.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In sound/soc/codecs/sgtl5000.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In sound/soc/fsl/fsl_ssi.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/core/sysctl_net_core.c (c0ce08cc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/bpf/test_run.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_rate.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/ipv6/syncookies.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In net/xdp/xsk.c (c0e78c9c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (c0e7b990)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/vsprintf.c (0)
Location: include/linux/log2.h:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/init-common.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In arch/powerpc/mm/hugetlbpage.c (c000000001357cb8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:add_huge_page_size
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d2708)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_get_table_size
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000db7e8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_pci_ioda2_table_alloc_pages
```
```
In kernel/dma/swiotlb.c (c0000000001f6d40)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/verifier.c (c00000000030b5e8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
```
```
In kernel/bpf/arraymap.c (c000000000324218)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/btf.c (c00000000032d83c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (c00000000034db44)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (c0000000003a2cb4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (c00000000137e0e8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (c0000000003e1fc8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/cma.c (c000000001387590)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (c0000000004b730c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (c0000000004e441c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (c00000000138b3f4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (c000000000520554)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (c0000000005f5248)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (c0000000005f7a20)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (c00000000060b960)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (c00000000062bfb0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (c00000000075367c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-settings.c (c00000000077c518)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/blk-settings.c:blk_queue_chunk_sectors
```
```
In block/partition-generic.c (c0000000007973bc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/kfifo.c (c0000000007d901c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (c0000000007dfc60)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (c0000000008119e0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpio-mmio.c (c000000000848a08)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_init
```
```
In drivers/pci/pci.c (c00000000085d34c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/base/memory.c (c0000000013ab4a0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (c0000000009b66f8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (c0000000009c8b68)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (c0000000009ff0e8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (c000000000a4c0d0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/ata/libata-core.c (c000000000a608bc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (c000000000be3d7c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (c000000000bf3e00)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (c000000000c26348)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (c000000000c9fd00)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (c000000000ebdd80)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (c000000000ec11f0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffe0001282a0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/verifier.c (ffffffe0001a1b44)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
```
```
In kernel/bpf/arraymap.c (ffffffe0001b2a9a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/btf.c (ffffffe0001b8f36)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffe0001ce15e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffe0001f9686)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffe00001455e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffe000218d82)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
```
```
In mm/cma.c (ffffffe000019e8e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffe00027bf9e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffe00029645c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (ffffffe00001ca8e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffe0002ba612)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffe00033a622)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffe00033c6c0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffe0003493ee)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffe00035d8c4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffe00040da8c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-settings.c (ffffffe000429022)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/partition-generic.c (ffffffe0004394a6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/kfifo.c (ffffffe000461bda)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffe000465f5e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004adc92)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_init
```
```
In drivers/pci/pci.c (ffffffe0004bc682)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffe000511148)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/base/regmap/regmap.c (ffffffe000595a64)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffe0005a1ba0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (ffffffe0005c1e2e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005ef7f6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/ata/libata-core.c (ffffffe0005fd042)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffe0006e91d6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (ffffffe0006f3642)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffe0007072fe)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffe000751c12)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (ffffffe0008abb12)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad8bc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b8ff)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
```
In kernel/dma/swiotlb.c (ffffffff81128947)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/verifier.c (ffffffff811dbaf6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
```
```
In kernel/bpf/arraymap.c (ffffffff811eec77)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/btf.c (ffffffff811f4e56)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff8120b33c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff81245353)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff828c5832)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff81272435)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/cma.c (ffffffff828cc7de)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff812fecb9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff8131d61a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (ffffffff828cf5b1)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff81349016)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff813dde37)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff813e0972)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff813ee8ab)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff81404b46)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff814c58ae)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-settings.c (ffffffff814e25e8)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/partition-generic.c (ffffffff814f3fb3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/kfifo.c (ffffffff815217bd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff81525894)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff8154b3f3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8156a305)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_init
```
```
In drivers/pci/pci.c (ffffffff815744d2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff81618ef6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff816a3295)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a693c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/memory.c (ffffffff828f0751)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff816e620e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff816f2f17)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (ffffffff8170627e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff817396bc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/nvme/host/core.c (ffffffff81742039)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_set_queue_limits
```
```
In drivers/ata/libata-core.c (ffffffff81757c5c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff81848410)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (ffffffff81853635)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff818776ca)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff818c8ee0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (ffffffff81a49f29)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (ffffffff81a4befa)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8102b0af)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
```
In kernel/dma/swiotlb.c (ffffffff8111b1d7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/verifier.c (ffffffff811ce8b6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
```
```
In kernel/bpf/arraymap.c (ffffffff811e1a07)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/btf.c (ffffffff811e7ba6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff811fe10c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff81238303)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff828bdf57)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff812643a5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/cma.c (ffffffff828c4efa)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff812ef8d9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff8130e1ba)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (ffffffff828c7ccd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff81339cf6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff813ce8b7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff813d13f2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff813df32b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff813f55c6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff814b62ce)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-settings.c (ffffffff814d2f78)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/partition-generic.c (ffffffff814e44c3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/kfifo.c (ffffffff81511aad)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff81515b74)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff8153b6d3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pci/pci.c (ffffffff81562c32)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff8160d426)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff81680c85)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8168432c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/memory.c (ffffffff828e7bd8)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff816c084e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff816cd017)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (ffffffff816d9cfe)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171b35c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/nvme/host/core.c (ffffffff81723cc9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_set_queue_limits
```
```
In drivers/ata/libata-core.c (ffffffff81737afc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff8180fa70)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (ffffffff8181ac45)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In net/core/sysctl_net_core.c (ffffffff81882e20)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (ffffffff81a06b19)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (ffffffff81a08aea)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b75f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
```
In kernel/dma/swiotlb.c (ffffffff81126667)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/verifier.c (ffffffff811d98c6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
```
```
In kernel/bpf/arraymap.c (ffffffff811eca47)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/btf.c (ffffffff811f2c26)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff812090dc)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff812430f3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff828d85b2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff812701d5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/cma.c (ffffffff828df55e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff812fcaa9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff8131b0ea)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (ffffffff828e2331)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff81346ae6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff813db2ac)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff813ddcf2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff813ebc2b)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff81401ec6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff814c193e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-settings.c (ffffffff814de678)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/partition-generic.c (ffffffff814f0043)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/kfifo.c (ffffffff8151d84d)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff81521924)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff81547133)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pci/pci.c (ffffffff81573d02)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff81646cd6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff816d1505)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d4bac)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/memory.c (ffffffff829042a3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff8171339e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff817205f7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (ffffffff8174504e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81779e4c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/ata/libata-core.c (ffffffff8178799c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff81897a40)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (ffffffff818a2c65)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff818c8b6a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff81919ee0)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (ffffffff81ab5dd9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7daa)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
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
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103c75f)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
```
In kernel/dma/swiotlb.c (ffffffff81132ca7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In kernel/bpf/verifier.c (ffffffff811e7cd6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
```
```
In kernel/bpf/arraymap.c (ffffffff811faee7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_gen_lookup
  - kernel/bpf/arraymap.c:array_map_gen_lookup
```
```
In kernel/bpf/btf.c (ffffffff81201136)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
```
```
In kernel/events/core.c (ffffffff81217e6c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
```
```
In mm/percpu.c (ffffffff81252883)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff828dd9d3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
```
```
In mm/vmalloc.c (ffffffff8127fc05)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:alloc_vmap_area
```
```
In mm/cma.c (ffffffff828e4975)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - mm/cma.c:cma_declare_contiguous
```
```
In fs/namespace.c (ffffffff8130de04)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
```
In fs/block_dev.c (ffffffff8132cd8a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
```
```
In fs/verity/hash_algs.c (ffffffff828e7747)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
  - fs/verity/hash_algs.c:fsverity_check_hash_algs
```
```
In fs/verity/open.c (ffffffff81359dc6)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/verity/open.c:fsverity_init_merkle_tree_params
```
```
In fs/proc/base.c (0)
Location: include/linux/log2.h:45
Inline: True
```
```
In fs/ext4/super.c (ffffffff813f05a7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/ext4/sysfs.c (ffffffff813f3112)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_attr_store
```
```
In fs/jbd2/revoke.c (ffffffff814015db)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:jbd2_journal_init_revoke
```
```
In fs/fat/inode.c (ffffffff81417e96)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
```
```
In crypto/cbc.c (ffffffff814da40e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In block/blk-settings.c (ffffffff814f74d8)
Location: include/linux/log2.h:45
Inline: True
```
```
In block/partition-generic.c (ffffffff815090d3)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - block/partition-generic.c:rescan_partitions
```
```
In lib/kfifo.c (ffffffff815370bd)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/hexdump.c (ffffffff8153b2a4)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/hexdump.c:hex_dump_to_buffer
```
```
In lib/iommu-helper.c (ffffffff81560f83)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - lib/iommu-helper.c:iommu_area_alloc
```
```
In drivers/pci/pci.c (ffffffff8158e1e2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_set_mps
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/pci.c:pcix_set_mmrbc
```
```
In drivers/clk/clk-divider.c (ffffffff81661266)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_get_val
```
```
In drivers/iommu/iova.c (ffffffff816eb715)
Location: include/linux/log2.h:45
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ef2ac)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/base/memory.c (ffffffff82909fe2)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
```
In drivers/base/regmap/regmap.c (ffffffff8172e58e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/block/loop.c (ffffffff8173b9b7)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/nvdimm/bus.c (ffffffff8176048e)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81793c7c)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/ata/libata-core.c (ffffffff817a17ec)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/md/md-bitmap.c (ffffffff818b3c20)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:chunksize_store
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-table.c (ffffffff818beea5)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_calculate_queue_limits
```
```
In drivers/mmc/core/core.c (ffffffff818e568a)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_init_erase
```
```
In net/core/sysctl_net_core.c (ffffffff8193b120)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_table_len_sysctl
```
```
In net/xdp/xsk.c (ffffffff81ac1fe9)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_init_queue
```
```
In net/xdp/xdp_umem.c (ffffffff81ac41ca)
Location: include/linux/log2.h:45
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
</ul>

## Differences
