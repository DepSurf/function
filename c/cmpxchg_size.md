# Function: <code>cmpxchg_size</code>

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
In arch/x86/events/amd/core.c (ffffffff8100857a)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_put_event_constraints
  - arch/x86/events/amd/core.c:amd_get_event_constraints
  - arch/x86/events/amd/core.c:amd_get_event_constraints
```
```
In arch/x86/events/amd/uncore.c (ffffffff810094bd)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_del
  - arch/x86/events/amd/uncore.c:amd_uncore_add
```
```
In arch/x86/xen/p2m.c (ffffffff8101ecc3)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff810527fb)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_ioctl
```
```
In arch/x86/kernel/acpi/boot.c (ffffffff81058a32)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:__acpi_release_global_lock
  - arch/x86/kernel/acpi/boot.c:__acpi_acquire_global_lock
```
```
In arch/x86/mm/pat.c (ffffffff8107b645)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_memtype
```
```
In kernel/exit.c (ffffffff810924b3)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/task_work.c (ffffffff810b1118)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/task_work.c:task_work_run
  - kernel/task_work.c:task_work_cancel
  - kernel/task_work.c:task_work_add
```
```
In kernel/sched/core.c (ffffffff810bfae0)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:wake_up_if_idle
  - kernel/sched/core.c:wake_up_nohz_cpu
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/sched/clock.c (ffffffff810c3520)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_local
```
```
In kernel/sched/fair.c (ffffffff810c67a5)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/locking/osq_lock.c (ffffffff810e4e9b)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/locking/qspinlock.c (ffffffff810e50f9)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (ffffffff819ef62b)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_unlock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_lock_interruptible
  - kernel/locking/rtmutex.c:rt_mutex_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowunlock
```
```
In kernel/acct.c (ffffffff81135f1e)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/debug/kdb/kdb_io.c (ffffffff81161263)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
```
In kernel/trace/ring_buffer.c (ffffffff81177f55)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/tracing_map.c (ffffffff81189eca)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/trace/trace_functions.c (ffffffff8118b5a5)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
```
```
In kernel/trace/blktrace.c (ffffffff81191456)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/irq_work.c (ffffffff811b00fc)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_queue_on
```
```
In kernel/bpf/devmap.c (ffffffff811c99ec)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
```
```
In mm/oom_kill.c (ffffffff811f1fbf)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/page_alloc.c (ffffffff811f614b)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/mmzone.c (ffffffff81214f76)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - mm/mmzone.c:page_cpupid_xchg_last
```
```
In mm/frontswap.c (ffffffff8124f348)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - mm/frontswap.c:frontswap_register_ops
```
```
In mm/huge_memory.c (ffffffff81273f8a)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
```
```
In mm/memcontrol.c (ffffffff8127e994)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/cleancache.c (ffffffff8128b0c5)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - mm/cleancache.c:cleancache_register_ops
```
```
In fs/exec.c (ffffffff812a348c)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
```
```
In fs/dcache.c (ffffffff812b5a04)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
```
```
In fs/inode.c (ffffffff812b8191)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - fs/inode.c:inode_set_flags
```
```
In fs/libfs.c (ffffffff812c6fb1)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - fs/libfs.c:move_cursor
```
```
In fs/fs-writeback.c (ffffffff812cc950)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (ffffffff812d71ac)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - fs/buffer.c:block_invalidatepage
```
```
In fs/direct-io.c (ffffffff812df644)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - fs/direct-io.c:sb_init_dio_done_wq
```
```
In fs/notify/mark.c (ffffffff812e5bef)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In fs/crypto/keyinfo.c (ffffffff812fbd71)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
```
```
In fs/locks.c (ffffffff812fd79d)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - fs/locks.c:locks_get_lock_context
```
```
In fs/posix_acl.c (ffffffff8130b1a9)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
```
```
In fs/iomap.c (ffffffff8130fa4f)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_bio_end_io
```
```
In fs/ext4/inode.c (ffffffff8134f479)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_update_bh_state
```
```
In fs/debugfs/file.c (ffffffff813d1991)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In block/blk-mq.c (ffffffff8148ddfc)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
```
In lib/lockref.c (ffffffff814c1a9d)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/llist.c (ffffffff814ca61f)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - lib/llist.c:llist_del_first
  - lib/llist.c:llist_add_batch
```
```
In lib/errseq.c (ffffffff814cdc0f)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - lib/errseq.c:errseq_check_and_advance
  - lib/errseq.c:errseq_set
```
```
In lib/genalloc.c (ffffffff814d53f8)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:gen_pool_alloc_algo
  - lib/genalloc.c:bitmap_clear_ll
  - lib/genalloc.c:bitmap_clear_ll
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d69b5)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_cache_add
```
```
In drivers/xen/mcelog.c (ffffffff81603a4b)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_ioctl
```
```
In drivers/tty/tty_audit.c (ffffffff8161cdf6)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
```
In drivers/char/random.c (ffffffff81648553)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/iommu/amd_iommu.c (ffffffff81668246)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/iommu/intel-iommu.c (ffffffff81671af9)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel-svm.c (ffffffff816761e8)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816ed53a)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/md/md.c (ffffffff817f3751)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_do_sync
```
```
In drivers/md/dm.c (ffffffff8180a92b)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_create
```
```
In net/core/sock.c (ffffffff8187853a)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/core/dev.c (ffffffff818955b5)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_schedule_prep
```
```
In net/core/dst.c (ffffffff8189f4d4)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/core/dst.c:__dst_destroy_metrics_generic
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/filter.c (ffffffff818b25d3)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_skb_set_tunnel_proto
```
```
In net/core/netpoll.c (ffffffff818bf582)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_poll_dev
```
```
In net/core/lwtunnel.c (ffffffff818c7724)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_encap_del_ops
  - net/core/lwtunnel.c:lwtunnel_encap_add_ops
```
```
In net/ipv4/route.c (ffffffff818e2da0)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cache_route
  - net/ipv4/route.c:ip_idents_reserve
```
```
In net/ipv4/protocol.c (ffffffff818e7d4a)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/ipv4/protocol.c:inet_del_offload
  - net/ipv4/protocol.c:inet_del_protocol
  - net/ipv4/protocol.c:inet_add_offload
  - net/ipv4/protocol.c:inet_add_protocol
```
```
In net/ipv4/tcp.c (ffffffff818f6878)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819070ae)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_output.c:tcp_release_cb
```
```
In net/ipv6/route.c (ffffffff8197670d)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/ip6_icmp.c (ffffffff819aae85)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender
  - net/ipv6/ip6_icmp.c:inet6_register_icmp_sender
```
```
In net/ipv6/protocol.c (ffffffff819ab51a)
Location: include/asm-generic/atomic-instrumented.h:353
Inline: True
Inline callers:
  - net/ipv6/protocol.c:inet6_del_offload
  - net/ipv6/protocol.c:inet6_add_offload
  - net/ipv6/protocol.c:inet6_del_protocol
  - net/ipv6/protocol.c:inet6_add_protocol
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
