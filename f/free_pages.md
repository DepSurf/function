# Function: <code>free_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81194df0)
Location: mm/page_alloc.c:3295
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:free_pages_exact
Direct callers:
  - arch/x86/events/intel/pt.c:pt_buffer_fini_topa
  - arch/x86/xen/mmu.c:xen_pgd_free
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/kernel/pci-dma.c:dma_generic_free_coherent
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/pageattr.c:try_to_free_pud_page
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/groups.c:groups_free
  - kernel/groups.c:groups_alloc
  - kernel/power/swap.c:swap_read_page
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/user_namespace.c:map_write
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:event_filter_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:subsystem_filter_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_events_trigger.c:event_trigger_write
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:free_pages_exact
  - mm/memory.c:tlb_finish_mmu
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:SyS_mincore
  - mm/slub.c:__kmem_cache_create
  - mm/migrate.c:SyS_move_pages
  - fs/super.c:mount_fs
  - fs/super.c:mount_fs
  - fs/select.c:poll_freewait
  - fs/namespace.c:copy_mount_options
  - fs/namespace.c:SyS_mount
  - fs/libfs.c:simple_transaction_release
  - fs/libfs.c:free_page_put_link
  - fs/compat.c:compat_SyS_mount
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_attr_write
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/kernfs/symlink.c:kernfs_iop_follow_link
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/dir.c:fuse_follow_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_write_avc_cache_threshold
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_commit_bools_write
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_write_bool
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/blkcipher.c:blkcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_free_table
  - lib/percpu_ida.c:percpu_ida_destroy
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_free_chunk_page
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:alloc_new_range
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping
  - drivers/base/devres.c:devm_pages_release
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_update_state
  - net/core/dev.c:__dev_alloc_name
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/sched/sch_api.c:qdisc_class_hash_free
  - net/netlink/af_netlink.c:free_pg_vec
  - net/ipv4/fib_semantics.c:fib_info_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff81194df0-ffffffff81194e32: free_pages.part.78 (STB_LOCAL)
ffffffff81194e40-ffffffff81194e56: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811a9135)
Location: mm/page_alloc.c:3763
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/pt.c:pt_buffer_fini_topa
  - arch/x86/xen/mmu.c:xen_pgd_free
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/pci-dma.c:dma_generic_free_coherent
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/groups.c:groups_free
  - kernel/groups.c:groups_alloc
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swap_read_page
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:tlb_finish_mmu
  - mm/mincore.c:SyS_mincore
  - mm/slub.c:__kmem_cache_create
  - mm/migrate.c:SyS_move_pages
  - fs/super.c:mount_fs
  - fs/super.c:mount_fs
  - fs/select.c:poll_freewait
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/jbd2/journal.c:jbd2_free
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/blkcipher.c:blkcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_free_table
  - lib/percpu_ida.c:percpu_ida_destroy
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_free_chunk_page
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_update_state
  - net/core/dev.c:__dev_alloc_name
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/sched/sch_api.c:qdisc_class_hash_free
  - net/ipv4/fib_semantics.c:fib_info_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff811a8f50-ffffffff811a8f99: free_pages.part.80 (STB_LOCAL)
ffffffff811a8fa0-ffffffff811a8fb6: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811b9695)
Location: mm/page_alloc.c:3904
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/pt.c:pt_buffer_fini_topa
  - arch/x86/xen/mmu.c:xen_pgd_free
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/kernel/pci-dma.c:dma_generic_free_coherent
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swap_read_page
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:tlb_finish_mmu
  - mm/mincore.c:SyS_mincore
  - mm/slub.c:__kmem_cache_create
  - mm/migrate.c:SYSC_move_pages
  - fs/super.c:mount_fs
  - fs/super.c:mount_fs
  - fs/select.c:poll_freewait
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/jbd2/journal.c:jbd2_free
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_free_table
  - lib/percpu_ida.c:percpu_ida_destroy
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_free_chunk_page
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel_irq_remapping.c:intel_teardown_irq_remapping
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:__dev_alloc_name
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/sched/sch_api.c:qdisc_class_hash_free
  - net/ipv4/fib_semantics.c:fib_info_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/dma-noop.c:dma_noop_free
```
**Symbols:**

```
ffffffff811b94f0-ffffffff811b9533: free_pages.part.81 (STB_LOCAL)
ffffffff811b9540-ffffffff811b9556: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811c1705)
Location: mm/page_alloc.c:4191
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/pt.c:pt_buffer_fini_topa
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/kernel/pci-dma.c:dma_generic_free_coherent
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_init_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:arch_tlb_finish_mmu
  - mm/mincore.c:SyS_mincore
  - mm/slub.c:__kmem_cache_create
  - mm/migrate.c:SYSC_move_pages
  - fs/super.c:mount_fs
  - fs/super.c:mount_fs
  - fs/select.c:poll_freewait
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/jbd2/journal.c:jbd2_free
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/apparmor/apparmorfs.c:put_multi_transaction
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_free_table
  - lib/percpu_ida.c:percpu_ida_destroy
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_free_chunk_page
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_put
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu_init.c:free_dma_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:__dev_alloc_name
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/sched/sch_api.c:qdisc_class_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/dma-virt.c:dma_virt_free
```
**Symbols:**

```
ffffffff811c1560-ffffffff811c15a3: free_pages.part.87 (STB_LOCAL)
ffffffff811c15b0-ffffffff811c15c7: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5b25)
Location: mm/page_alloc.c:4310
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_fini_topa
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/kernel/pci-dma.c:dma_generic_free_coherent
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:free_transition_pgtable
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:tlb_remove_table_rcu
  - mm/memory.c:arch_tlb_finish_mmu
  - mm/mincore.c:SyS_mincore
  - mm/slub.c:__kmem_cache_create
  - mm/migrate.c:SYSC_move_pages
  - fs/super.c:mount_fs
  - fs/super.c:mount_fs
  - fs/select.c:poll_freewait
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/jbd2/journal.c:jbd2_free
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/apparmor/apparmorfs.c:multi_transaction_kref
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_free_table
  - lib/percpu_ida.c:percpu_ida_destroy
  - lib/swiotlb.c:swiotlb_free_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - lib/swiotlb.c:swiotlb_free
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_free_chunk_page
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu_init.c:free_dma_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
  - lib/dma-virt.c:dma_virt_free
```
**Symbols:**

```
ffffffff811d5980-ffffffff811d59c3: free_pages.part.90 (STB_LOCAL)
ffffffff811d59d0-ffffffff811d59e7: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811f6f36)
Location: mm/page_alloc.c:4442
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_fini_topa
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:tlb_remove_table_rcu
  - mm/memory.c:arch_tlb_finish_mmu
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/slub.c:__kmem_cache_create
  - fs/super.c:mount_fs
  - fs/super.c:mount_fs
  - fs/select.c:poll_freewait
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_copy_data
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/smack/smack_lsm.c:smack_sb_copy_data
  - security/apparmor/apparmorfs.c:multi_transaction_kref
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kfree
  - lib/percpu_ida.c:percpu_ida_destroy
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_free_chunk_page
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:free_pt_l5
  - drivers/iommu/amd_iommu.c:free_pt_l4
  - drivers/iommu/amd_iommu.c:free_pt_l3
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:free_pt_l2
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu_init.c:free_dma_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff811f6d90-ffffffff811f6dd3: free_pages.part.94 (STB_LOCAL)
ffffffff811f6de0-ffffffff811f6df6: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff812092d6)
Location: mm/page_alloc.c:4619
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_fini_topa
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/mmu_gather.c:arch_tlb_finish_mmu
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:multi_transaction_kref
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - lib/scatterlist.c:sg_kfree
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_page_list
  - drivers/iommu/amd_iommu_init.c:free_dma_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff81209130-ffffffff81209173: free_pages.part.99 (STB_LOCAL)
ffffffff81209180-ffffffff81209196: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81270716)
Location: mm/page_alloc.c:4786
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_fini_topa
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:multi_transaction_kref
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kfree
  - lib/generic-radix-tree.c:genradix_free_recurse
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_page_list
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff81270550-ffffffff81270593: free_pages.part.0 (STB_LOCAL)
ffffffff812705a0-ffffffff812705b6: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff8127f556)
Location: mm/page_alloc.c:4804
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_free_hyperv_page
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:multi_transaction_kref
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kfree
  - lib/generic-radix-tree.c:genradix_free_recurse
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_page_list
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff8127f390-ffffffff8127f3d3: free_pages.part.0 (STB_LOCAL)
ffffffff8127f3e0-ffffffff8127f3f6: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b1a7c)
Location: mm/page_alloc.c:4907
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_free_hyperv_page
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pte_range
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:get_swap_reader
  - kernel/power/swap.c:get_swap_reader
  - kernel/power/swap.c:get_swap_reader
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:get_swap_writer
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_insert_pages
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:do_proc_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/vmcore.c:vmcore_cleanup
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:key_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:key_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_free_table
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:grow_gnttab_list
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_map_page
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:free_ga_log
  - drivers/iommu/amd/init.c:free_ga_log
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_unmap
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:intel_unmap
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:iova_entry_free
  - drivers/iommu/intel/iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/ipv4/fib_semantics.c:fib_info_hash_move
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff812b1670-ffffffff812b16b9: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bd3fe)
Location: mm/page_alloc.c:5081
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/xen/time.c:xen_setup_vsyscall_time_info
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_free_hyperv_page
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:get_swap_reader
  - kernel/power/swap.c:get_swap_reader
  - kernel/power/swap.c:get_swap_reader
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_insert_pages
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/slub.c:free_loc_track
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:do_proc_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:key_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:key_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/scatterlist.c:sg_free_table
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:get_free_page_and_send
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:grow_gnttab_list
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenstored_local_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/iommu.c:iommu_map_page
  - drivers/iommu/amd/iommu.c:increase_address_space
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:free_ga_log
  - drivers/iommu/amd/init.c:free_ga_log
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/dma-iommu.c:iommu_dma_entry_dtor
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff812bd000-ffffffff812bd049: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c238e)
Location: mm/page_alloc.c:5282
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/slub.c:free_loc_track
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/scatterlist.c:sg_free_table
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:free_ga_log
  - drivers/iommu/amd/init.c:free_ga_log
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/dma-iommu.c:iommu_dma_entry_dtor
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff812c1eb0-ffffffff812c1ef9: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81305d7e)
Location: mm/page_alloc.c:5463
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - init/do_mounts.c:mount_root
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/slub.c:slab_debug_trace_release
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_alloc_table
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:free_ga_log
  - drivers/iommu/amd/init.c:free_ga_log
  - drivers/iommu/amd/io_pgtable.c:v1_free_pgtable
  - drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:domain_exit
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/dma-iommu.c:iommu_dma_entry_dtor
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff81305810-ffffffff81305859: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136ddbe)
Location: mm/page_alloc.c:5518
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
  - mm/slub.c:slab_debug_trace_release
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/libfs.c:simple_transaction_get
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_alloc_table
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/stackdepot.c:__stack_depot_save
  - lib/stackdepot.c:__stack_depot_save
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:free_ga_log
  - drivers/iommu/amd/init.c:free_ga_log
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/firmware/efi/memmap.c:__efi_memmap_free
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff8136dc70-ffffffff8136dccd: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ea28e)
Location: mm/page_alloc.c:5645
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:free_pages_exact
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - arch/x86/platform/efi/efi.c:realloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
  - mm/slub.c:slab_debug_trace_release
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/libfs.c:simple_transaction_get
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_free_append_table
  - lib/scatterlist.c:sg_free_append_table
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/stackdepot.c:__stack_depot_save
  - lib/stackdepot.c:__stack_depot_save
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff813ea120-ffffffff813ea17d: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141f26e)
Location: mm/page_alloc.c:4573
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:free_pages_exact
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - arch/x86/platform/efi/efi.c:realloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_free_pages
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
  - mm/slub.c:slab_debug_trace_release
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/libfs.c:simple_transaction_get
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_free_append_table
  - lib/scatterlist.c:sg_free_append_table
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/stackdepot.c:__stack_depot_save
  - lib/stackdepot.c:__stack_depot_save
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_attach_device
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/hv/hv_common.c:hv_common_free
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:__dev_alloc_name
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff8141f100-ffffffff8141f15d: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144bf2e)
Location: mm/page_alloc.c:4662
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:free_pages_exact
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
  - arch/x86/hyperv/ivm.c:hv_snp_boot_ap
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/platform/efi/memmap.c:__efi_memmap_free
  - arch/x86/platform/efi/efi.c:realloc_pages
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:fill_page_cache_func
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/dma/swiotlb.c:swiotlb_dyn_free
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_init_late
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_free_pages
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:rb_remove_pages
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:free_saved_cmdlines_buffer
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__p4d_alloc
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/slub.c:slab_debug_trace_release
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/libfs.c:simple_transaction_get
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release_bin_file
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/ioctl.c:fuse_do_ioctl
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_sidtab_hash_stats
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/integrity/ima/ima_crypto.c:ima_free_pages
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/core.c:check_partition
  - block/partitions/core.c:check_partition
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_free_append_table
  - lib/scatterlist.c:sg_free_append_table
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/stackdepot.c:stack_depot_save_flags
  - lib/stackdepot.c:stack_depot_save_flags
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:set_evtchn_to_irq
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_save_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:protection_domain_free
  - drivers/iommu/amd/iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:state_next
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/init.c:free_pci_segments
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:free_pgtable
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:dma_pte_free_level
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_free_table
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_alloc
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/buffer.c:hcd_buffer_free_pages
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/hv/hv_common.c:hv_common_free
  - drivers/hv/hv_common.c:hv_common_init
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff8144bdc0-ffffffff8144be1d: free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffff800010317178)
Location: mm/page_alloc.c:4804
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/arm64/kernel/vdso.c:aarch32_alloc_vdso_pages
  - arch/arm64/mm/pgd.c:pgd_free
  - arch/arm64/mm/mmu.c:pud_free_pmd_page
  - virt/kvm/kvm_main.c:kvm_vcpu_uninit
  - virt/kvm/kvm_main.c:kvm_vcpu_init
  - virt/kvm/coalesced_mmio.c:kvm_coalesced_mmio_free
  - virt/kvm/arm/arm.c:teardown_hyp_mode
  - virt/kvm/arm/mmu.c:kvm_mmu_free_memory_caches
  - virt/kvm/arm/mmu.c:kvm_phys_addr_ioremap
  - virt/kvm/arm/mmu.c:free_hyp_pgds
  - virt/kvm/arm/mmu.c:free_hyp_pgds
  - virt/kvm/arm/mmu.c:free_hyp_pgds
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__do_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kfree
  - lib/generic-radix-tree.c:genradix_free_recurse
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_free_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_free_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_free_prop_table
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffff800010316f30-ffff800010316f78: free_pages.part.0 (STB_LOCAL)
ffff800010316f78-ffff800010316fbc: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (c05318a0)
Location: mm/page_alloc.c:4804
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/arm/mm/pgd.c:pgd_free
  - arch/arm/mm/pgd.c:pgd_alloc
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:release_swap_reader
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/dma/virt.c:dma_virt_free
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__se_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/slub.c:free_loc_track
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kfree
  - lib/generic-radix-tree.c:genradix_free_recurse
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_free_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_free_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_free_prop_table
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_free_pages
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_free
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/ipv4/fib_semantics.c:fib_info_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
c0531748-c0531780: free_pages.part.0 (STB_LOCAL)
c0531780-c05317a4: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (c0000000003e94fc)
Location: mm/page_alloc.c:4804
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/powerpc/kernel/iommu.c:iommu_free_coherent
  - arch/powerpc/kernel/iommu.c:iommu_alloc_coherent
  - arch/powerpc/kernel/iommu.c:iommu_tce_table_put
  - arch/powerpc/mm/init_64.c:vmemmap_free
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_prot_free
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_prot_free
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_prot_free
  - arch/powerpc/sysdev/xive/native.c:xive_native_cleanup_queue
  - arch/powerpc/sysdev/xive/spapr.c:xive_spapr_cleanup_queue
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_ioda_release_pe
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_pci_ioda2_table_do_free_pages
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_pci_ioda2_table_do_free_pages
  - arch/powerpc/perf/imc-pmu.c:cleanup_all_trace_imc_memory
  - arch/powerpc/perf/imc-pmu.c:cleanup_all_thread_imc_memory
  - arch/powerpc/perf/imc-pmu.c:cleanup_all_core_imc_memory
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/memory.c:print_vma_addr
  - mm/mincore.c:__se_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:put_multi_transaction
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kfree
  - lib/generic-radix-tree.c:genradix_free_recurse
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/tty/tty_port.c:tty_port_put
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
c0000000003e9290-c0000000003e92bc: free_pages.part.0 (STB_LOCAL)
c0000000003e92c0-c0000000003e92dc: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffe00021d3ea)
Location: mm/page_alloc.c:4804
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/fork.c:__mmdrop
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:free_pgd_range
  - mm/mincore.c:__se_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kfree
  - lib/generic-radix-tree.c:genradix_free_recurse
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/tty/tty_port.c:tty_port_put
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffe00021d27e-ffffffe00021d2d8: free_pages.part.0 (STB_LOCAL)
ffffffe00021d2d8-ffffffe00021d30c: free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81277ba6)
Location: mm/page_alloc.c:4804
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_free_hyperv_page
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swap_read_pages
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:multi_transaction_kref
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kfree
  - lib/generic-radix-tree.c:genradix_free_recurse
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_page_list
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff812779e0-ffffffff81277a23: free_pages.part.0 (STB_LOCAL)
ffffffff81277a30-ffffffff81277a46: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81269ab6)
Location: mm/page_alloc.c:4804
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/hyperv/hv_init.c:hv_free_hyperv_page
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:multi_transaction_kref
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kfree
  - lib/generic-radix-tree.c:genradix_free_recurse
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_page_list
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/hv/vmbus_drv.c:vmbus_exit
  - drivers/hv/vmbus_drv.c:hv_acpi_init
  - drivers/hv/hv.c:hv_synic_free
  - drivers/hv/hv.c:hv_synic_free
  - drivers/hv/hv.c:hv_synic_free
  - drivers/hv/connection.c:vmbus_disconnect
  - drivers/hv/connection.c:vmbus_disconnect
  - drivers/hv/connection.c:vmbus_disconnect
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff812698f0-ffffffff81269933: free_pages.part.0 (STB_LOCAL)
ffffffff81269940-ffffffff81269956: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81275946)
Location: mm/page_alloc.c:4804
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_free_hyperv_page
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:multi_transaction_kref
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kfree
  - lib/generic-radix-tree.c:genradix_free_recurse
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_page_list
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff81275780-ffffffff812757c3: free_pages.part.0 (STB_LOCAL)
ffffffff812757d0-ffffffff812757e6: free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_pages(long unsigned int addr, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81285506)
Location: mm/page_alloc.c:4804
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/pt.c:pt_buffer_free_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/time.c:xen_time_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/hv_init.c:hv_free_hyperv_page
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_free_coherent
  - arch/x86/kernel/pci-calgary_64.c:calgary_alloc_coherent
  - arch/x86/mm/init_64.c:free_pagetable
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:save_image_lzo
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_process_locs
  - kernel/trace/ring_buffer.c:ring_buffer_free_read_page
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_free_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/tracing_map.c:tracing_map_array_free
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc
  - mm/memory.c:print_vma_addr
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__pte_alloc_kernel
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table_rcu
  - mm/page_alloc.c:free_pages_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/slub.c:__kmem_cache_create
  - fs/select.c:poll_freewait
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/libfs.c:simple_transaction_release
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/vmcore.c:free_elfcorebuf
  - fs/configfs/file.c:configfs_release
  - fs/ext4/super.c:ext4_calculate_overhead
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_do_ioctl
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/selinuxfs.c:sel_read_avc_hash_stats
  - security/selinux/selinuxfs.c:sel_read_bool
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/apparmor/apparmorfs.c:multi_transaction_kref
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
  - block/partitions/check.c:check_partition
  - block/partitions/check.c:check_partition
  - lib/scatterlist.c:sg_kfree
  - lib/generic-radix-tree.c:genradix_free_recurse
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - drivers/acpi/nvs.c:suspend_nvs_free
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:return_free_pages_to_mm
  - drivers/xen/grant-table.c:gnttab_init
  - drivers/xen/grant-table.c:get_free_entries
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_fifo.c:evtchn_fifo_alloc_control_block
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/events/events_fifo.c:evtchn_fifo_setup
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/tty/tty_port.c:tty_port_destructor
  - drivers/tty/tty_port.c:tty_port_free_xmit_buf
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_remove
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/intel-gtt.c:i810_cleanup
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_free
  - drivers/iommu/amd_iommu.c:free_gcr3_tbl_level1
  - drivers/iommu/amd_iommu.c:iommu_map_page
  - drivers/iommu/amd_iommu.c:free_page_list
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/amd_iommu_init.c:free_ga_log
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:prepare_domain_attach_device
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:dma_free_pagelist
  - drivers/iommu/intel-iommu.c:dma_pte_free_pagetable
  - drivers/iommu/intel-iommu.c:dma_pte_free_level
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-pasid.c:intel_pasid_free_table
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/base/devres.c:devm_get_free_pages
  - drivers/base/devres.c:devm_pages_release
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/usb/host/ohci-hcd.c:debug_close
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/ras/cec.c:cec_init
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/neighbour.c:neigh_hash_free_rcu
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/packet/af_packet.c:free_pg_vec
```
**Symbols:**

```
ffffffff81285340-ffffffff81285383: free_pages.part.0 (STB_LOCAL)
ffffffff81285390-ffffffff812853a6: free_pages (STB_GLOBAL)
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
