# Function: <code>__get_free_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81191b40)
Location: mm/page_alloc.c:3260
Inline: True
Inline callers:
  - mm/page_alloc.c:get_zeroed_page
  - mm/page_alloc.c:alloc_pages_exact
Direct callers:
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pte_alloc_one_kernel
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/groups.c:groups_alloc
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swsusp_read
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - mm/memory.c:__tlb_remove_page
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:SyS_mincore
  - mm/slub.c:alloc_loc_track
  - mm/migrate.c:SyS_move_pages
  - fs/select.c:__pollwait
  - fs/namespace.c:copy_mount_options
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/dir.c:fuse_follow_link
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/blkcipher.c:blkcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kmalloc
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - net/core/neighbour.c:neigh_hash_alloc
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81191b40-ffffffff81191b7b: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a90c6)
Location: mm/page_alloc.c:3728
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
Direct callers:
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pte_alloc_one_kernel
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/groups.c:groups_alloc
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:SyS_mincore
  - mm/slub.c:alloc_loc_track
  - mm/migrate.c:SyS_move_pages
  - fs/select.c:__pollwait
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/blkcipher.c:blkcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kmalloc
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/pci/host/pcie-designware.c:dw_pcie_msi_init
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - net/core/neighbour.c:neigh_hash_alloc
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff811a6720-ffffffff811a6755: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b6a90)
Location: mm/page_alloc.c:3869
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pte_alloc_one_kernel
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:SyS_mincore
  - mm/slub.c:alloc_loc_track
  - mm/migrate.c:SYSC_move_pages
  - fs/select.c:__pollwait
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kmalloc
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/pci/host/pcie-designware.c:dw_pcie_msi_init
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - net/core/neighbour.c:neigh_hash_alloc
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - lib/dma-noop.c:dma_noop_alloc
```
**Symbols:**

```
ffffffff811b6a90-ffffffff811b6abf: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811be930)
Location: mm/page_alloc.c:4156
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pte_alloc_one_kernel
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:SyS_mincore
  - mm/slub.c:alloc_loc_track
  - mm/migrate.c:SYSC_move_pages
  - fs/select.c:__pollwait
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/configfs/file.c:configfs_write_file
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kmalloc
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - net/core/neighbour.c:neigh_hash_alloc
  - net/sched/sch_api.c:qdisc_class_hash_alloc
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - lib/dma-virt.c:dma_virt_alloc
```
**Symbols:**

```
ffffffff811be930-ffffffff811be963: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d36a0)
Location: mm/page_alloc.c:4275
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pte_alloc_one_kernel
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/memory.c:print_vma_addr
  - mm/memory.c:tlb_remove_table
  - mm/mincore.c:SyS_mincore
  - mm/slub.c:alloc_loc_track
  - mm/migrate.c:SYSC_move_pages
  - fs/select.c:__pollwait
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/configfs/file.c:configfs_write_file
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kmalloc
  - lib/percpu_ida.c:__percpu_ida_init
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - lib/dma-virt.c:dma_virt_alloc
```
**Symbols:**

```
ffffffff811d36a0-ffffffff811d36d3: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f4960)
Location: mm/page_alloc.c:4407
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pte_alloc_one_kernel
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/memory.c:print_vma_addr
  - mm/memory.c:tlb_remove_table
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/configfs/file.c:configfs_write_file
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/percpu_ida.c:__percpu_ida_init
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_expand
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff811f4960-ffffffff811f498f: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81206da0)
Location: mm/page_alloc.c:4587
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pte_alloc_one_kernel
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/configfs/file.c:configfs_write_file
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff81206da0-ffffffff81206dd2: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126cdd0)
Location: mm/page_alloc.c:4754
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_file
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff8126cdd0-ffffffff8126ce02: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127bbe0)
Location: mm/page_alloc.c:4772
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/hyperv/hv_init.c:hv_alloc_hyperv_page
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_file
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff8127bbe0-ffffffff8127bc12: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b1c13)
Location: mm/page_alloc.c:4875
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/hyperv/hv_init.c:hv_alloc_hyperv_zeroed_page
  - arch/x86/hyperv/hv_init.c:hv_alloc_hyperv_page
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:get_swap_reader
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:do_proc_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_file
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/file.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:key_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:key_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/core.c:check_partition
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:grow_gnttab_list
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff812add30-ffffffff812add62: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bd58d)
Location: mm/page_alloc.c:5026
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/hyperv/hv_init.c:hv_alloc_hyperv_zeroed_page
  - arch/x86/hyperv/hv_init.c:hv_alloc_hyperv_page
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:get_swap_reader
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_mem_alloc
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:do_proc_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_file
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/file.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:key_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:key_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/core.c:check_partition
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:grow_gnttab_list
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/iommu/amd/init.c:iommu_init_ga_log
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff812b9810-ffffffff812b9842: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c2520)
Location: mm/page_alloc.c:5227
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_mem_alloc
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_file
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/core.c:check_partition
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff812bebe0-ffffffff812bec12: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81305ef0)
Location: mm/page_alloc.c:5416
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
Direct callers:
  - init/do_mounts.c:mount_root
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/sparse-vmemmap.c:vmemmap_remap_range
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_mem_alloc
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_iter
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/core.c:check_partition
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_init
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff81301470-ffffffff813014a2: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136df50)
Location: mm/page_alloc.c:5471
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_iter
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/core.c:check_partition
  - io_uring/io_uring.c:io_mem_alloc
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:copy_device_table
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/vfio/vfio_iommu_type1.c:vfio_batch_init
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff81368ca0-ffffffff81368ce2: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e6850)
Location: mm/page_alloc.c:5595
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/platform/efi/efi.c:realloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_iter
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/core.c:check_partition
  - io_uring/io_uring.c:io_mem_alloc
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:alloc_pci_segment
  - drivers/iommu/amd/init.c:alloc_pci_segment
  - drivers/iommu/amd/init.c:alloc_pci_segment
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff813e4c20-ffffffff813e4c62: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141b7ee)
Location: mm/page_alloc.c:4523
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/platform/efi/efi.c:realloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_iter
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/core.c:check_partition
  - io_uring/io_uring.c:io_mem_alloc
  - io_uring/kbuf.c:io_register_pbuf_ring
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:alloc_pci_segment
  - drivers/iommu/amd/init.c:alloc_pci_segment
  - drivers/iommu/amd/init.c:alloc_pci_segment
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/buffer.c:hcd_buffer_alloc_pages
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/hv/hv_common.c:hv_alloc_hyperv_page
  - drivers/hv/hv_common.c:hv_common_init
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
**Symbols:**

```
ffffffff81419700-ffffffff81419742: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144882e)
Location: mm/page_alloc.c:4612
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/platform/efi/efi.c:realloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_iter
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - security/integrity/ima/ima_crypto.c:ima_alloc_pages
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/core.c:check_partition
  - io_uring/io_uring.c:io_mem_alloc
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_setup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:alloc_pci_segment
  - drivers/iommu/amd/init.c:alloc_pci_segment
  - drivers/iommu/amd/init.c:alloc_pci_segment
  - drivers/iommu/amd/init.c:__copy_device_table
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_alloc
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/buffer.c:hcd_buffer_alloc_pages
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/hv/hv_common.c:hv_alloc_hyperv_page
  - drivers/hv/hv_common.c:hv_common_init
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
**Symbols:**

```
ffffffff81446440-ffffffff81446482: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103170d8)
Location: mm/page_alloc.c:4772
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
Direct callers:
  - arch/arm64/mm/pgd.c:pgd_alloc
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:kvm_phys_addr_ioremap
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - arch/arm/xen/mm.c:xen_get_swiotlb_free_pages
  - arch/arm/xen/mm.c:xen_get_swiotlb_free_pages
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_file
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffff8000103131a8-ffff800010313208: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c053397c)
Location: mm/page_alloc.c:4772
Inline: False
Direct callers:
  - arch/arm/mm/pgd.c:pgd_alloc
  - arch/arm/mm/mmu.c:late_alloc
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__se_sys_mincore
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/vmcore.c:vmcore_init
  - fs/configfs/file.c:configfs_write_file
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/ipv4/fib_semantics.c:fib_info_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
c053397c-c05339b8: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e46c0)
Location: mm/page_alloc.c:4772
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/iommu.c:tce_setrange_multi_pSeriesLP
  - kernel/fork.c:mm_init
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:__se_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_file
  - fs/jbd2/journal.c:jbd2_alloc
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
c0000000003e46c0-c0000000003e4734: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021ec76)
Location: mm/page_alloc.c:4772
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__se_sys_mincore
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/configfs/file.c:configfs_write_file
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffe00021ec76-ffffffe00021ecd4: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81274230)
Location: mm/page_alloc.c:4772
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/hyperv/hv_init.c:hv_alloc_hyperv_page
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_file
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff81274230-ffffffff81274262: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812661a0)
Location: mm/page_alloc.c:4772
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_alloc_hyperv_page
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_file
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/hv/connection.c:vmbus_connect
  - drivers/hv/connection.c:vmbus_connect
  - drivers/hv/connection.c:vmbus_connect
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff812661a0-ffffffff812661d2: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81271fd0)
Location: mm/page_alloc.c:4772
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/hyperv/hv_init.c:hv_alloc_hyperv_page
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_file
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff81271fd0-ffffffff81272002: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int __get_free_pages(gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81281a30)
Location: mm/page_alloc.c:4772
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/hyperv/hv_init.c:hv_alloc_hyperv_page
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/kernel/tce_64.c:build_tce_table
  - arch/x86/mm/init.c:alloc_low_pages
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_header_init
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:write_page
  - kernel/power/swap.c:write_page
  - kernel/dma/virt.c:dma_virt_alloc
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/trace/ftrace.c:ftrace_process_locs
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:__tlb_remove_page_size
  - mm/page_alloc.c:alloc_pages_exact
  - mm/page_alloc.c:get_zeroed_page
  - mm/slub.c:alloc_loc_track
  - fs/select.c:__pollwait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/quota/dquot.c:dquot_init
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/configfs/file.c:configfs_write_file
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - block/partitions/check.c:check_partition
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_alloc
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/neighbour.c:neigh_hash_alloc
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_set_ring
  - net/xdp/xsk_queue.c:xskq_create
```
**Symbols:**

```
ffffffff81281a30-ffffffff81281a62: __get_free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
