# Function: <code>__arch_atomic_add_unless</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006b33)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_add_exclusive
```
```
In arch/x86/kernel/process.c (ffffffff81039bd7)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:get_wchan
```
```
In arch/x86/kernel/stacktrace.c (ffffffff8103fed1)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk
```
```
In kernel/cred.c (ffffffff810b5a25)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
```
```
In kernel/sched/core.c (ffffffff810bac95)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810cd6c9)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/locking/mutex.c (ffffffff810e47d5)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
```
```
In kernel/power/hibernate.c (ffffffff810ea831)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
```
```
In kernel/power/user.c (ffffffff810f0667)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - kernel/power/user.c:snapshot_open
```
```
In kernel/irq/chip.c (ffffffff810fad0f)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In kernel/futex.c (ffffffff8112a945)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff8112ea70)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - kernel/module.c:try_module_get
  - kernel/module.c:try_release_module_ref
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81162795)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi
```
```
In kernel/bpf/syscall.c (ffffffff811b5554)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_inc_not_zero
```
```
In kernel/events/core.c (ffffffff811de8e7)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:ring_buffer_get
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_lock_task_context
```
```
In kernel/events/ring_buffer.c (ffffffff811e2e6f)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/events/uprobes.c (ffffffff811e5179)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/filemap.c (ffffffff811ecea8)
Location: arch/x86/include/asm/atomic.h:265
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
In mm/swap.c (ffffffff81202c2f)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/swap.c:deactivate_file_page
```
```
In mm/vmscan.c (ffffffff81208523)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/vmscan.c:__isolate_lru_page
```
```
In mm/gup.c (ffffffff81226b68)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
```
```
In mm/rmap.c (ffffffff8123ff14)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
```
```
In mm/swapfile.c (ffffffff8124c5fa)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8125857f)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/ksm.c (ffffffff8125f3f9)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff819e668b)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff81270a71)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffffffff81278eb2)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
```
In mm/memcontrol.c (ffffffff8127e749)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81288236)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
```
```
In mm/page_idle.c (ffffffff81290edf)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In fs/super.c (ffffffff8129c9e6)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/super.c:grab_super
```
```
In fs/userfaultfd.c (ffffffff812f010b)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_release
```
```
In fs/proc/task_mmu.c (ffffffff813180a9)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/task_mmu.c:m_start
```
```
In fs/proc/base.c (ffffffff8131d983)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/proc/base.c:environ_read
```
```
In fs/proc/array.c (ffffffff81321f8d)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In fs/proc/proc_sysctl.c (ffffffff81326534)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/kernfs/mount.c (ffffffff8132b043)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_pin_sb
```
```
In fs/kernfs/dir.c (ffffffff8132cf70)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/ext4/balloc.c (ffffffff813368d7)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
```
```
In fs/ext4/ialloc.c (ffffffff813490a5)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:ext4_init_inode_table
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
```
```
In fs/ext4/mballoc.c (ffffffff81365e17)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_group_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_new_inode_pa
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
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
In fs/ext4/super.c (ffffffff81386fc1)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
```
In lib/syscall.c (ffffffff814f0320)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - lib/syscall.c:collect_syscall
```
```
In drivers/phy/phy-core.c (ffffffff814f9d85)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8152167e)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d7185)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_notify_nmi
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d2e5)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff8163131f)
Location: arch/x86/include/asm/atomic.h:265
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
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/iommu/intel-svm.c (ffffffff8167599d)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/base/core.c (ffffffff8167f13d)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81690206)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:pm_runtime_get_if_in_use
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/scsi/hosts.c (ffffffff816e9f78)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff817335fc)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/net/loopback.c (ffffffff817345c7)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/net/loopback.c:loopback_xmit
```
```
In drivers/usb/core/hcd.c (ffffffff81758ff1)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8176105f)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8176e2ee)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817b7da3)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817db302)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db58e)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81825f6d)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler
```
```
In drivers/mmc/core/sdio.c (ffffffff8183cf6a)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8183ed65)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185b533)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/core/sock.c (ffffffff81874930)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/core/sock.c:sk_dst_check
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skbuff.c (ffffffff8187bd8e)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/core/skbuff.c:__copy_skb_header
```
```
In net/core/dev.c (ffffffff8189429c)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:dev_loopback_xmit
  - net/core/dev.c:dev_fill_metadata_dst
```
```
In net/core/neighbour.c (ffffffff818a12cb)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/core/neighbour.c:__neigh_event_send
```
```
In net/core/filter.c (ffffffff818b30ae)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_set_tunnel_key
```
```
In net/core/dst_cache.c (ffffffff818c85fd)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/core/dst_cache.c:dst_cache_set_ip6
  - net/core/dst_cache.c:dst_cache_set_ip4
```
```
In net/netfilter/nf_queue.c (ffffffff818e14e3)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue
```
```
In net/ipv4/route.c (ffffffff818e61b0)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_options.c (ffffffff818eab5c)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/ip_output.c (ffffffff818ebd68)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef66d)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191023a)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912e84)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916a21)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check
```
```
In net/ipv4/udp.c (ffffffff8191c012)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/arp.c (ffffffff81921b78)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81923ea2)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff819402d7)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_cache_report
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194fa36)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffffffff81955f7f)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819566ac)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/ip6_output.c (ffffffff81963acd)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/addrconf.c (ffffffff8196545b)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819783b2)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_link_failure
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_create_rt_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81991600)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81999bbe)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_lookup
```
```
In net/ipv6/ip6mr.c (ffffffff8199d5e2)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_cache_report
```
```
In net/ipv6/fib6_rules.c (ffffffff819a3a2a)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
```
In net/ipv6/seg6_local.c (ffffffff819a8a5e)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
```
In lib/dec_and_lock.c (ffffffff819ce1b0)
Location: arch/x86/include/asm/atomic.h:265
Inline: True
```
</details>
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
