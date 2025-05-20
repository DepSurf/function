# Function: <code>raw_atomic_add_unless</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008399)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff8213e241)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931ce)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810969ca)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e82f5)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
```
```
In kernel/cred.c (ffffffff81133751)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff81144365)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/locking/mutex.c (ffffffff8118db45)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/hibernate.c (ffffffff81194025)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff811ae204)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/module/main.c (ffffffff811db4d7)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81256ab5)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/events/core.c (ffffffff8136775a)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:get_pmu_ctx
```
```
In kernel/events/uprobes.c (ffffffff8137fd57)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/filemap.c (ffffffff8138e109)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In mm/vmscan.c (ffffffff813a9271)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff813daea3)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813e3b92)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813ea8d0)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/rmap.c (ffffffff8140f4ae)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff81425832)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swapfile.c (ffffffff814329b3)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff814464e3)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff81452ed9)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81469125)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8146e4f2)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
```
```
In mm/huge_memory.c (ffffffff81478295)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff81488ede)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814999a2)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff814a2acb)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
```
```
In fs/super.c (ffffffff814b34e4)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff815262ef)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/mbcache.c (ffffffff8154c98f)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/proc/task_mmu.c (ffffffff81564ffc)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81569591)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8156ae0a)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff815831ef)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/ext4/balloc.c (ffffffff8158fdc5)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815a7ec6)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff815cd686)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81600e41)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/fuse/file.c (ffffffff8165b37e)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff81786e4d)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/timeout.c (ffffffff817d9dd1)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In drivers/phy/phy-core.c (ffffffff818e9cc4)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8192ac29)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a317b5)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81a3f353)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81a688c3)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba3f5)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abfd83)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff81adbbe0)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a0a4)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/base/core.c (ffffffff81b3352b)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff81b4fa92)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff81bcab94)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81c2e547)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fe2c)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff81c73c05)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c80987)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81c84248)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81c8df1c)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f7c4)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81ce5fd5)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d3712e)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d3764a)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9dfe3)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc3315)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4a9e)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de327a)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff82005d43)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In lib/dec_and_lock.c (ffffffff8209fb60)
Location: include/linux/atomic/atomic-arch-fallback.h:2432
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
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
In arch/x86/events/core.c (ffffffff8100dab9)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff82220231)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a63e)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109df3a)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f0695)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114f885)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/locking/mutex.c (ffffffff8119c4f5)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/hibernate.c (ffffffff811a2a15)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff811bde04)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/module/main.c (ffffffff811f1187)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81270975)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/events/core.c (ffffffff81394b09)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:get_pmu_ctx
```
```
In kernel/events/uprobes.c (ffffffff813a8fa2)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/filemap.c (ffffffff813b905f)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_folio
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:filemap_get_entry
```
```
In mm/vmscan.c (ffffffff813d63e5)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff81404d9a)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8140e402)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff81416ffc)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/rmap.c (ffffffff8143be78)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff81452a84)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/swapfile.c (ffffffff8146bdd3)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8147ff83)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_hugetlb_folio
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff8148d739)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81498045)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff8149ee82)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
```
```
In mm/huge_memory.c (ffffffff814a79d5)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff814b45e3)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
```
```
In mm/memory-failure.c (ffffffff814c9143)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff814d395b)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_folio
```
```
In fs/super.c (ffffffff814e478c)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - fs/super.c:get_bdev_super
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff8155953a)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_move
  - fs/userfaultfd.c:userfaultfd_poison
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_writeprotect
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/mbcache.c (ffffffff815827bf)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/proc/task_mmu.c (ffffffff8159c3fc)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff815a1bb1)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff815a37ea)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff815bbe3f)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/ext4/balloc.c (ffffffff815c8954)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff815e1ad6)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81605f06)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_clear_bb
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_discard_allocated_blocks
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_mb_mark_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff81639b91)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/fuse/file.c (ffffffff8169504e)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff817c952d)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/timeout.c (ffffffff8181dfe1)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In drivers/phy/phy-core.c (ffffffff81931164)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff819734b9)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7cc25)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81a8ac83)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81ab9be4)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d135)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b12c03)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:__uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/tty/serdev/core.c (ffffffff81b2ef40)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81274)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In drivers/base/core.c (ffffffff81b8ae6a)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff81ba8012)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff81c1f7c4)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81ce0f97)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2cec)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff81d285c5)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d35357)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81d38c48)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81d42a3c)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d5441b)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81d9b085)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded366)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded8ca)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e55d63)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7bbf5)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d37e)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e9936a)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d4b95)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In lib/dec_and_lock.c (ffffffff82177b30)
Location: include/linux/atomic/atomic-arch-fallback.h:2441
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_raw_lock
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
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
