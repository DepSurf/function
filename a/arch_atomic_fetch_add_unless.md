# Function: <code>arch_atomic_fetch_add_unless</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007d7a)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff81bbe075)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109eaa5)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
```
```
In kernel/cred.c (ffffffff810d7575)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
```
```
In kernel/locking/mutex.c (ffffffff8110e165)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/hibernate.c (ffffffff81114cb5)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff8112804d)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/module.c (ffffffff811636c5)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119ce35)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/events/core.c (ffffffff81239fa3)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/uprobes.c (ffffffff81245827)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff8124a8f5)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
```
```
In mm/filemap.c (ffffffff8124ff3d)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff812602ef)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff81267817)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81287e6b)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
```
```
In mm/rmap.c (ffffffff812a6623)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812be3df)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812cb341)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812d3ffa)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812e13e2)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
```
```
In mm/migrate.c (ffffffff812e6bdb)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812edf43)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff812f5e16)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/memcontrol.c:mc_handle_present_pte
```
```
In mm/memory-failure.c (ffffffff81300379)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff81309252)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff81317a2e)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - fs/super.c:grab_super
  - fs/super.c:deactivate_super
```
```
In fs/userfaultfd.c (ffffffff81373520)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8137bf92)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
```
```
In fs/io-wq.c (ffffffff8138a5d0)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/proc/task_mmu.c (ffffffff813b6753)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813b9eb6)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813bdb5a)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff813cf1ae)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813ee412)
Location: include/linux/atomic-arch-fallback.h:1086
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
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
  - fs/ext4/ialloc.c:ext4_validate_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81409521)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (0)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In lib/dec_and_lock.c (ffffffff815e8140)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In drivers/phy/phy-core.c (ffffffff815ffeca)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8162ee9e)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f23b5)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816fcae2)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817548a5)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff817586d8)
Location: include/linux/atomic-arch-fallback.h:1086
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
In drivers/tty/serdev/core.c (ffffffff8176d9e4)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/intel/svm.c (ffffffff817a974c)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff817b55d2)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817c9e9d)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff8182f958)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81877d10)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/spi/spi.c:pm_runtime_put_noidle
```
```
In drivers/net/loopback.c (ffffffff8187eb47)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff8189b7f5)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a2841)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In drivers/cdrom/cdrom.c (ffffffff818b0d81)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff818bbab6)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818c41de)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818d2910)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819499a0)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a15c)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81999691)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff819b3283)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b41d0)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81bc3275)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8dd2)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff819e3870)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb716)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81a08615)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a1621f)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a29bbe)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a4fec7)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f908)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a93f44)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81a9a750)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a9c1e9)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9feeb)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5d55)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9ae1)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acda9b)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ad5795)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ad9d17)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81adbf8e)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b022a3)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15cf2)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e76f)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1ff71)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b30a94)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b316a5)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b40e10)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67085)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b70c41)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b747ed)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a940)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b80119)
Location: include/linux/atomic-arch-fallback.h:1086
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In arch/x86/events/core.c (ffffffff81006e2a)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff81c36915)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068071)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a605)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In kernel/cred.c (ffffffff810d2237)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In kernel/locking/mutex.c (ffffffff8110b425)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/hibernate.c (ffffffff811114e5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff81123b5d)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/module.c (ffffffff8115ddf2)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81199e75)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/events/core.c (ffffffff81243631)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/uprobes.c (ffffffff8124fe47)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff81254c95)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
```
```
In mm/filemap.c (ffffffff8125a147)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
```
```
In mm/swap.c (ffffffff8126a41f)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff812725fd)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff8128cb89)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8129182b)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In mm/rmap.c (ffffffff812b1ab8)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff812c9ff9)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812d6f7a)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812df9ea)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812ec29a)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In mm/migrate.c (ffffffff812f1f2b)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff812f95b3)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff813050d1)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8130c629)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff813150a6)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff81322c8e)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/super.c:grab_super
  - fs/super.c:deactivate_super
```
```
In fs/userfaultfd.c (ffffffff813813d0)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8138cf23)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In fs/io-wq.c (ffffffff8139bd60)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/io-wq.c:io_impersonate_work
```
```
In fs/proc/task_mmu.c (ffffffff813c86b3)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813cb946)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813cf8aa)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff813e0dde)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/ext4/balloc.c (0)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81400a40)
Location: include/linux/atomic-arch-fallback.h:1156
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
In fs/ext4/mballoc.c (ffffffff8141b73a)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_group_add_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_discard_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (0)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In lib/dec_and_lock.c (ffffffff8160d317)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In drivers/phy/phy-core.c (ffffffff81624dba)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8165455e)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170f775)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81719a22)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff817324e0)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:channels_on_cpu_inc
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176fba5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81773798)
Location: include/linux/atomic-arch-fallback.h:1156
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
In drivers/tty/serdev/core.c (ffffffff817883c4)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5b22)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff817c9d7e)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817dde37)
Location: include/linux/atomic-arch-fallback.h:1156
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
In drivers/scsi/hosts.c (ffffffff81c1646a)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81886520)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/spi/spi.c:pm_runtime_put_noidle
```
```
In drivers/spi/spi-mem.c (ffffffff8188bee8)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/net/loopback.c (ffffffff8188d0c7)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff818aa405)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2561)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In drivers/cdrom/cdrom.c (ffffffff81c1a577)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff818c8896)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818d00ce)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818dcd00)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f560)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fcec)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c771)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff819b57d3)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b6820)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81c3c1a2)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81c2dbc6)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff819e33c5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819eb436)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81a09bc3)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff81a16e80)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a2a51e)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a55f04)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81a6f3f1)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81a998f8)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a9de80)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81aa46a8)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81aa6049)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaa776)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1be5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5a31)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad9adb)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ae1d33)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ae6777)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ae8aea)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b10644)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b24162)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d0b1)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e881)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f6c4)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b40295)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4f8c6)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75660)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b7f651)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b8355d)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b89890)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f29c)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In arch/x86/events/core.c (ffffffff8100754a)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff81c28db8)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810685e1)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109adc5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In kernel/cred.c (ffffffff810d3e17)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In kernel/locking/mutex.c (ffffffff8110d245)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/hibernate.c (ffffffff81111f35)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff81123ebd)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/module.c (ffffffff811600b2)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119aca5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/events/core.c (ffffffff812485f5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/uprobes.c (ffffffff81254727)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff81259245)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
```
```
In mm/filemap.c (ffffffff8125e112)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
```
```
In mm/swap.c (ffffffff8126f535)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff812777ca)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff812919e1)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8129754a)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In mm/rmap.c (ffffffff812b7188)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff812c69bd)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In mm/swapfile.c (ffffffff812d0a70)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812de579)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff812e6c0a)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812f8266)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff813003a5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8130a5c0)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813143d1)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff8131b79c)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff81328d4e)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/super.c:grab_super
  - fs/super.c:deactivate_super
```
```
In fs/userfaultfd.c (ffffffff81387d78)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_continue
  - fs/userfaultfd.c:userfaultfd_zeropage
  - fs/userfaultfd.c:userfaultfd_copy
  - fs/userfaultfd.c:userfaultfd_register
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/io_uring.c (ffffffff8139774b)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/proc/task_mmu.c (ffffffff813cf6f3)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff813d2936)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813d6977)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff813e790e)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/ext4/balloc.c (ffffffff813f227d)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff81407b9c)
Location: include/linux/atomic-arch-fallback.h:1156
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
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814264e0)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_free_data_in_buddy
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8144f692)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In lib/dec_and_lock.c (ffffffff815f0a77)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In drivers/phy/phy-core.c (ffffffff8160876a)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81636f0e)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0fb5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816fad22)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81717b1c)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753555)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81757158)
Location: include/linux/atomic-arch-fallback.h:1156
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
In drivers/tty/serdev/core.c (ffffffff8176bd14)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/intel/svm.c (ffffffff81798e40)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff817ad596)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817c21b7)
Location: include/linux/atomic-arch-fallback.h:1156
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
In drivers/mfd/arizona-irq.c (ffffffff817ee0ab)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/hosts.c (ffffffff81c08174)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81868d90)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/spi/spi.c:pm_runtime_put_noidle
```
```
In drivers/spi/spi-mem.c (ffffffff8186e848)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/net/loopback.c (ffffffff8186fa07)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff8188d755)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81895881)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
```
```
In drivers/cdrom/cdrom.c (ffffffff81c0c463)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818a9dd9)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff818abed6)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818b36fe)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818c0070)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819339f3)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933bac)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81981441)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81999e63)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8199afd0)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81c2e642)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81c1fd75)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff819c9419)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff819d1946)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff819f0554)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff819fdb28)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81a116be)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81a38f14)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81a57cc4)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81a84c08)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81a88da4)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81a8f79d)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81a91209)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a95d25)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abcbf5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0a90)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac4b29)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81acba06)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ad1a47)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81ad3da5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afe254)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11d92)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1acf6)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c5df)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d562)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e8a5)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b3d5f6)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b64090)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81b6e171)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81b721d0)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81b786e0)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ec5c)
Location: include/linux/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In arch/x86/events/core.c (ffffffff81007db6)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff81d46f48)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072d77)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab0a5)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
```
```
In kernel/cred.c (ffffffff810e6ee7)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff810f25c5)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/locking/mutex.c (ffffffff8112ca85)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/hibernate.c (ffffffff81131f55)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff8114449d)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/module.c (ffffffff81185262)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811c4c45)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/events/core.c (ffffffff81282c4b)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/uprobes.c (ffffffff81290157)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff81294f05)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
```
```
In mm/filemap.c (ffffffff8129a83b)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
```
```
In mm/oom_kill.c (ffffffff812a31ce)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
```
```
In mm/swap.c (ffffffff812ac685)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff812b5179)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff812d12a8)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812d7efe)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
```
```
In mm/rmap.c (ffffffff812f95a8)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff8130b460)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
```
```
In mm/swapfile.c (ffffffff8131614b)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81325869)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8132eb3a)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff813428bc)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff8134a00d)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff81355d1d)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8135f7be)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff81368a6c)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff8137637e)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/super.c:grab_super
  - fs/super.c:deactivate_super
```
```
In fs/userfaultfd.c (ffffffff813d5085)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
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
In fs/io_uring.c (ffffffff813df075)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
```
```
In fs/proc/task_mmu.c (ffffffff81420ad3)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff81423e86)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff814280a7)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff8143961e)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/ext4/balloc.c (ffffffff8144425d)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff8145a466)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
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
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff8147a176)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
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
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff814a3212)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/fuse/file.c (ffffffff814edea0)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
```
```
In lib/dec_and_lock.c (ffffffff8165dbb7)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In drivers/phy/phy-core.c (ffffffff816773aa)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff816a714e)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176b0c5)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81775712)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff8179533a)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d6985)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff817da998)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
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
In drivers/tty/serdev/core.c (ffffffff817f1444)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/iommu-sva-lib.c (ffffffff8182fb85)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva-lib.c:__mmget_not_zero
```
```
In drivers/base/core.c (ffffffff81836847)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8184bb17)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_release_supplier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff81d0bff8)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff818f8940)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/spi/spi.c:pm_runtime_put_noidle
```
```
In drivers/spi/spi-mem.c (ffffffff818fe956)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/net/loopback.c (ffffffff818fffa7)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/vfio.c (ffffffff81920cb5)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_add_container_user
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff819297f1)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
```
```
In drivers/cdrom/cdrom.c (ffffffff81d12ecd)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff8193ece9)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81940f5b)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81948b8e)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff819566f5)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81994ef8)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6dc3)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d6fdc)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a2a833)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81a4667f)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81a4790e)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81d4cd02)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d316d7)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81a787b9)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81a81516)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81aa1982)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81aaf0f5)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81ac2b9e)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81aeede4)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81b10c8c)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f132)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81b43514)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81b4a9dd)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81b4c59d)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b51185)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79985)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e454)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b832d9)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81b8a296)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81b90677)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81b92a65)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbf4e4)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5910)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf263)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0f1d)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81bf3712)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4c74)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c05686)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2bb50)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81c3619a)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81c3c680)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81c43220)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a3c1)
Location: include/linux/atomic/atomic-arch-fallback.h:1156
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In arch/x86/events/core.c (ffffffff810072f9)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff81f15508)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e7cd)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080fa5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb_cpumask
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c0d05)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In kernel/cred.c (ffffffff81101191)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff8110e425)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/locking/mutex.c (ffffffff8114dcd5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/hibernate.c (ffffffff81153c65)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff81167f04)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/module/main.c (ffffffff8118be44)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811f85e5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/events/core.c (ffffffff812ce84e)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:unaccount_event
```
```
In kernel/events/uprobes.c (ffffffff812e5217)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff812eaad5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
```
```
In mm/filemap.c (ffffffff812f148a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/vmscan.c (ffffffff8130d67c)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
```
```
In mm/compaction.c (ffffffff81330a57)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81337e0c)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/gup.c:try_get_folio
```
```
In mm/rmap.c (ffffffff8135fe85)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff813741b4)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In mm/swapfile.c (ffffffff813812e0)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81394462)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff8139ec09)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff813b2ff5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff813c0a59)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff813ce822)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813dd085)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff813e65ca)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff813f5544)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff8145d68b)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
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
In fs/proc/task_mmu.c (ffffffff81498908)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff8149c9dd)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8149df5a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff814b469e)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/ext4/balloc.c (ffffffff814c0140)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff814d78fb)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
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
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff814fc51d)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
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
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
  - fs/ext4/mballoc.c:ext4_mb_init_cache
```
```
In fs/ext4/super.c (ffffffff8152a6c4)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/fuse/file.c (ffffffff8157d29e)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8168bffd)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/io_uring.c (ffffffff816ce685)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_link_timeout_fn
```
```
In lib/dec_and_lock.c (ffffffff817771d3)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In drivers/phy/phy-core.c (ffffffff81792434)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff817c9bd9)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189fca5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In drivers/clk/clk.c (ffffffff818aba53)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff818ce060)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81914a65)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81919903)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
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
In drivers/tty/serdev/core.c (ffffffff81931a50)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/iommu-sva-lib.c (ffffffff81970d85)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva-lib.c:__mmget_not_zero
```
```
In drivers/base/core.c (ffffffff81978856)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff819915b2)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
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
In drivers/scsi/hosts.c (ffffffff81ed4f30)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81a4d711)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff81a502bc)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In drivers/net/loopback.c (ffffffff81a51a6a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a810b5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
```
```
In drivers/cdrom/cdrom.c (ffffffff81eddcf8)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81a96dc1)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81a99379)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81aa16cc)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ab0306)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81af1b8b)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39971)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39c1a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81b94b73)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb4325)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81bb5897)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff81f1c942)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81efdb9c)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81bec17a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81bf525a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81c19ab5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81c27e70)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81c3d85d)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81c71d3e)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81c97e0e)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb879)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81ccffd3)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81cd7841)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81cd9bf1)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cddf2d)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09717)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e442)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d138e2)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81d1db79)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81d21afb)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81d2407d)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d5427e)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c16a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75fcd)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77c6c)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81d89e79)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81d8da9a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In net/ipv6/route.c (ffffffff81d9fc84)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc90cf)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81dd3d9a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81ddaa5d)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81de1f9e)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81de9ab5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In arch/x86/events/core.c (ffffffff81008b69)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/alternative.c (ffffffff820bc9d1)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:poke_int3_handler
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810902ba)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_cpumask
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093a4a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dcd15)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In kernel/cred.c (ffffffff811262a1)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/cred.c:get_task_cred
```
```
In kernel/sched/core.c (ffffffff81135155)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_put
  - kernel/sched/core.c:sched_core_get
```
```
In kernel/locking/mutex.c (ffffffff8117ce95)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/power/hibernate.c (ffffffff811831b5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernate_acquire
```
```
In kernel/irq/chip.c (ffffffff8119c3b4)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/module/main.c (ffffffff811c8574)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/module/main.c:try_module_get
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8123fa45)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/events/core.c (ffffffff8133699a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/events/core.c:account_event
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:unaccount_event
  - kernel/events/core.c:get_pmu_ctx
```
```
In kernel/events/uprobes.c (ffffffff8134ebc4)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In kernel/jump_label.c (ffffffff81354a35)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - kernel/jump_label.c:static_key_slow_try_dec
```
```
In mm/filemap.c (ffffffff8135be2a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/filemap.c:next_uptodate_page
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios_contig
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:__filemap_get_folio
```
```
In mm/vmscan.c (ffffffff81379c00)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:should_skip_mm
  - mm/vmscan.c:isolate_lru_folios
```
```
In mm/compaction.c (ffffffff813a7685)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff813af483)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/rmap.c (ffffffff813dad6e)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/rmap.c:folio_lock_anon_vma_read
  - mm/rmap.c:folio_get_anon_vma
```
```
In mm/memory_hotplug.c (ffffffff813f1c87)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In mm/swapfile.c (ffffffff813ffb23)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81412ebf)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/hugetlb.c:get_hwpoison_huge_page
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/ksm.c (ffffffff8141e249)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81433435)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
```
```
In mm/migrate_device.c (ffffffff814387f2)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_range
```
```
In mm/huge_memory.c (ffffffff81442961)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/memcontrol.c (ffffffff81453286)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81463e8b)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
```
In mm/page_idle.c (ffffffff8146e0ba)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff8147e7b4)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff814ed1ab)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
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
In fs/mbcache.c (ffffffff81514f8f)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
```
```
In fs/proc/task_mmu.c (ffffffff8152cbc6)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/inode.c (ffffffff815313dd)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff81532c1a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/kernfs/dir.c (ffffffff8154b59f)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_id
```
```
In fs/ext4/balloc.c (ffffffff8155807f)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
  - fs/ext4/balloc.c:ext4_validate_block_bitmap
```
```
In fs/ext4/ialloc.c (ffffffff81570658)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
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
In fs/ext4/mballoc.c (ffffffff81596c1c)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_mb_mark_bb
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_discard_work
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
```
In fs/ext4/super.c (ffffffff815c9084)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:ext4_check_descriptors
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In fs/fuse/file.c (ffffffff81622efe)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8174a76d)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_find_and_get_req
```
```
In io_uring/timeout.c (ffffffff81798f21)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
```
```
In drivers/phy/phy-core.c (ffffffff818a6e54)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff818e7609)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e90a5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In drivers/clk/clk.c (ffffffff819f7153)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81a1f6c3)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a6fc45)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a75593)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
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
In drivers/tty/serdev/core.c (ffffffff81a903d0)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/iommu-sva.c (ffffffff81adbe81)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
  - drivers/iommu/iommu-sva.c:__mmget_not_zero
```
```
In drivers/base/core.c (ffffffff81ae5015)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff81b01962)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
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
In drivers/scsi/hosts.c (ffffffff81b76f04)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81bd7b24)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81bd942c)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In drivers/net/loopback.c (ffffffff81bdacaa)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/cdrom/cdrom.c (ffffffff81c0c335)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c19967)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81c1d349)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81c26f5c)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c38404)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81c7ed55)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf069)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf57a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d34c73)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff81d58985)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81d5a0fe)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/firmware/efi/efi.c (ffffffff820c4997)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_persistent
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d7533a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81d98b5a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff81da377a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_queue_err_skb
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff81dcaa6a)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
```
```
In net/core/neighbour.c (ffffffff81ddaa50)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff81df3d3d)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff81e29e3e)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
  - net/core/dst_cache.c:dst_cache_per_cpu_get
```
```
In net/sched/sch_frag.c (ffffffff81e53dae)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_frag_xmit
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b6c9)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/route.c (ffffffff81e901b7)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff81e97ebf)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff81e9a381)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1823)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece9e7)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3ef2)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed98a2)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff81ee4c38)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81ee8f3b)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81eeb70d)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1e45e)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f374ca)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81f4270d)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f444ae)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/ip6_output.c (ffffffff81f57e23)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_append_data
  - net/ipv6/ip6_output.c:ip6_sk_dst_lookup_flow
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bbca)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f6ed24)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99f0f)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81fa53aa)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff81fac76c)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb44ce)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd1f5)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In lib/dec_and_lock.c (ffffffff8201fc50)
Location: include/linux/atomic/atomic-arch-fallback.h:1240
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
