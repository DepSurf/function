# Function: <code>atomic64_inc</code>

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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In kernel/fork.c (ffffffff8107e3b4)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff81092b77)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/rcu/tree.c (ffffffff810e4f2a)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited
```
```
In kernel/audit_tree.c (ffffffff8112bbf8)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/events/core.c (ffffffff81184cc5)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_get
```
```
In kernel/events/uprobes.c (ffffffff8118781b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/workingset.c (ffffffff811b9f60)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff811b9ff7)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff811bd2b1)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc
  - mm/memory.c:__pmd_alloc
```
```
In mm/mmap.c (ffffffff811c71f6)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff811ca2fd)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/rmap.c (ffffffff811cb522)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811d1a02)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swapfile.c (ffffffff811d3dfc)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/hugetlb.c (ffffffff811de4ee)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/slub.c (ffffffff811e99ed)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:kmem_cache_open
```
```
In mm/migrate.c (ffffffff811f298d)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff811f4403)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memory-failure.c (ffffffff812030e2)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff81207afb)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff81220adb)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812277c9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In fs/file.c (ffffffff81229f71)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
  - fs/file.c:f_dupfd
```
```
In fs/eventpoll.c (ffffffff8125668a)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/proc/fd.c (ffffffff81281909)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff81311259)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff8132b215)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In security/integrity/ima/ima_queue.c (ffffffff813971d8)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff813987df)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/bio.c (ffffffff813b0f8b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-ioc.c (ffffffff813bee51)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In block/cfq-iosched.c (ffffffff813e34a1)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
```
```
In drivers/tty/tty_io.c (ffffffff814e1ca6)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff8156fc08)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a2b69)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff8169ee5f)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff8170ec97)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_fp_dup
```
```
In net/core/dev.c (ffffffff81717c53)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/compat.c (ffffffff8173f463)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff8178f064)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_out_count
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/unix/af_unix.c (ffffffff817bdf49)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff817c20d9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff817c81a5)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff817deb34)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff817e3f47)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff817e7ce9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmpv6_notify
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff817ea4e4)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f12b3)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff817f2885)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff818038a4)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In kernel/fork.c (ffffffff810800b4)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In kernel/sys.c (ffffffff81095cfb)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/rcu/tree.c (ffffffff810eb987)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81133de8)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811605f0)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/events/uprobes.c (ffffffff81199fec)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/workingset.c (ffffffff811d4370)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff811d4417)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff811da9ab)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mmap.c (ffffffff811e4241)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff811e67e1)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/rmap.c (ffffffff811e866d)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ef2aa)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swapfile.c (ffffffff811f2405)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff811fca44)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/slub.c (ffffffff8120d0bf)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8121243c)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff81214c90)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121c606)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81227da9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff8122d3e9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff8124872b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff8124ff59)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In fs/file.c (ffffffff812537a4)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff8127efaf)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/proc/fd.c (ffffffff812aea46)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff813456c4)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff8135feba)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In security/integrity/ima/ima_queue.c (ffffffff813d3232)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff813d4d9f)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/bio.c (ffffffff813f497b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-ioc.c (ffffffff81402e21)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8142982c)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
```
```
In drivers/tty/tty_io.c (ffffffff815343ba)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff815c5528)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815f9bf7)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff8170022c)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff8177669d)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81782e0d)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/compat.c (ffffffff817ac171)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff817fc921)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/unix/af_unix.c (ffffffff8182aeb9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8182f0e9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff8183527b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff8184ca70)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818522f6)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81856dac)
Location: arch/x86/include/asm/atomic64_64.h:84
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
In net/ipv6/mcast.c (ffffffff818596ff)
Location: arch/x86/include/asm/atomic64_64.h:84
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
In net/ipv6/tcp_ipv6.c (ffffffff81860ffb)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff818615cd)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81875447)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:packet_direct_xmit
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In kernel/fork.c (ffffffff81084a14)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In kernel/sys.c (ffffffff8109acdf)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/rcu/tree.c (ffffffff810f3523)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In kernel/audit_tree.c (ffffffff8113db68)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff8116b050)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/events/uprobes.c (ffffffff811a9720)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/workingset.c (ffffffff811e43c0)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff811e4467)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff811ea518)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mmap.c (ffffffff811f4241)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff811f6ab1)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/rmap.c (ffffffff811f9798)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ffc2a)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swapfile.c (ffffffff81202e00)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff8120d528)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/slub.c (ffffffff8121f11f)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8122462b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff81227278)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122e03a)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff8123a345)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff8123f90c)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff8125b75b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81262ff9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In fs/file.c (ffffffff812669f4)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff81292b3f)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/aio.c (ffffffff8129979e)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/proc/fd.c (ffffffff812c441a)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff8135b3f4)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813766ba)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In security/integrity/ima/ima_queue.c (ffffffff813ea87a)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff813ec7ef)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/bio.c (ffffffff8140e36b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-ioc.c (ffffffff8141cb51)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In block/cfq-iosched.c (ffffffff814430a8)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_request
```
```
In drivers/tty/tty_io.c (ffffffff81560ae5)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81627d67)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff81731f5e)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff817a391d)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff817b06de)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817cbd92)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/compat.c (ffffffff817db791)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff8182d884)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/unix/af_unix.c (ffffffff8185c8e9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81860b69)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81866db9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff8187e931)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818840b6)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81888bac)
Location: arch/x86/include/asm/atomic64_64.h:84
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
In net/ipv6/mcast.c (ffffffff8188b52f)
Location: arch/x86/include/asm/atomic64_64.h:84
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
In net/ipv6/tcp_ipv6.c (ffffffff81892f2b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff8189351a)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff818a9917)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:packet_direct_xmit
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
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In kernel/fork.c (ffffffff810818f1)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In kernel/sys.c (ffffffff81097add)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/rcu/tree.c (ffffffff810f3489)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In kernel/kcmp.c (ffffffff810f9787)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
```
```
In kernel/audit_tree.c (ffffffff8113f20b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff8116dfd0)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/events/uprobes.c (ffffffff811b0c0c)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811dcfb8)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In mm/workingset.c (ffffffff811ee823)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff811ee8c7)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff811f556b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mmap.c (ffffffff811ff15f)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81201983)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/rmap.c (ffffffff812046b4)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8120a858)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swapfile.c (ffffffff8120dea2)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/hugetlb.c (ffffffff812193fa)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/slub.c (ffffffff8122b8fe)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8122fa37)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812330b2)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8123a335)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81245cd9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/userfaultfd.c (ffffffff8124b463)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812685ee)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81270896)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In fs/file.c (ffffffff812741ef)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff8129fd21)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/aio.c (ffffffff812a7515)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/proc/fd.c (ffffffff812d16ae)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff8136fd5f)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff8138a22b)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In security/integrity/ima/ima_queue.c (ffffffff813f6bcc)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff813f8bdf)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/bio.c (ffffffff8141bf5d)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-ioc.c (ffffffff8142aac1)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
```
```
In block/cfq-iosched.c (ffffffff81452147)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_request
```
```
In drivers/tty/tty_io.c (ffffffff81574033)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c555d)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:dma_ops_domain_flush_tlb
  - drivers/iommu/amd_iommu.c:dma_ops_domain_flush_tlb
```
```
In drivers/block/loop.c (ffffffff81607f48)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8163d8a2)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff8174ae29)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff817c1a7d)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff817cec00)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817ea848)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff817f9946)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff817fad75)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff8184ec99)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/unix/af_unix.c (ffffffff81881069)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff818852c9)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff8188b5a0)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff818a49d7)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818aa86d)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff818af23c)
Location: arch/x86/include/asm/atomic64_64.h:84
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
In net/ipv6/mcast.c (ffffffff818b12bd)
Location: arch/x86/include/asm/atomic64_64.h:84
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
In net/ipv6/tcp_ipv6.c (ffffffff818b9466)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff818b9b09)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff818d0633)
Location: arch/x86/include/asm/atomic64_64.h:84
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:packet_direct_xmit
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
In kernel/fork.c (ffffffff810881d5)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
```
```
In kernel/sys.c (ffffffff8109e7cd)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/rcu/tree.c (ffffffff810fcea9)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
```
```
In kernel/kcmp.c (ffffffff81104219)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
```
```
In kernel/audit_tree.c (ffffffff8114c037)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff8117ae53)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
  - kernel/trace/tracing_map.c:tracing_map_insert
```
```
In kernel/events/uprobes.c (ffffffff811c4792)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811eef28)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/workingset.c (ffffffff81204c93)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff81204d37)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff8121775f)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8121a343)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/rmap.c (ffffffff8121d5f3)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81223bf0)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swapfile.c (ffffffff81229113)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81247012)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8124d763)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8125906e)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81265cfd)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/userfaultfd.c (ffffffff8126b74d)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff8128ae9e)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812931d6)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
```
```
In fs/file.c (ffffffff81296aef)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff812c3126)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/aio.c (ffffffff812ca898)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/proc/fd.c (ffffffff812f5ebd)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff81394a5f)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813ae458)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff8141ecec)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8142100f)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff81455cb1)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8147efbf)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
```
```
In drivers/tty/tty_io.c (ffffffff815d8526)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816290cd)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff81670bc1)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816a65f2)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff817bd18f)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff8183b48d)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81848520)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81865f92)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81877266)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff818786f5)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff818cea19)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/unix/af_unix.c (ffffffff819021f9)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81906479)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff8190c819)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff819273b5)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8192d386)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81931f4c)
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
In net/ipv6/mcast.c (ffffffff8193390d)
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
In net/ipv6/tcp_ipv6.c (ffffffff8193c3da)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff8193ca8f)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81955553)
Location: arch/x86/include/asm/atomic64_64.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:packet_direct_xmit
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
In kernel/fork.c (ffffffff8108bf25)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
```
```
In kernel/sys.c (ffffffff810a4036)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8110e9f0)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/audit_tree.c (ffffffff8115aa87)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff8118a25a)
Location: include/asm-generic/atomic-instrumented.h:106
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
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/events/uprobes.c (ffffffff811e4d45)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/oom_kill.c (ffffffff811f3cb7)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/vmscan.c (ffffffff8120b3cb)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff8120fa2d)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/workingset.c (ffffffff81225b33)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff81225bd3)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff812387f0)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8123c014)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8123f3e5)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81245155)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
```
In mm/swapfile.c (ffffffff8124a425)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81268349)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8127124e)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8127d3ef)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff81286601)
Location: include/asm-generic/atomic-instrumented.h:106
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
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff81290002)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812b168f)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812b8e2f)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
```
```
In fs/file.c (ffffffff812bcc8f)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff812ebd1b)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/fd.c (ffffffff81323305)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff813c3b81)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813df565)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff81450f8c)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8145356f)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff81489031)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
```
```
In block/cfq-iosched.c (ffffffff814b314c)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
```
```
In drivers/tty/tty_io.c (ffffffff81611c73)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff81663dd5)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff816ac0e4)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e28ec)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81805275)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff81885b8d)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818920b3)
Location: include/asm-generic/atomic-instrumented.h:106
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
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff818c8997)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff818ca8cd)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81924d86)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81957f47)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81959b35)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8195d305)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81963c65)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff8197f79a)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81985e42)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff8198aa1c)
Location: include/asm-generic/atomic-instrumented.h:106
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
Location: include/asm-generic/atomic-instrumented.h:106
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
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81995adc)
Location: include/asm-generic/atomic-instrumented.h:106
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819ae1c3)
Location: include/asm-generic/atomic-instrumented.h:106
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
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
```
```
In kernel/sys.c (ffffffff810ace06)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81119f70)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/audit_tree.c (ffffffff8116781a)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff81197bbf)
Location: include/asm-generic/atomic-instrumented.h:116
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
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff811f53b0)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81204949)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8121e0b3)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81222801)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/workingset.c (ffffffff812391f3)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81239293)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff8124c1b0)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81250434)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff81253af6)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828be1fa)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8125979b)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
```
In mm/swapfile.c (ffffffff8125ea66)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff8127de55)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff812856af)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff81291ffa)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8129b56e)
Location: include/asm-generic/atomic-instrumented.h:116
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
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff812a5036)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812c68df)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812cdf6f)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
```
```
In fs/file.c (ffffffff812d1f4f)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff812f9e00)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff812fff6c)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/fd.c (ffffffff8133a5d5)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff813dd331)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813f9be3)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff8146df6c)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8147074f)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff81478196)
Location: include/asm-generic/atomic-instrumented.h:116
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
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162e9e8)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816823c5)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff816cdbba)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81705d9c)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81831475)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818a62bd)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818b5f14)
Location: include/asm-generic/atomic-instrumented.h:116
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
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff818f38a1)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff818f599d)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81953b8c)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff8198d038)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff8198e6b5)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81991e45)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81998c00)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff819b5d8b)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bc433)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c12dc)
Location: include/asm-generic/atomic-instrumented.h:116
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
Location: include/asm-generic/atomic-instrumented.h:116
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
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff819cc3e8)
Location: include/asm-generic/atomic-instrumented.h:116
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819e4b53)
Location: include/asm-generic/atomic-instrumented.h:116
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b263c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81124bf0)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff81174462)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811a51af)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d60f3)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff8120d077)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81213ca5)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121c0c0)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8122d746)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81231e08)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/workingset.c (ffffffff8124a243)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff8124a2f3)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff8125e60d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8126275c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff81265d5b)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828d73cd)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff81274f67)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff8127afa7)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81299ca8)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8129ff1f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812aca23)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812b6753)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/zsmalloc.c (ffffffff812bebed)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812c06f9)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812e33ac)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812eadaf)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In fs/file.c (ffffffff812eef90)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff8131a4d7)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff81320fad)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8133208d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81362792)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff81408e70)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff814261e7)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149b63c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8149e120)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814a6067)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8166260b)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816b9b05)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff81708d76)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81740bad)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81874019)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818f174d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81901ec6)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81952747)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8195504a)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff819b8486)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff819f88a2)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff819f9e05)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819fd685)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a04a56)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a2486b)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a2af5f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a300a7)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a3aedc)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a53c30)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b8d0c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81130bb0)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff811802d2)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811b09df)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e2099)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff8121a3e5)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812257f9)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8123b928)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff8123fec8)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff81258693)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81258733)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8125c5ea)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126ce1d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81270f0c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff81274688)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828df83e)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff81283e73)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff8128aa87)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812a9b68)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b12bf)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812be2dd)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812c8623)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812d0b4d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812d2646)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812f4e3c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812fc8df)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In fs/file.c (ffffffff81300a50)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff8132d2f7)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff81333d4d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff81345c4d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff8137a9f2)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8143ff37)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814b587c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814b859f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814c09b7)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In block/blk-iocost.c (ffffffff81512e2a)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff81684c7b)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816dc8f5)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff8172d056)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81764e7f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff818a5e29)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8192369d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81934106)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81988a97)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8198b4ea)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff819ef186)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f502)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a30a85)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a34275)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b647)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a5b2eb)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a61abf)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a66bf7)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a71b5c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a8a820)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810c074c)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8113fc3a)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/audit_tree.c (ffffffff81193ae2)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811c8f96)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff811fc77f)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff812689f1)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8127114b)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (ffffffff81286f43)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8128bb32)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8129cbc7)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812a15c9)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff82cfcdfa)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff812b59e6)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
  - mm/madvise.c:madvise_willneed
```
```
In mm/swapfile.c (ffffffff812bd7bf)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812d9f13)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812e6755)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff812f3bb9)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812fdf0a)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8130296b)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff8130751b)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff8132d48c)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff8133517f)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
```
```
In fs/file.c (ffffffff81339c90)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813670a7)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8136eeda)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff81380519)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813c3a90)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81490cb7)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff81514f1c)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81518145)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff815211db)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
```
```
In block/blk-iocost.c (ffffffff815742f6)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff81735e10)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tioccons
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff817934d5)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff817e98a1)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81824b0f)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81975d81)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819f71f2)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_install_fd
```
```
In net/core/dev.c (ffffffff81a08af7)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81a60709)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff81a631d7)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81add0d8)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81b22115)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81b24cb5)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b29085)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b30c13)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81b53f17)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b5a97b)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b5f627)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81b6b44f)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81b863be)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810bcde0)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d0b2)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/audit_tree.c (ffffffff81190c52)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811c6656)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff81200c91)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81273462)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8127a62f)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff8127d365)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff81291263)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81296aee)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812a7f57)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812ace04)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff82fe987d)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff812c0ea0)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
```
```
In mm/slub.c (ffffffff812e5245)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/khugepaged.c (ffffffff812ff346)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff8130a3ac)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8130e728)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff8131325b)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff81338c2c)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81340aef)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
```
```
In fs/file.c (ffffffff813459d9)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff813743f7)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8137b26f)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8138a963)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_add_task_file
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813d5c1e)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff814ae404)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff81531f8c)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81535115)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff8153e22b)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
```
```
In block/blk-iocost.c (ffffffff815913ac)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff81752942)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tioccons
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff817bfe25)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff817fe321)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/net/tun.c (ffffffff8189c4fb)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819f6c62)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/core/dev.c (ffffffff81a0a22c)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81a68f99)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (ffffffff81ae9e2b)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30b0e)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81b33845)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b379b5)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f83e)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81b62516)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b69110)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b6ddc7)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81b79edd)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81b95ce8)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810be675)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d181)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/audit_tree.c (ffffffff81191bb2)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811c76b0)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff812016e1)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81278782)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8127f76f)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff812824f5)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff8129c68a)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812ac040)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812b20ed)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff831f3f26)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff812c8120)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
```
```
In mm/slub.c (ffffffff812ece15)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/khugepaged.c (ffffffff81305fc3)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff81310c45)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81314c04)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff81318e7b)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff8133f2bc)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81346f6f)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
```
```
In fs/file.c (ffffffff8134bd99)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff8137ada7)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8138302c)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8139bc64)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813dcc2e)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/ext4/mballoc.c (ffffffff81422bc0)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In ipc/shm.c (ffffffff814b4231)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff81539004)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8153a35c)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8153d735)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff815469e6)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
```
```
In block/blk-iocost.c (ffffffff815980ec)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff81736d26)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff817a3045)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/net/tun.c (ffffffff8187ea5f)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819dcdd5)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/core/dev.c (ffffffff819ee6c0)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81a4c359)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (ffffffff81ad5581)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e842)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81b21255)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b25655)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d6df)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81b50808)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b57280)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b5c14a)
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
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
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81b68a0e)
Location: include/asm-generic/atomic-instrumented.h:1048
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81b84bba)
Location: include/asm-generic/atomic-instrumented.h:1048
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
In kernel/trace/tracing_map.c (ffffffff811f2dfd)
Location: include/linux/atomic/atomic-instrumented.h:757
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff81233446)
Location: include/linux/atomic/atomic-instrumented.h:757
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
In fs/ext4/mballoc.c (ffffffff8147635d)
Location: include/linux/atomic/atomic-instrumented.h:757
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In crypto/algapi.c (ffffffff815a6f96)
Location: include/linux/atomic/atomic-instrumented.h:757
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
In block/blk-iocost.c (ffffffff815ff7fa)
Location: include/linux/atomic/atomic-instrumented.h:757
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/iommu/iova.c (ffffffff8182c385)
Location: include/linux/atomic/atomic-instrumented.h:757
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
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
In kernel/trace/tracing_map.c (ffffffff8122c3b4)
Location: include/linux/atomic/atomic-instrumented.h:807
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff812713a5)
Location: include/linux/atomic/atomic-instrumented.h:807
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
In fs/ext4/mballoc.c (ffffffff814f856b)
Location: include/linux/atomic/atomic-instrumented.h:807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In crypto/algapi.c (ffffffff8164e0f6)
Location: include/linux/atomic/atomic-instrumented.h:807
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
In block/blk-iocost.c (ffffffff816b1790)
Location: include/linux/atomic/atomic-instrumented.h:807
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/iommu/dma-iommu.c (ffffffff81969f75)
Location: include/linux/atomic/atomic-instrumented.h:807
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
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
In kernel/trace/tracing_map.c (ffffffff81277ee4)
Location: include/linux/atomic/atomic-instrumented.h:807
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff812c7221)
Location: include/linux/atomic/atomic-instrumented.h:807
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
Location: include/linux/atomic/atomic-instrumented.h:807
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
In fs/ext4/mballoc.c (ffffffff81592c18)
Location: include/linux/atomic/atomic-instrumented.h:807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
```
```
In crypto/algapi.c (ffffffff81707576)
Location: include/linux/atomic/atomic-instrumented.h:807
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
In block/blk-iocost.c (ffffffff8176fd13)
Location: include/linux/atomic/atomic-instrumented.h:807
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad3fd5)
Location: include/linux/atomic/atomic-instrumented.h:807
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
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
In kernel/trace/tracing_map.c (ffffffff8128f924)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff812ee7a8)
Location: include/linux/atomic/atomic-instrumented.h:1997
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
Location: include/linux/atomic/atomic-instrumented.h:1997
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
In mm/zswap.c (ffffffff81436818)
Location: include/linux/atomic/atomic-instrumented.h:1997
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
In fs/ext4/mballoc.c (ffffffff815c99f0)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_good_group_avg_frag_lists
```
```
In security/keys/dh.c (ffffffff816925c2)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81733179)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/aead.c (ffffffff81741ea2)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/geniv.c (ffffffff817421a9)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/skcipher.c (ffffffff81742ff2)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/ahash.c (ffffffff8174514d)
Location: include/linux/atomic/atomic-instrumented.h:1997
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
Location: include/linux/atomic/atomic-instrumented.h:1997
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
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/sig.c (ffffffff81747be1)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_sign
  - crypto/sig.c:crypto_sig_sign
```
```
In crypto/dh.c (ffffffff8174896e)
Location: include/linux/atomic/atomic-instrumented.h:1997
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
Location: include/linux/atomic/atomic-instrumented.h:1997
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
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_update
```
```
In crypto/rng.c (ffffffff81758463)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff817593c2)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
```
```
In block/blk-iocost.c (ffffffff817b0039)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In lib/iov_iter.c (ffffffff81811c77)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - lib/iov_iter.c:hash_and_copy_to_iter
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b227a5)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
```
```
In net/ipv4/tcp.c (ffffffff81f0aebc)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_key
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c162)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_headers
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffae1f)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
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
In kernel/cgroup/misc.c (ffffffff8124f4e8)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/trace/tracing_map.c (ffffffff812aae84)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
```
In kernel/bpf/syscall.c (ffffffff8130ce25)
Location: include/linux/atomic/atomic-instrumented.h:1997
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
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
```
In kernel/bpf/tcx.c (ffffffff8137b7b0)
Location: include/linux/atomic/atomic-instrumented.h:1997
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
Location: include/linux/atomic/atomic-instrumented.h:1997
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
In mm/zswap.c (ffffffff81470b4b)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
  - mm/zswap.c:__zswap_load
```
```
In fs/ext4/mballoc.c (ffffffff81602985)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_find_good_group_avg_frag_lists
  - fs/ext4/mballoc.c:ext4_mb_choose_next_group_p2_aligned
```
```
In security/keys/dh.c (ffffffff816ceb92)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/aead.c (ffffffff81782d82)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/geniv.c (ffffffff81783089)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/lskcipher.c (ffffffff81783d9a)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/lskcipher.c:crypto_lskcipher_decrypt
  - crypto/lskcipher.c:crypto_lskcipher_encrypt
  - crypto/lskcipher.c:crypto_lskcipher_crypt
```
```
In crypto/skcipher.c (ffffffff81785342)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_decrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
```
In crypto/ahash.c (ffffffff81787e76)
Location: include/linux/atomic/atomic-instrumented.h:1997
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
Location: include/linux/atomic/atomic-instrumented.h:1997
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
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/sig.c (ffffffff81789a51)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_verify
  - crypto/sig.c:crypto_sig_sign
  - crypto/sig.c:crypto_sig_sign
```
```
In crypto/dh.c (ffffffff8178a8be)
Location: include/linux/atomic/atomic-instrumented.h:1997
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
Location: include/linux/atomic/atomic-instrumented.h:1997
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
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
  - crypto/rng.c:crypto_rng_reset
```
```
In crypto/drbg.c (ffffffff8179b2c2)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed
```
```
In block/blk-iocost.c (ffffffff817f3e49)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79325)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
  - drivers/iommu/dma-iommu.c:fq_flush_iotlb
```
```
In drivers/net/netkit.c (ffffffff81ce658f)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_link_attach
  - drivers/net/netkit.c:netkit_link_update
  - drivers/net/netkit.c:netkit_link_release
  - drivers/net/netkit.c:netkit_prog_detach
  - drivers/net/netkit.c:netkit_prog_attach
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff510d)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
```
```
In net/ipv4/tcp_ao.c (ffffffff820585e5)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_ao_ignore_icmp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cb3dd)
Location: include/linux/atomic/atomic-instrumented.h:1997
Inline: True
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
In virt/kvm/arm/arm.c (ffff8000100c71a0)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl_run
```
```
In kernel/fork.c (ffff8000100f472c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffff800010115128)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffff800010197b00)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/audit_tree.c (ffff8000101f5640)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/ring_buffer.c (ffff8000102186e0)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/trace/tracing_map.c (ffff80001022ec00)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
```
```
In kernel/bpf/syscall.c (ffff8000102657d4)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffff80001029f180)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/ring_buffer.c (ffff8000102a2838)
Location: include/linux/atomic-fallback.h:1376
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
In kernel/events/uprobes.c (ffff8000102a57d4)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102b2910)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffff8000102b7838)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffff8000102ccb44)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffff8000102d3218)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffff8000102f04c0)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffff8000102f0660)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffff8000102f4af8)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffff8000103040a4)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffff800010306f5c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/msync.c:__arm64_sys_msync
```
```
In mm/rmap.c (ffff80001030a288)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffff8000114588d4)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffff80001031e188)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
```
```
In mm/swapfile.c (ffff8000103260e4)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffff80001034b638)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffff8000103518b4)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffff80001035fc2c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffff800010365d3c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
```
```
In mm/memory-failure.c (ffff8000103705b0)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffff80001037591c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffff8000103781b0)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/select.c (ffff8000103a1e50)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffff8000103ac6ec)
Location: include/linux/atomic-fallback.h:1376
Inline: True
```
```
In fs/file.c (ffff8000103b29f4)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffff8000103e9494)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffff8000103f1b30)
Location: include/linux/atomic-fallback.h:1376
Inline: True
```
```
In fs/io_uring.c (ffff800010403c48)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
```
```
In fs/proc/fd.c (ffff800010446fa0)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffff8000105286fc)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffff8000105adcec)
Location: include/linux/atomic-fallback.h:1376
Inline: True
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0824)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffff8000105ba98c)
Location: include/linux/atomic-fallback.h:1376
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
In block/blk-ioc.c (ffff8000105e87fc)
Location: include/linux/atomic-fallback.h:1376
Inline: True
```
```
In block/genhd.c (ffff8000105faafc)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/blk-iocost.c (ffff80001061723c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffff800010852574)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffff8000108cd0e4)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffff8000109249ac)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffff8000109656dc)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffff800010afad08)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffff800010bbde7c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffff800010bd2468)
Location: include/linux/atomic-fallback.h:1376
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
In net/core/filter.c (ffff800010c01534)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffff800010c30c50)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffff800010c35f28)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffff800010ca4fc0)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffff800010cee690)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffff800010cf0d58)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffff800010cf47b4)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffff800010cfc76c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffff800010d20b1c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d26b50)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffff800010d2cb40)
Location: include/linux/atomic-fallback.h:1376
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
In net/ipv6/mcast.c (ffff800010d3012c)
Location: include/linux/atomic-fallback.h:1376
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
In net/ipv6/tcp_ipv6.c (ffff800010d39d8c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffff800010d3a594)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffff800010d581d0)
Location: include/linux/atomic-fallback.h:1376
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
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c0768cac)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
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
In block/blk-iocost.c (c07c2068)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
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
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011f608)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_protect
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_bulk_remove
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_remove
```
```
In kernel/fork.c (c00000000013a690)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (c00000000015d0d8)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (c0000000001f7d0c)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/audit_tree.c (c00000000026ac4c)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (c0000000002b8294)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_lookup
```
```
In kernel/bpf/syscall.c (c00000000030a300)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (c0000000003585e8)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c000000000368ba8)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (c00000000036f634)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (c00000000038a344)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (c000000000391c74)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (c0000000003b4f1c)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (c0000000003b5004)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (c0000000003baa70)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (c0000000003d0e04)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (c0000000003d50a0)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/rmap.c (c0000000003d9d08)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (c000000001382130)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (c0000000003f257c)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/swapfile.c (c0000000003fc630)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (c00000000042ac64)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (c000000000437e8c)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (c00000000044a9a8)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (c00000000045af94)
Location: arch/powerpc/include/asm/atomic.h:397
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
In mm/memory-failure.c (c000000000461d98)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (c000000000466774)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (c00000000046a8fc)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (c00000000049b948)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (c0000000004a7968)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
```
```
In fs/file.c (c0000000004ae974)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (c0000000004efe6c)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (c0000000004f9438)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
```
```
In fs/io_uring.c (c000000000510b18)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/proc/fd.c (c00000000055ce6c)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (c0000000006731c4)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (c00000000072c884)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (c000000000730524)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (c00000000074139c)
Location: arch/powerpc/include/asm/atomic.h:397
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
In block/blk-ioc.c (c00000000077dacc)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
```
```
In block/blk-iocost.c (c0000000007b6ae8)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (c0000000008f0dd4)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (c0000000009c88d0)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (c000000000a1bf68)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (c000000000be8d74)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (c000000000c976b0)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (c000000000cb0aac)
Location: arch/powerpc/include/asm/atomic.h:397
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
In net/core/filter.c (c000000000ce9038)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (c000000000d299d8)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (c000000000d2e0e0)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (c000000000db8c80)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (c000000000e13328)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (c000000000e146d4)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (c000000000e1a77c)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (c000000000e24320)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (c000000000e4ef98)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c000000000e5787c)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (c000000000e5e61c)
Location: arch/powerpc/include/asm/atomic.h:397
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
In net/ipv6/mcast.c (c000000000e6144c)
Location: arch/powerpc/include/asm/atomic.h:397
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
In net/ipv6/tcp_ipv6.c (c000000000e6add4)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (c000000000e6d79c)
Location: arch/powerpc/include/asm/atomic.h:397
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (c000000000e93240)
Location: arch/powerpc/include/asm/atomic.h:397
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
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c0d08)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffe0000d214e)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffe000128cd8)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffe000168810)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/ring_buffer.c (ffffffe000176afe)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/syscall.c (ffffffe0001a1096)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffffffe0001ce75e)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/ring_buffer.c (ffffffe0001d146a)
Location: include/linux/atomic-fallback.h:1376
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
In mm/filemap.c (ffffffe0001d8206)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffe0001dbb34)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffe0001eb544)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffe0001ee3ce)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffe000203e62)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffe000203f0c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffe000205c94)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffe000210948)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffe0002124de)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/rmap.c (ffffffe000214030)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffe000016f58)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffe000221234)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/swapfile.c (ffffffe000226440)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffe00023ccec)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/memcontrol.c (ffffffe000248c0e)
Location: include/linux/atomic-fallback.h:1376
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
In mm/zsmalloc.c (ffffffe00024e678)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffe00024feaa)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffe00026a6fe)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffe000270cd6)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/inode.c:drop_nlink
```
```
In fs/file.c (ffffffe000276a1a)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffe00029dc84)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffe0002a4364)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffe0002b1350)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/proc/fd.c (ffffffe0002dcd6e)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffe00038bd76)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In security/integrity/ima/ima_queue.c (ffffffe0003f6064)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffe0003f83d8)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffe00040069a)
Location: include/linux/atomic-fallback.h:1376
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
In block/blk-ioc.c (ffffffe000429796)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
```
```
In block/genhd.c (ffffffe000436e56)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In block/blk-iocost.c (ffffffe00044d8bc)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffe00052f80e)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffe0005a1aca)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffe0005d1faa)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffe0006ec5c2)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffe00074c646)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffe00075c970)
Location: include/linux/atomic-fallback.h:1376
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
In net/core/filter.c (ffffffe00077fffa)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffe0007a6b5c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (ffffffe0008008da)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b856)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffe00083d0e0)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffe0008405de)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffe00084700a)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffe000862b9c)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffe000868b24)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffe00086cdc6)
Location: include/linux/atomic-fallback.h:1376
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
In net/ipv6/mcast.c (ffffffe00086f884)
Location: include/linux/atomic-fallback.h:1376
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
In net/ipv6/tcp_ipv6.c (ffffffe000875bb6)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffe000877238)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffe00088f410)
Location: include/linux/atomic-fallback.h:1376
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
In kernel/fork.c (ffffffff810998b6)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b307c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81129360)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff811788f2)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811a8fff)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811da6b9)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff81212a35)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121de49)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81233f78)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81238518)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff81250ce3)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81250d83)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81254c3a)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126546d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8126955c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8126ccd8)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828c86f2)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8127c4c3)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81283067)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812a2148)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a989f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b68bd)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812c0c03)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812c912d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812cac26)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812ed41c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812f4ebf)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In fs/file.c (ffffffff812f9030)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813258d7)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8132c32d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8133e22d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81372fd2)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81438517)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814ade5c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814b0b7f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814b8f97)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In block/blk-iocost.c (ffffffff8150b40a)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff8164a6fb)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816a2345)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff816f2e36)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171956f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff8184bca9)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818c369d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818d4106)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81928907)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8192b35a)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff8198ef26)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff819ceb92)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff819d0115)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819d3905)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff819dacd7)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff819fa97b)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a0114f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a06287)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a111ec)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a29eb0)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810a19ac)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8111bbf0)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff8116ba92)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff8119bf7f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811cd479)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff812057af)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81210fff)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81226fe8)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff8122b519)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff81243c23)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81243cc3)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81247a7a)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8125788d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8125b84c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8125ed14)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828c0e17)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8126e373)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81274ff4)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81293c28)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8129b1ff)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812a7a8d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812b1c7b)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812ba16d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812bbbb0)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812de04c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812e5adf)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In fs/file.c (ffffffff812e9c50)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff81316477)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8131d691)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8132eeed)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81363aa2)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81428f87)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149e87c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814a159f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814a99b7)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In block/blk-iocost.c (ffffffff814fb86a)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff8162ab4b)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff8167fd35)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff816ccf36)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f29df)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/net/vxlan.c (ffffffff81772f72)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In drivers/md/md-bitmap.c (ffffffff818132c9)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8187d5dd)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff8188df96)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff818e26b7)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff818e510a)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff819489e6)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b956)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff8198ced5)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819906c5)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81997a97)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff819b773b)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bdf0f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c3047)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff819cdfac)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819e70a0)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b25dc)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81127080)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff811766c2)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811a6dcf)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811d8489)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff812107d5)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121bbe9)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81231d18)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff812362b8)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff8124ea83)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff8124eb23)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812529da)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126320d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812672fc)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8126aa78)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828db472)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8127a263)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81280e77)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff8129ff58)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a76af)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b46cd)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812bea13)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812c6f3d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812c8a36)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812eb22c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812f2ccf)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In fs/file.c (ffffffff812f6e40)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813233a7)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff81329dfd)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8133bcfd)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81370aa2)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff814346b7)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814a9efc)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814acc0f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814b5027)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In block/blk-iocost.c (ffffffff8150749a)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff81678abb)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816d05b5)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff81720516)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8175833f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff8189b2d9)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8191469d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81925106)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81979a97)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8197c4ea)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199ddc4)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_kill_acct
  - net/netfilter/nf_conntrack_core.c:__nf_ct_refresh_acct
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/ipv4/icmp.c (ffffffff819f97c6)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81a39612)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a3ab95)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a3e385)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a45757)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a653fb)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a6bbcf)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a70d07)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a7bc6c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a95a60)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810babdc)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff811336c8)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff81183f92)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/tracing_map.c (ffffffff811b4b6f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffff811e6817)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff8121f6e6)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8122ac47)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81241178)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81246593)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff8125e3fc)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff8125e4a3)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812623aa)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff81272bcd)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81276c9c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8127a3e1)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828e0893)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff81289e43)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81290b84)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812b0098)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b79b5)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812c507e)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812cf483)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812d62ab)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812d972e)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812fc21c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff813043df)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In fs/file.c (ffffffff813080b0)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813350f7)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8133c8c4)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/io_uring.c (ffffffff8134eead)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81384482)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8144b7d9)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814c294c)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814c565f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In crypto/algapi.c (ffffffff814cdaa7)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
```
```
In block/blk-iocost.c (ffffffff8152095d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_timer_fn
```
```
In drivers/tty/tty_io.c (ffffffff816926f4)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/iommu/iova.c (ffffffff816eab45)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_domain_flush
  - drivers/iommu/iova.c:iova_domain_flush
```
```
In drivers/block/loop.c (ffffffff8173b8d6)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8177381f)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff818b7439)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8193586d)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff819465e6)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff8199bfb9)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8199ea3a)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81a03ab6)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81a45042)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a45e15)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a49e45)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a51427)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a7196e)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a781df)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a7d317)
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
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
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a884bc)
Location: include/asm-generic/atomic-instrumented.h:1047
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81aa26a0)
Location: include/asm-generic/atomic-instrumented.h:1047
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
