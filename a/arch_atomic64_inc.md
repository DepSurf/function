# Function: <code>arch_atomic64_inc</code>

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
In kernel/fork.c (ffffffff8108bf25)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
```
```
In kernel/sys.c (ffffffff810a4036)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8110e9f0)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/audit_tree.c (ffffffff8115aa87)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff8118a25a)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff811b390f)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/events/uprobes.c (ffffffff811e4d45)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/oom_kill.c (ffffffff811f3cb7)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/vmscan.c (ffffffff8120b3cb)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff8120fa2d)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/workingset.c (ffffffff81225b33)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff81225bd3)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff812387f0)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8123c014)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8123f3e5)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81245155)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
```
In mm/swapfile.c (ffffffff8124a425)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81268349)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8127124e)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8127d3ef)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff81286601)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff8128a71b)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff81290002)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812b168f)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812b8e2f)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
```
```
In fs/file.c (ffffffff812bcc8f)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff812ebd1b)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/fd.c (ffffffff81323305)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff813c3b81)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813df565)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff81450f8c)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8145356f)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff81489031)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
```
```
In block/cfq-iosched.c (ffffffff814b314c)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
```
```
In drivers/tty/tty_io.c (ffffffff81611c73)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff81663dd5)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff816ac0e4)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e28ec)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81805275)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff81885b8d)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818920b3)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b4093)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff818c8997)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff818ca8cd)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81924d86)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81957f47)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81959b35)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8195d305)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81963c65)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff8197f79a)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81985e42)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff8198aa1c)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff8198c27d)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199484a)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81995adc)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819ae1c3)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In kernel/fork.c (ffffffff810937e5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In kernel/sys.c (ffffffff810ace06)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81119f70)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/audit_tree.c (ffffffff8116781a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff81197bbf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff811c45ae)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff811f53b0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81204949)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8121e0b3)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81222801)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/workingset.c (ffffffff812391f3)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81239293)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff8124c1b0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81250434)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff81253af6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828be1fa)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8125979b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
```
In mm/swapfile.c (ffffffff8125ea66)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff8127de55)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff812856af)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff81291ffa)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8129b56e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff8129f444)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff812a5036)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812c68df)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812cdf6f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff812d1f4f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff812f9e00)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff812fff6c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/fd.c (ffffffff8133a5d5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff813dd331)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813f9be3)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff8146df6c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8147074f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff81478196)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-ioc.c (ffffffff814a2f61)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162e9e8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816823c5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff816cdbba)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81705d9c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81831475)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818a62bd)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818b5f14)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818dc850)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff818f38a1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff818f599d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81953b8c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff8198d038)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff8198e6b5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81991e45)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81998c00)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff819b5d8b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bc433)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c12dc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c2d25)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb2da)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff819cc3e8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819e4b53)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In kernel/fork.c (ffffffff81099ba2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b263c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81124bf0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff81174462)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811a51af)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d60f3)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff8120d077)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81213ca5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121c0c0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8122d746)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81231e08)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/workingset.c (ffffffff8124a243)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff8124a2f3)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff8125e60d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8126275c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff81265d5b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828d73cd)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff81274f67)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff8127afa7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81299ca8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8129ff1f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812aca23)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812b6753)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812ba731)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/zsmalloc.c (ffffffff812bebed)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812c06f9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812e33ac)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812eadaf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff812eef90)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff8131a4d7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff81320fad)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8133208d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81362792)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff81408e70)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff814261e7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149b63c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8149e120)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814a6067)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-ioc.c (ffffffff814d1011)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8166260b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816b9b05)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff81708d76)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81740bad)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81874019)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818f174d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81901ec6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81929996)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81952747)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8195504a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff819b8486)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff819f88a2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff819f9e05)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819fd685)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a04a56)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a2486b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a2af5f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a300a7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a31b2f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39d14)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a3aedc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a53c30)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In kernel/fork.c (ffffffff8109ff96)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b8d0c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81130bb0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff811802d2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811b09df)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e2099)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff8121a3e5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812257f9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81229a52)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8123b928)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff8123fec8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff81258693)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81258733)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8125c5ea)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126ce1d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81270f0c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff81274688)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828df83e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff81283e73)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff8128aa87)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812a9b68)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b12bf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812be2dd)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812c8623)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812cc611)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812d0b4d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812d2646)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812f4e3c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812fc8df)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff81300a50)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff8132d2f7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff81333d4d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff81345c4d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff8137a9f2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8143ff37)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814b587c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814b859f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814c09b7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-ioc.c (ffffffff814ea3d1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In block/blk-iocost.c (ffffffff81512e2a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff81684c7b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816dc8f5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff8172d056)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81764e7f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff818a5e29)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8192369d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81934106)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8195bfff)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81988a97)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8198b4ea)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff819ef186)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f502)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a30a85)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a34275)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b647)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a5b2eb)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a61abf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a66bf7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a6867f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a708a4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a71b5c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a8a820)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In kernel/fork.c (ffffffff810a7022)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810c074c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8113fc3a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/audit_tree.c (ffffffff81193ae2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811c8f96)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff811fc77f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In mm/filemap.c (ffffffff812534a2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/oom_kill.c (ffffffff812568a5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff812689f1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8127114b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (ffffffff81286f43)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8128bb32)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8129cbc7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812a15c9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff82cfcdfa)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff812b59e6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
  - mm/madvise.c:madvise_willneed
```
```
In mm/swapfile.c (ffffffff812bd7bf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812d9f13)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812e6755)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff812f3bb9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812fdf0a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
```
```
In mm/hugetlb_cgroup.c (ffffffff812ff8f2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8130296b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff8130751b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff8132d48c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff8133517f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff81339c90)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813670a7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8136eeda)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff81380519)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813c3a90)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81490cb7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff81514f1c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81518145)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff815211db)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-ioc.c (ffffffff81549371)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In block/blk-iocost.c (ffffffff815742f6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff81735e10)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tioccons
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff817934d5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff817e98a1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81824b0f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81975d81)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819f71f2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_install_fd
```
```
In net/core/dev.c (ffffffff81a08af7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a30f77)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81a60709)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff81a631d7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81add0d8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81b22115)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81b24cb5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b29085)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b30c13)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81b53f17)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b5a97b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b5f627)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b6199f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b694c8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81b6b44f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81b863be)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In kernel/fork.c (ffffffff810a2b55)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810bcde0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d0b2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/audit_tree.c (ffffffff81190c52)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811c6656)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff81200c91)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In mm/filemap.c (ffffffff8125e0ab)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/oom_kill.c (ffffffff8126143b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81273462)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8127a62f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff8127d365)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff81291263)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81296aee)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812a7f57)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812ace04)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff82fe987d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff812c0ea0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
```
```
In mm/slub.c (ffffffff812e5245)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/khugepaged.c (ffffffff812ff346)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff8130a3ac)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
```
```
In mm/hugetlb_cgroup.c (ffffffff8130bc3c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8130e728)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff8131325b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff81338c2c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81340aef)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff813459d9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff82fee175)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff813743f7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8137b26f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8138a963)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_add_task_file
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813d5c1e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff814ae404)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff81531f8c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81535115)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff8153e22b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-ioc.c (ffffffff81565191)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In block/blk-iocost.c (ffffffff815913ac)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff81752942)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tioccons
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff817bfe25)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff817fe321)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/net/tun.c (ffffffff8189c4fb)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/md/md-bitmap.c (ffffffff8197ad71)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819f6c62)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/core/dev.c (ffffffff81a0a22c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a33407)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81a68f99)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (ffffffff81ae9e2b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30b0e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81b33845)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b379b5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f83e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81b62516)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b69110)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b6ddc7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b7012c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b77ef4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81b79edd)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81b95ce8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In kernel/fork.c (ffffffff810a385f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810be675)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d181)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/audit_tree.c (ffffffff81191bb2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811c76b0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff812016e1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
```
```
In mm/filemap.c (ffffffff81260d6d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81265c77)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81278782)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8127f76f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff812824f5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff8129c68a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812ac040)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812b20ed)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff831f3f26)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff812c8120)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In mm/slub.c (ffffffff812ece15)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/khugepaged.c (ffffffff81305fc3)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff81310c45)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
```
```
In mm/hugetlb_cgroup.c (ffffffff8131223c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81314c04)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff81318e7b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff8133f2bc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81346f6f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff8134bd99)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:__receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff831f89b2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff8137ada7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8138302c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8139bc64)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813dcc2e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff81422bc0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In ipc/shm.c (ffffffff814b4231)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff81539004)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8153a35c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8153d735)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff815469e6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-ioc.c (ffffffff8156d801)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In block/blk-iocost.c (ffffffff815980ec)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff81736d26)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff817a3045)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/net/tun.c (ffffffff8187ea5f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/md/md-bitmap.c (ffffffff8195efa1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819dcdd5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/core/dev.c (ffffffff819ee6c0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a1a1ae)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81a4c359)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (ffffffff81ad5581)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e842)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81b21255)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b25655)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d6df)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81b50808)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b57280)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b5c14a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81b5e38e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b669ff)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81b68a0e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81b84bba)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073706)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810b4eab)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d554)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/audit_tree.c (ffffffff811baa72)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811f2dfd)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff81233446)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_mmap_open
```
```
In mm/filemap.c (ffffffff8129d7d0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff812a24a4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff812b64dc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff812bda26)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff812c0605)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff812d6fe3)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812dd302)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812ef2fb)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812f3ce4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff832da26c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8130d104)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In mm/slub.c (ffffffff81335025)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff8133c959)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/khugepaged.c (ffffffff8134fe31)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff8135bf09)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
```
```
In mm/hugetlb_cgroup.c (ffffffff8135db6a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81360c84)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff81365488)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff8138cc4c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff813949cf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff81399bd9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff832df92a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff813c7fac)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/io_uring.c (ffffffff813e7379)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff8142e30e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff8147635d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In ipc/shm.c (ffffffff8150c8cb)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff81597844)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff81598cdc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8159c5b5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff815a6f96)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-ioc.c (ffffffff815d21d7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
```
```
In block/blk-iocost.c (ffffffff815ff7fa)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff817b76ff)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff8182c385)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff8186e03e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/net/tun.c (ffffffff8191024a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/md/md-bitmap.c (ffffffff81a048e1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81a8d015)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/core/dev.c (ffffffff81a9f95d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81acc447)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81b04809)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (ffffffff81b94387)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81be3364)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81be6315)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81bead65)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81bf38be)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81c17bb0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81c1e85a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81c238b1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81c25868)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e5ac)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81c306d8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81c5105c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810814e6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810c954a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81160946)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff811da1a9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff811eddd2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff8122c3b4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff812713a5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_mmap_open
```
```
In mm/filemap.c (ffffffff812f4886)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff812fa40c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8131197e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff81319799)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff8131d0c5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff81336843)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8133cfec)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff81352729)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81357b11)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff8348f2fc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/madvise.c (ffffffff813786e6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/slub.c (ffffffff813ad46c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff813afd79)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/khugepaged.c (ffffffff813c804a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff813d5802)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
```
```
In mm/hugetlb_cgroup.c (ffffffff813d7c0b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff813d8b3e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff8140df2c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81416baf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff8141c689)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff83495644)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff8144efd8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/coredump.c (ffffffff81484a32)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff814a7a37)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff814f856b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In ipc/shm.c (ffffffff8159e87a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff81639348)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8163d6fe)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff816415f4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff8164e0f6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-ioc.c (ffffffff8167dd85)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-iocost.c (ffffffff816b1790)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In io_uring/io_uring.c (ffffffff816d3cc2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff818f2cfa)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/dma-iommu.c (ffffffff81969f75)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819edad8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/net/tun.c (ffffffff81a63f18)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/vfio/vfio.c (ffffffff81a76e56)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_open
```
```
In drivers/md/md-bitmap.c (ffffffff81b6c580)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81c02905)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81c95827)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/icmp.c (ffffffff81d25c46)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/unix/af_unix.c (ffffffff81d7ed65)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81d83015)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c495)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81db3998)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81dbb0aa)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81dc07e2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81dc3058)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcbe4a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81dcde16)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81df2508)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093db6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810e6aa6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81193e86)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff8121f729)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff81234402)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff81277ee4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff812c7221)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_mmap_open
```
```
In kernel/events/ring_buffer.c (ffffffff8134b443)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/filemap.c (ffffffff8135e9c6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/oom_kill.c (ffffffff81364b7c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81384fa9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8138d74b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff813909f5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff813adaad)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff813b4bc6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff813cc735)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff813d22b7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff83ec17cf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/madvise.c (ffffffff813f5ef8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/slub.c (ffffffff81427c43)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/kfence/core.c (ffffffff81430379)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In mm/khugepaged.c (ffffffff8144cb18)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In mm/memcontrol.c (ffffffff8145b29d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
```
```
In mm/hugetlb_cgroup.c (ffffffff8145da71)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81463e65)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff81498a5c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff814a203f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff814a8799)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff83eca138)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff814dd7c6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/coredump.c (ffffffff81517f28)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff8153d437)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff81592c18)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In ipc/shm.c (ffffffff81647f3a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff816f09a8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff816f522e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff816f95e4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff81707576)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
```
```
In block/blk-ioc.c (ffffffff8173a9d5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-iocost.c (ffffffff8176fd13)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In io_uring/msg_ring.c (ffffffff81798c7d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
```
```
In io_uring/rsrc.c (ffffffff817a1591)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/tty/tty_io.c (ffffffff81a4b32d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad3fd5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
```
```
In drivers/base/memory.c (ffffffff81b1705d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_inc
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b6ae15)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/net/tun.c (ffffffff81bf3100)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/md-bitmap.c (ffffffff81d08654)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81db1da5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81e51387)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/icmp.c (ffffffff81eed59f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/ipmr.c (ffffffff81f1ec34)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff81f4c0f5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81f50675)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a455)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81f83338)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81f8b17f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81f90f6d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81f93a63)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9cf5b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81f9f02e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffffffff81faca6e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff81fc6618)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In arch/x86/kernel/nmi.c (ffffffff8213de6a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096d46)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810f2460)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a56e6)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff8123589b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff8124b0f2)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff8128f924)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff812ee7a8)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_mmap_open
```
```
In kernel/events/ring_buffer.c (ffffffff8137c493)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/filemap.c (ffffffff8139175e)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/oom_kill.c (ffffffff8139703c)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff813b6b09)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
```
```
In mm/shmem.c (ffffffff813c0106)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff813c32f5)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff813e9bc9)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff813fea85)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
```
```
In mm/msync.c (ffffffff81406e7c)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff836e6fdf)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/madvise.c (ffffffff81428dbc)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/zswap.c (ffffffff81436818)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/slub.c (ffffffff8145d1bb)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/kfence/core.c (ffffffff81465cf2)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
```
```
In mm/khugepaged.c (ffffffff814823c6)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In mm/memcontrol.c (ffffffff81490f0d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
```
```
In mm/hugetlb_cgroup.c (ffffffff81493761)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8149997c)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff814cdafc)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff814d71cf)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In fs/file.c (ffffffff814dd789)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff836ef178)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff81514026)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/coredump.c (ffffffff8154f825)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff81575713)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff815c99f0)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_good_group_avg_frag_lists
```
```
In ipc/shm.c (ffffffff81680450)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/keys/dh.c (ffffffff816925c2)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/landlock/fs.c (ffffffff8172ae44)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8172f32e)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81733179)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In security/integrity/ima/ima_api.c (ffffffff81733757)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/aead.c (ffffffff81741ea2)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/geniv.c (ffffffff817421a9)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81742ff2)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/ahash.c (ffffffff8174514d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_op
```
```
In crypto/shash.c (ffffffff81746805)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
```
```
In crypto/akcipher.c (ffffffff8174784e)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/sig.c (ffffffff81747be1)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_sign
  - crypto/sig.c:crypto_sig_sign
```
```
In crypto/dh.c (ffffffff8174896e)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_set_secret
  - crypto/dh.c:dh_safe_prime_set_secret
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a801)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/gcm.c (ffffffff817530dd)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In crypto/rng.c (ffffffff81758463)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff817593c2)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
```
```
In block/blk-ioc.c (ffffffff817770d5)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-iocost.c (ffffffff817b0039)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In io_uring/msg_ring.c (ffffffff817d998e)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/rsrc.c (ffffffff817e2799)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In lib/iov_iter.c (ffffffff81811c77)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/tty/tty_io.c (ffffffff81a953cd)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b227a5)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
```
```
In drivers/base/memory.c (ffffffff81b65dcd)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_inc
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbe232)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/net/tun.c (ffffffff81c4a372)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/md-bitmap.c (ffffffff81d717e4)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81e22348)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81eacbd3)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/tcp.c (ffffffff81f0aebc)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c162)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv4/icmp.c (ffffffff81f4cf5f)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/ipmr.c (ffffffff81f7e734)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff81fabed5)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81faffe5)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81fba140)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81fe364b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81feb846)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81ff185d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff81ff43cb)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd9ec)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81fffb7b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffffffff8200d47e)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff820272dd)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
```
In net/handshake/netlink.c (ffffffff82092685)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_accept_doit
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
In arch/x86/kernel/nmi.c (ffffffff8221fe6a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e2b6)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810fc030)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b51d6)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff8124f4e8)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff81264ff2)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff812aae84)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff8130ce25)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:bpf_map_do_batch
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
  - kernel/bpf/syscall.c:__bpf_prog_get
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
  - kernel/bpf/syscall.c:bpf_map_get
  - kernel/bpf/syscall.c:bpf_map_mmap
  - kernel/bpf/syscall.c:bpf_map_mmap_open
```
```
In kernel/bpf/verifier.c (ffffffff813230af)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/tcx.c (ffffffff8137b7b0)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/bpf/tcx.c:tcx_link_update
  - kernel/bpf/tcx.c:tcx_link_release
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_prog_detach
  - kernel/bpf/tcx.c:tcx_prog_attach
```
```
In kernel/events/ring_buffer.c (ffffffff813a57ae)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/filemap.c (ffffffff813bb4cc)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
  - mm/filemap.c:do_sync_mmap_readahead
```
```
In mm/oom_kill.c (ffffffff813c0db0)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff813df9c9)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
```
```
In mm/shmem.c (ffffffff813e7740)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/shmem.c:shmem_falloc_wait
```
```
In mm/util.c (ffffffff813ede15)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff81414d37)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8142af23)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
```
```
In mm/msync.c (ffffffff8143352c)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff8391958f)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/slub.c (ffffffff814578bb)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/madvise.c (ffffffff814625ec)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/zswap.c (ffffffff81470b4b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
  - mm/zswap.c:__zswap_load
  - mm/zswap.c:shrink_memcg_cb
  - mm/zswap.c:zswap_folio_swapin
```
```
In mm/kfence/core.c (ffffffff81494f70)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:kfence_guarded_alloc
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
```
```
In mm/khugepaged.c (ffffffff814b176c)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In mm/memcontrol.c (ffffffff814c087a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:reclaim_high
  - mm/memcontrol.c:reclaim_high
```
```
In mm/hugetlb_cgroup.c (ffffffff814c30d3)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff814c911d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff8150043c)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff8150954f)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In fs/file.c (ffffffff815101d9)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff839221c8)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff815484f6)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/backing-file.c (ffffffff81581864)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In fs/coredump.c (ffffffff81585664)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff815ae070)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff81602985)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_good_group_avg_frag_lists
  - fs/ext4/mballoc.c:ext4_mb_choose_next_group_p2_aligned
```
```
In ipc/shm.c (ffffffff816bc840)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/keys/dh.c (ffffffff816ceb92)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/landlock/fs.c (ffffffff8176c964)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8176fcbc)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81774177)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/aead.c (ffffffff81782d82)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/geniv.c (ffffffff81783089)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/lskcipher.c (ffffffff81783d9a)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/lskcipher.c:crypto_lskcipher_decrypt
  - crypto/lskcipher.c:crypto_lskcipher_encrypt
  - crypto/lskcipher.c:crypto_lskcipher_crypt
```
```
In crypto/skcipher.c (ffffffff81785342)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/ahash.c (ffffffff81787e76)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_digest
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_finup
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:crypto_ahash_update
```
```
In crypto/shash.c (ffffffff817889b1)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
```
```
In crypto/akcipher.c (ffffffff817896be)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/sig.c (ffffffff81789a51)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_sign
  - crypto/sig.c:crypto_sig_sign
```
```
In crypto/dh.c (ffffffff8178a8be)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_compute_shared_secret
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_generate_public_key
  - crypto/dh.c:dh_safe_prime_set_secret
  - crypto/dh.c:dh_safe_prime_set_secret
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c3c1)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/rng.c (ffffffff8179a363)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff8179b2c2)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
```
```
In block/blk-ioc.c (ffffffff817b9305)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In block/blk-iocost.c (ffffffff817f3e49)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In io_uring/msg_ring.c (ffffffff8181dcae)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In drivers/tty/tty_io.c (ffffffff81ae7dab)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79325)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
```
```
In drivers/base/memory.c (ffffffff81bb9c4d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_inc
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c12982)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81cacccb)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_handle_to_fd
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_fd_to_handle
  - drivers/gpu/drm/drm_prime.c:drm_prime_add_buf_handle
```
```
In drivers/net/netkit.c (ffffffff81ce658f)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_link_attach
  - drivers/net/netkit.c:netkit_link_update
  - drivers/net/netkit.c:netkit_link_release
  - drivers/net/netkit.c:netkit_prog_detach
  - drivers/net/netkit.c:netkit_prog_attach
```
```
In drivers/net/tun.c (ffffffff81cffcf5)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d06fd7)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:mergeable_buf_free
  - drivers/net/virtio_net.c:receive_small
```
```
In drivers/md/md-bitmap.c (ffffffff81e288c3)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/skbuff.c (ffffffff81ed2ee4)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
```
```
In net/core/scm.c (ffffffff81ee0288)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81f6f690)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff510d)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8201306f)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034313)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff82044ddf)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/ipv4/tcp_ao.c (ffffffff820585e5)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_ao_ignore_icmp
```
```
In net/unix/af_unix.c (ffffffff820792f5)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8207d645)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff820875a1)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff820b1555)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff820b9511)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff820bf45c)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_xrlim_allow
```
```
In net/ipv6/mcast.c (ffffffff820c12f7)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc86b)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff820ce971)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffffffff820dc448)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff820f67a1)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mmap
  - net/packet/af_packet.c:packet_mm_open
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
```
In net/handshake/netlink.c (ffffffff82168f97)
Location: arch/x86/include/asm/atomic64_64.h:43
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_nl_accept_doit
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810998b6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b307c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81129360)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff811788f2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811a8fff)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811da6b9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff81212a35)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121de49)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff812220a2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81233f78)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81238518)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff81250ce3)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81250d83)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81254c3a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126546d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8126955c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8126ccd8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828c86f2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8127c4c3)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81283067)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812a2148)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a989f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b68bd)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812c0c03)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812c4bf1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812c912d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812cac26)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812ed41c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812f4ebf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff812f9030)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813258d7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8132c32d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8133e22d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81372fd2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81438517)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814ade5c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814b0b7f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814b8f97)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-ioc.c (ffffffff814e29b1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In block/blk-iocost.c (ffffffff8150b40a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff8164a6fb)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816a2345)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff816f2e36)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171956f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff8184bca9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818c369d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818d4106)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818fbfcf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81928907)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8192b35a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff8198ef26)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff819ceb92)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff819d0115)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819d3905)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff819dacd7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff819fa97b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a0114f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a06287)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a07d0f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ff34)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a111ec)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a29eb0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In kernel/fork.c (ffffffff810882fc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810a19ac)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8111bbf0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff8116ba92)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff8119bf7f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811cd479)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff812057af)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81210fff)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81215252)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81226fe8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff8122b519)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff81243c23)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81243cc3)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81247a7a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8125788d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8125b84c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8125ed14)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828c0e17)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8126e373)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81274ff4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81293c28)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8129b1ff)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812a7a8d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812b1c7b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812b5c31)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812ba16d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812bbbb0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812de04c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812e5adf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff812e9c50)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff81316477)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8131d691)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8132eeed)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81363aa2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81428f87)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149e87c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814a159f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814a99b7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-ioc.c (ffffffff814d3341)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In block/blk-iocost.c (ffffffff814fb86a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff8162ab4b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff8167fd35)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff816ccf36)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f29df)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/net/vxlan.c (ffffffff81772f72)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In drivers/md/md-bitmap.c (ffffffff818132c9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8187d5dd)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff8188df96)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b5dff)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff818e26b7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff818e510a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff819489e6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b956)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff8198ced5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819906c5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81997a97)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff819b773b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bdf0f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c3047)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff819c4acf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cccf4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff819cdfac)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819e70a0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In kernel/fork.c (ffffffff81099866)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b25dc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81127080)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff811766c2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811a6dcf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d8489)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff812107d5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121bbe9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff8121fe42)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81231d18)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff812362b8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff8124ea83)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff8124eb23)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812529da)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126320d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812672fc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8126aa78)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828db472)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8127a263)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81280e77)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff8129ff58)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a76af)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b46cd)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812bea13)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812c2a01)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812c6f3d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812c8a36)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812eb22c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812f2ccf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff812f6e40)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813233a7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff81329dfd)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8133bcfd)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81370aa2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff814346b7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814a9efc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814acc0f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814b5027)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-ioc.c (ffffffff814dea41)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In block/blk-iocost.c (ffffffff8150749a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff81678abb)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816d05b5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff81720516)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8175833f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff8189b2d9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8191469d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81925106)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8194cfff)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81979a97)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8197c4ea)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199ddc4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_kill_acct
  - net/netfilter/nf_conntrack_core.c:__nf_ct_refresh_acct
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/ipv4/icmp.c (ffffffff819f97c6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81a39612)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a3ab95)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a3e385)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a45757)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a653fb)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a6bbcf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a70d07)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7278f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a9b4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a7bc6c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a95a60)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In kernel/fork.c (ffffffff810a14cf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810babdc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff811336c8)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff81183f92)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811b4b6f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e6817)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff8121f6e6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8122ac47)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff8122ef27)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81241178)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81246593)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff8125e3fc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff8125e4a3)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812623aa)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff81272bcd)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81276c9c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8127a3e1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828e0893)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff81289e43)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81290b84)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812b0098)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b79b5)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812c507e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812cf483)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
```
In mm/memory-failure.c (ffffffff812d34a1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812d62ab)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812d972e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812fc21c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff813043df)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In fs/file.c (ffffffff813080b0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813350f7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8133c8c4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/io_uring.c (ffffffff8134eead)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81384482)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8144b7d9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814c294c)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814c565f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814cdaa7)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
```
```
In block/blk-ioc.c (ffffffff814f78b1)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
```
```
In block/blk-iocost.c (ffffffff8152095d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff816926f4)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816eab45)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff8173b8d6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8177381f)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff818b7439)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8193586d)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff819465e6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8196e9bf)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff8199bfb9)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8199ea3a)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81a03ab6)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81a45042)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a45e15)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a49e45)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a51427)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a7196e)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a781df)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a7d317)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/mcast.c (ffffffff81a7ee1b)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a871f2)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a884bc)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81aa26a0)
Location: arch/x86/include/asm/atomic64_64.h:86
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
</details>
</li>
</ul>

## Differences
