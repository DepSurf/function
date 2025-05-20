# Function: <code>atomic_long_inc</code>

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
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In kernel/fork.c (ffffffff8107e3b4)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff81092b77)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/rcu/tree.c (ffffffff810e4f2a)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited
```
```
In kernel/audit_tree.c (ffffffff8112bbf8)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/events/core.c (ffffffff81184cc5)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_get
```
```
In kernel/events/uprobes.c (ffffffff8118781b)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/workingset.c (ffffffff811b9f60)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff811b9ff7)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff811bd2b1)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc
  - mm/memory.c:__pmd_alloc
```
```
In mm/mmap.c (ffffffff811c71f6)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff811ca2fd)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/rmap.c (ffffffff811cb522)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811d1a02)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swapfile.c (ffffffff811d3dfc)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/hugetlb.c (ffffffff811de4ee)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/slub.c (ffffffff811e99ed)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:kmem_cache_open
```
```
In mm/migrate.c (ffffffff811f298d)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff811f4403)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memory-failure.c (ffffffff812030e2)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff81207afb)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff81220adb)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812277c9)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In fs/file.c (ffffffff81229f71)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
  - fs/file.c:f_dupfd
```
```
In fs/eventpoll.c (ffffffff8125668a)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/proc/fd.c (ffffffff81281909)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff81311259)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff8132b215)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In security/integrity/ima/ima_queue.c (ffffffff813971d8)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff813987df)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/bio.c (ffffffff813b0f8b)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-ioc.c (ffffffff813bee51)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In block/cfq-iosched.c (ffffffff813e34a1)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
```
```
In drivers/tty/tty_io.c (ffffffff814e1ca6)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:redirected_tty_write
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/block/loop.c (ffffffff8156fc08)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a2b69)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff8169ee5f)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff8170ec97)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/scm.c:scm_fp_dup
```
```
In net/core/dev.c (ffffffff81717c53)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/compat.c (ffffffff8173f463)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff8178f064)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_out_count
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/unix/af_unix.c (ffffffff817bdf49)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff817c20d9)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff817c81a5)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff817deb34)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff817e3f47)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff817e7ce9)
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff817f2885)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff818038a4)
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In kernel/fork.c (ffffffff810800b4)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In kernel/sys.c (ffffffff81095cfb)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/rcu/tree.c (ffffffff810eb987)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In kernel/audit_tree.c (ffffffff81133de8)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/events/uprobes.c (ffffffff81199fec)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/workingset.c (ffffffff811d4370)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff811d4417)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff811da9ab)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mmap.c (ffffffff811e4241)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff811e67e1)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/rmap.c (ffffffff811e866d)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ef2aa)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swapfile.c (ffffffff811f2405)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff811fca44)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/slub.c (ffffffff8120d0bf)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8121243c)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff81214c90)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121c606)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81227da9)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff8122d3e9)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff8124872b)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff8124ff59)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In fs/file.c (ffffffff812537a4)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff8127efaf)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/proc/fd.c (ffffffff812aea46)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff813456c4)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff8135feba)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In security/integrity/ima/ima_queue.c (ffffffff813d3232)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff813d4d9f)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/bio.c (ffffffff813f497b)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-ioc.c (ffffffff81402e21)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8142982c)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
```
```
In drivers/tty/tty_io.c (ffffffff815343ba)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff815c5528)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815f9bf7)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff8170022c)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff8177669d)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81782e0d)
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff817fc921)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/unix/af_unix.c (ffffffff8182aeb9)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8182f0e9)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff8183527b)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff8184ca70)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818522f6)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81856dac)
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff818615cd)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81875447)
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In kernel/fork.c (ffffffff81084a14)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In kernel/sys.c (ffffffff8109acdf)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/rcu/tree.c (ffffffff810f3523)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In kernel/audit_tree.c (ffffffff8113db68)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/events/uprobes.c (ffffffff811a9720)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/workingset.c (ffffffff811e43c0)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff811e4467)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff811ea518)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mmap.c (ffffffff811f4241)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff811f6ab1)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/rmap.c (ffffffff811f9798)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ffc2a)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swapfile.c (ffffffff81202e00)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:swap_entry_free
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page
```
```
In mm/hugetlb.c (ffffffff8120d528)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/slub.c (ffffffff8121f11f)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8122462b)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff81227278)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122e03a)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff8123a345)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff8123f90c)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff8125b75b)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81262ff9)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In fs/file.c (ffffffff812669f4)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff81292b3f)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/aio.c (ffffffff8129979e)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/proc/fd.c (ffffffff812c441a)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff8135b3f4)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813766ba)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In security/integrity/ima/ima_queue.c (ffffffff813ea87a)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff813ec7ef)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/bio.c (ffffffff8140e36b)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-ioc.c (ffffffff8141cb51)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In block/cfq-iosched.c (ffffffff814430a8)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_request
```
```
In drivers/tty/tty_io.c (ffffffff81560ae5)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81627d67)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff81731f5e)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff817a391d)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff817b06de)
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/compat.c (ffffffff817db791)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff8182d884)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/unix/af_unix.c (ffffffff8185c8e9)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81860b69)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81866db9)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff8187e931)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818840b6)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81888bac)
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff8189351a)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff818a9917)
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In kernel/fork.c (ffffffff810818f1)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In kernel/sys.c (ffffffff81097add)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/rcu/tree.c (ffffffff810f3489)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In kernel/kcmp.c (ffffffff810f9787)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
```
```
In kernel/audit_tree.c (ffffffff8113f20b)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/events/uprobes.c (ffffffff811b0c0c)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811dcfb8)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In mm/workingset.c (ffffffff811ee823)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff811ee8c7)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff811f556b)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc
```
```
In mm/mmap.c (ffffffff811ff15f)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81201983)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/rmap.c (ffffffff812046b4)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8120a858)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swapfile.c (ffffffff8120dea2)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/hugetlb.c (ffffffff812193fa)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/slub.c (ffffffff8122b8fe)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8122fa37)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812330b2)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8123a335)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81245cd9)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/userfaultfd.c (ffffffff8124b463)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812685ee)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81270896)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In fs/file.c (ffffffff812741ef)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff8129fd21)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/aio.c (ffffffff812a7515)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/proc/fd.c (ffffffff812d16ae)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff8136fd5f)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff8138a22b)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - ipc/shm.c:SyS_shmctl
```
```
In security/integrity/ima/ima_queue.c (ffffffff813f6bcc)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff813f8bdf)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/bio.c (ffffffff8141bf5d)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - block/bio.c:bio_associate_current
```
```
In block/blk-ioc.c (ffffffff8142aac1)
Location: include/asm-generic/atomic-long.h:101
Inline: True
```
```
In block/cfq-iosched.c (ffffffff81452147)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_request
```
```
In drivers/tty/tty_io.c (ffffffff81574033)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff81607f48)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8163d8a2)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/bitmap.c (ffffffff8174ae29)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff817c1a7d)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff817cec00)
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff817f9946)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff817fad75)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff8184ec99)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/unix/af_unix.c (ffffffff81881069)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff818852c9)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff8188b5a0)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff818a49d7)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff818aa86d)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff818af23c)
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff818b9b09)
Location: include/asm-generic/atomic-long.h:101
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff818d0633)
Location: include/asm-generic/atomic-long.h:101
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
Location: include/asm-generic/atomic-long.h:102
Inline: True
```
```
In kernel/sys.c (ffffffff8109e7cd)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/rcu/tree.c (ffffffff810fcea9)
Location: include/asm-generic/atomic-long.h:102
Inline: True
```
```
In kernel/kcmp.c (ffffffff81104219)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - kernel/kcmp.c:SyS_kcmp
```
```
In kernel/audit_tree.c (ffffffff8114c037)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/events/uprobes.c (ffffffff811c4792)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811eef28)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/workingset.c (ffffffff81204c93)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff81204d37)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff8121775f)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8121a343)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/msync.c:SyS_msync
```
```
In mm/rmap.c (ffffffff8121d5f3)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81223bf0)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
```
In mm/swapfile.c (ffffffff81229113)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81247012)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8124d763)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8125906e)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81265cfd)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/userfaultfd.c (ffffffff8126b74d)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff8128ae9e)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812931d6)
Location: include/asm-generic/atomic-long.h:102
Inline: True
```
```
In fs/file.c (ffffffff81296aef)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff812c3126)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_ctl
```
```
In fs/aio.c (ffffffff812ca898)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
```
In fs/proc/fd.c (ffffffff812f5ebd)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff81394a5f)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813ae458)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff8141ecec)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8142100f)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff81455cb1)
Location: include/asm-generic/atomic-long.h:102
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8147efbf)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
```
```
In drivers/tty/tty_io.c (ffffffff815d8526)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff81670bc1)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816a65f2)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff817bd18f)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff8183b48d)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81848520)
Location: include/asm-generic/atomic-long.h:102
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
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81877266)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff818786f5)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff818cea19)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/unix/af_unix.c (ffffffff819021f9)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81906479)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff8190c819)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff819273b5)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff8192d386)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81931f4c)
Location: include/asm-generic/atomic-long.h:102
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
Location: include/asm-generic/atomic-long.h:102
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
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff8193ca8f)
Location: include/asm-generic/atomic-long.h:102
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81955553)
Location: include/asm-generic/atomic-long.h:102
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
Location: include/asm-generic/atomic-long.h:119
Inline: True
```
```
In kernel/sys.c (ffffffff810a4036)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8110e9f0)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/audit_tree.c (ffffffff8115aa87)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/bpf/syscall.c (ffffffff811b390f)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/events/uprobes.c (ffffffff811e4d45)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/oom_kill.c (ffffffff811f3cb7)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/vmscan.c (ffffffff8120b3cb)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff8120fa2d)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/workingset.c (ffffffff81225b33)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/prfile.c (ffffffff81225bd3)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff812387f0)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8123c014)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8123f3e5)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81245155)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
```
In mm/swapfile.c (ffffffff8124a425)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81268349)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8127124e)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff8127d3ef)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff81286601)
Location: include/asm-generic/atomic-long.h:119
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
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff81290002)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812b168f)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812b8e2f)
Location: include/asm-generic/atomic-long.h:119
Inline: True
```
```
In fs/file.c (ffffffff812bcc8f)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/eventpoll.c (ffffffff812ebd1b)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/fd.c (ffffffff81323305)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff813c3b81)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813df565)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff81450f8c)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8145356f)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff81489031)
Location: include/asm-generic/atomic-long.h:119
Inline: True
```
```
In block/cfq-iosched.c (ffffffff814b314c)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_dispatch_requests
```
```
In drivers/tty/tty_io.c (ffffffff81611c73)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff816ac0e4)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e28ec)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81805275)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In net/core/scm.c (ffffffff81885b8d)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818920b3)
Location: include/asm-generic/atomic-long.h:119
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
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff818c8997)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff818ca8cd)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81924d86)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81957f47)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81959b35)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8195d305)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81963c65)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff8197f79a)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81985e42)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff8198aa1c)
Location: include/asm-generic/atomic-long.h:119
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
Location: include/asm-generic/atomic-long.h:119
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
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81995adc)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819ae1c3)
Location: include/asm-generic/atomic-long.h:119
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
Location: include/asm-generic/atomic-long.h:119
Inline: True
```
```
In kernel/sys.c (ffffffff810ace06)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81119f70)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/audit_tree.c (ffffffff8116781a)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/bpf/syscall.c (ffffffff811c45ae)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff811f53b0)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81204949)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8121e0b3)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81222801)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/workingset.c (ffffffff812391f3)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81239293)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff8124c1b0)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81250434)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff81253af6)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828be1fa)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8125979b)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
```
In mm/swapfile.c (ffffffff8125ea66)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff8127de55)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff812856af)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff81291ffa)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8129b56e)
Location: include/asm-generic/atomic-long.h:119
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
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/userfaultfd.c (ffffffff812a5036)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812c68df)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812cdf6f)
Location: include/asm-generic/atomic-long.h:119
Inline: True
```
```
In fs/file.c (ffffffff812d1f4f)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff812f9e00)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff812fff6c)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/proc/fd.c (ffffffff8133a5d5)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff813dd331)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff813f9be3)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff8146df6c)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8147074f)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff814a2f61)
Location: include/asm-generic/atomic-long.h:119
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162e9e8)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff816cdbba)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81705d9c)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81831475)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818a62bd)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818b5f14)
Location: include/asm-generic/atomic-long.h:119
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
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff818f38a1)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff818f599d)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81953b8c)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff8198d038)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff8198e6b5)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81991e45)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81998c00)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff819b5d8b)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bc433)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c12dc)
Location: include/asm-generic/atomic-long.h:119
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
Location: include/asm-generic/atomic-long.h:119
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
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff819cc3e8)
Location: include/asm-generic/atomic-long.h:119
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819e4b53)
Location: include/asm-generic/atomic-long.h:119
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b263c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81124bf0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff81174462)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/bpf/syscall.c (ffffffff811d60f3)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff8120d077)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81213ca5)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121c0c0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8122d746)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81231e08)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/workingset.c (ffffffff8124a243)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff8124a2f3)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/mmap.c (ffffffff8125e60d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8126275c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff81265d5b)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828d73cd)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff81274f67)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff8127afa7)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81299ca8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8129ff1f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812aca23)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812b6753)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In mm/zsmalloc.c (ffffffff812bebed)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812c06f9)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812e33ac)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812eadaf)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In fs/file.c (ffffffff812eef90)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff8131a4d7)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff81320fad)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8133208d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81362792)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In fs/fuse/dev.c (ffffffff81408e70)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_get_req_nofail_nopages
```
```
In ipc/shm.c (ffffffff814261e7)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149b63c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8149e120)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff814d1011)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8166260b)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff81708d76)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81740bad)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81874019)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818f174d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81901ec6)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81952747)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8195504a)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff819b8486)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff819f88a2)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff819f9e05)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819fd685)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a04a56)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a2486b)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a2af5f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a300a7)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a3aedc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a53c30)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b8d0c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81130bb0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff811802d2)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/bpf/syscall.c (ffffffff811e2099)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff8121a3e5)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812257f9)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8123b928)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff8123fec8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff81258693)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81258733)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8125c5ea)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126ce1d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81270f0c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff81274688)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828df83e)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff81283e73)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff8128aa87)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812a9b68)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b12bf)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812be2dd)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812c8623)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812d0b4d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812d2646)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812f4e3c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812fc8df)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In fs/file.c (ffffffff81300a50)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff8132d2f7)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff81333d4d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff81345c4d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff8137a9f2)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8143ff37)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814b587c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814b859f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff814ea3d1)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81684c7b)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff8172d056)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81764e7f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff818a5e29)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8192369d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81934106)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81988a97)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8198b4ea)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff819ef186)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f502)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a30a85)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a34275)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b647)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a5b2eb)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a61abf)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a66bf7)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a71b5c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a8a820)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810c074c)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8113fc3a)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/audit_tree.c (ffffffff81193ae2)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/bpf/syscall.c (ffffffff811fc77f)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In mm/filemap.c (ffffffff812534a2)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff812689f1)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8127114b)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/prfile.c (ffffffff81286f43)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8128bb32)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8129cbc7)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812a15c9)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff82cfcdfa)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff812b59e6)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
  - mm/madvise.c:madvise_willneed
```
```
In mm/swapfile.c (ffffffff812bd7bf)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812d9f13)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812e6755)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move
```
```
In mm/khugepaged.c (ffffffff812f3bb9)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812fdf0a)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8130296b)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff8130751b)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff8132d48c)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff8133517f)
Location: include/asm-generic/atomic-long.h:159
Inline: True
```
```
In fs/file.c (ffffffff81339c90)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813670a7)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8136eeda)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff81380519)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813c3a90)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81490cb7)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff81514f1c)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81518145)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff81549371)
Location: include/asm-generic/atomic-long.h:159
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81735e10)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tioccons
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff817e98a1)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81824b0f)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff81975d81)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819f71f2)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:__scm_install_fd
```
```
In net/core/dev.c (ffffffff81a08af7)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81a60709)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff81a631d7)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81add0d8)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81b22115)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81b24cb5)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b29085)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b30c13)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81b53f17)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b5a97b)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b5f627)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81b6b44f)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81b863be)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810bcde0)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d0b2)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/audit_tree.c (ffffffff81190c52)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff8125e0ab)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81273462)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8127a62f)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff8127d365)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff81291263)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81296aee)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812a7f57)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812ace04)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff82fe987d)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff812c0ea0)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/madvise.c:madvise_remove
```
```
In mm/slub.c (ffffffff812e5245)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/khugepaged.c (ffffffff812ff346)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff8130a3ac)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8130e728)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff8131325b)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff81338c2c)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81340aef)
Location: include/asm-generic/atomic-long.h:159
Inline: True
```
```
In fs/file.c (ffffffff813459d9)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff813743f7)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8137b26f)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8138a963)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_add_task_file
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813d5c1e)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff814ae404)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff81531f8c)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81535115)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff81565191)
Location: include/asm-generic/atomic-long.h:159
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81752942)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tioccons
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff817fe321)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/net/tun.c (ffffffff8189c4fb)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819f6c62)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/core/dev.c (ffffffff81a0a22c)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81a68f99)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (ffffffff81ae9e2b)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30b0e)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81b33845)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b379b5)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f83e)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81b62516)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b69110)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b6ddc7)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81b79edd)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81b95ce8)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mmap
```
```
In kernel/sys.c (ffffffff810be675)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8111d181)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/audit_tree.c (ffffffff81191bb2)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff81260d6d)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81278782)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8127f76f)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff812824f5)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff8129c68a)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812ac040)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__split_vma
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812b20ed)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff831f3f26)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff812c8120)
Location: include/asm-generic/atomic-long.h:159
Inline: True
```
```
In mm/slub.c (ffffffff812ece15)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/khugepaged.c (ffffffff81305fc3)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff81310c45)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81314c04)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/zsmalloc.c (ffffffff81318e7b)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff8133f2bc)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81346f6f)
Location: include/asm-generic/atomic-long.h:159
Inline: True
```
```
In fs/file.c (ffffffff8134bd99)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff8137ada7)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8138302c)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8139bc64)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/io_uring.c:__io_sqe_files_update
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff813dcc2e)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff814b4231)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff81539004)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8153a35c)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8153d735)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff8156d801)
Location: include/asm-generic/atomic-long.h:159
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81736d26)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/net/tun.c (ffffffff8187ea5f)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff819dcdd5)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/core/dev.c (ffffffff819ee6c0)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81a4c359)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (ffffffff81ad5581)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e842)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81b21255)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81b25655)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d6df)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81b50808)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81b57280)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81b5c14a)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
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
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81b68a0e)
Location: include/asm-generic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81b84bba)
Location: include/asm-generic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810b4eab)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d554)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/audit_tree.c (ffffffff811baa72)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff8129d7d0)
Location: include/linux/atomic/atomic-instrumented.h:1335
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
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff812b64dc)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff812bda26)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff812c0605)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff812d6fe3)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812dd302)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812ef2fb)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812f3ce4)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff832da26c)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8130d104)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In mm/slub.c (ffffffff81335025)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff8133c959)
Location: include/linux/atomic/atomic-instrumented.h:1335
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
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff8135bf09)
Location: include/linux/atomic/atomic-instrumented.h:1335
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
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81360c84)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff81365488)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff8138cc4c)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff813949cf)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
```
```
In fs/file.c (ffffffff81399bd9)
Location: include/linux/atomic/atomic-instrumented.h:1335
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
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff813c7fac)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/io_uring.c (ffffffff813e7379)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff8142e30e)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8150c8cb)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff81597844)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff81598cdc)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8159c5b5)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff815d21d7)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
```
```
In drivers/tty/tty_io.c (ffffffff817b76ff)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff8186e03e)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/net/tun.c (ffffffff8191024a)
Location: include/linux/atomic/atomic-instrumented.h:1335
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
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81a8d015)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/core/dev.c (ffffffff81a9f95d)
Location: include/linux/atomic/atomic-instrumented.h:1335
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
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81b04809)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (ffffffff81b94387)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81be3364)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81be6315)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81bead65)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81bf38be)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81c17bb0)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81c1e85a)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81c238b1)
Location: include/linux/atomic/atomic-instrumented.h:1335
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
Location: include/linux/atomic/atomic-instrumented.h:1335
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
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81c306d8)
Location: include/linux/atomic/atomic-instrumented.h:1335
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81c5105c)
Location: include/linux/atomic/atomic-instrumented.h:1335
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
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810c954a)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81160946)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff811da1a9)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff811eddd2)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff812f4886)
Location: include/linux/atomic/atomic-instrumented.h:1426
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
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8131197e)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff81319799)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff8131d0c5)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff81336843)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8133cfec)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff81352729)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81357b11)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff8348f2fc)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/madvise.c (ffffffff813786e6)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/slub.c (ffffffff813ad46c)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff813afd79)
Location: include/linux/atomic/atomic-instrumented.h:1426
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
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff813d5802)
Location: include/linux/atomic/atomic-instrumented.h:1426
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
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff813d8b3e)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff8140df2c)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81416baf)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
```
```
In fs/file.c (ffffffff8141c689)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff83495644)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff8144efd8)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/coredump.c (ffffffff81484a32)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff814a7a37)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8159e87a)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff81639348)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8163d6fe)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff816415f4)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff8167dd85)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In io_uring/io_uring.c (ffffffff816d3cc2)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff818f2cfa)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819edad8)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/net/tun.c (ffffffff81a63f18)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/vfio/vfio.c (ffffffff81a76e56)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_open
```
```
In drivers/md/md-bitmap.c (ffffffff81b6c580)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81c02905)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81c95827)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/icmp.c (ffffffff81d25c46)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/unix/af_unix.c (ffffffff81d7ed65)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81d83015)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c495)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81db3998)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81dbb0aa)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81dc07e2)
Location: include/linux/atomic/atomic-instrumented.h:1426
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
Location: include/linux/atomic/atomic-instrumented.h:1426
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
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81dcde16)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81df2508)
Location: include/linux/atomic/atomic-instrumented.h:1426
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
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810e6aa6)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81193e86)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff8121f729)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff81234402)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff8135e9c6)
Location: include/linux/atomic/atomic-instrumented.h:1426
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
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81384fa9)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8138d74b)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff813909f5)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff813adaad)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff813b4bc6)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff813cc735)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff813d22b7)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff83ec17cf)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/madvise.c (ffffffff813f5ef8)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/slub.c (ffffffff81427c43)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/kfence/core.c (ffffffff81430379)
Location: include/linux/atomic/atomic-instrumented.h:1426
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
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In mm/memcontrol.c (ffffffff8145b29d)
Location: include/linux/atomic/atomic-instrumented.h:1426
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
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81463e65)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff81498a5c)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff814a203f)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
```
```
In fs/file.c (ffffffff814a8799)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff83eca138)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff814dd7c6)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/coredump.c (ffffffff81517f28)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff8153d437)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81647f3a)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff816f09a8)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff816f522e)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff816f95e4)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff8173a9d5)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In io_uring/msg_ring.c (ffffffff81798c7d)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
```
```
In io_uring/rsrc.c (ffffffff817a1591)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/tty/tty_io.c (ffffffff81a4b32d)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/base/memory.c (ffffffff81b1705d)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_inc
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b6ae15)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/net/tun.c (ffffffff81bf3100)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/md-bitmap.c (ffffffff81d08654)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81db1da5)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81e51387)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/icmp.c (ffffffff81eed59f)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/ipmr.c (ffffffff81f1ec34)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff81f4c0f5)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81f50675)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a455)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81f83338)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81f8b17f)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81f90f6d)
Location: include/linux/atomic/atomic-instrumented.h:1426
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
Location: include/linux/atomic/atomic-instrumented.h:1426
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
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81f9f02e)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffffffff81faca6e)
Location: include/linux/atomic/atomic-instrumented.h:1426
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff81fc6618)
Location: include/linux/atomic/atomic-instrumented.h:1426
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096d46)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810f2460)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a56e6)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff8123589b)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff8124b0f2)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff8139175e)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff813b6b09)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
```
```
In mm/shmem.c (ffffffff813c0106)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff813c32f5)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff813e9bc9)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff813fea85)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
```
```
In mm/msync.c (ffffffff81406e7c)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff836e6fdf)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/madvise.c (ffffffff81428dbc)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/slub.c (ffffffff8145d1bb)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/kfence/core.c (ffffffff81465cf2)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In mm/memcontrol.c (ffffffff81490f0d)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8149997c)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff814cdafc)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff814d71cf)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
```
```
In fs/file.c (ffffffff814dd789)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff836ef178)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff81514026)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/coredump.c (ffffffff8154f825)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff81575713)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81680450)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff8172ae44)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8172f32e)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81733757)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff817770d5)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In io_uring/msg_ring.c (ffffffff817d998e)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/rsrc.c (ffffffff817e2799)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/tty/tty_io.c (ffffffff81a953cd)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/base/memory.c (ffffffff81b65dcd)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_inc
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbe232)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/net/tun.c (ffffffff81c4a372)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/md-bitmap.c (ffffffff81d717e4)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81e22348)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81eacbd3)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/icmp.c (ffffffff81f4cf5f)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/ipmr.c (ffffffff81f7e734)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff81fabed5)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81faffe5)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81fba140)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81fe364b)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81feb846)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81ff185d)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81fffb7b)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffffffff8200d47e)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff820272dd)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
```
In net/handshake/netlink.c (ffffffff82092685)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e2b6)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810fc030)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b51d6)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/audit_tree.c (ffffffff81264ff2)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff813bb4cc)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff813df9c9)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
```
```
In mm/shmem.c (ffffffff813e7740)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_falloc_wait
```
```
In mm/util.c (ffffffff813ede15)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff81414d37)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8142af23)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
```
```
In mm/msync.c (ffffffff8143352c)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff8391958f)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/slub.c (ffffffff814578bb)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/madvise.c (ffffffff814625ec)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/zswap.c (ffffffff814703e3)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/zswap.c:shrink_memcg_cb
  - mm/zswap.c:zswap_folio_swapin
```
```
In mm/kfence/core.c (ffffffff81494f70)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In mm/memcontrol.c (ffffffff814c087a)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff814c911d)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff8150043c)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff8150954f)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
```
```
In fs/file.c (ffffffff815101d9)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff839221c8)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff815484f6)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/backing-file.c (ffffffff81581864)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
```
```
In fs/coredump.c (ffffffff81585664)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff815ae070)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff816bc840)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff8176c964)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8176fcbc)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81774177)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff817b9305)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In io_uring/msg_ring.c (ffffffff8181dcae)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In drivers/tty/tty_io.c (ffffffff81ae7dab)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/base/memory.c (ffffffff81bb9c4d)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_inc
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c12982)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81cacccb)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
In drivers/net/tun.c (ffffffff81cffcf5)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d06fd7)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/skbuff.c (ffffffff81ed2ee4)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
```
```
In net/core/scm.c (ffffffff81ee0288)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81f6f690)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/icmp.c (ffffffff8201306f)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034313)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff82044ddf)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff820792f5)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8207d645)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff820875a1)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff820b1555)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff820b9511)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff820bf45c)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff820ce971)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffffffff820dc448)
Location: include/linux/atomic/atomic-instrumented.h:3561
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff820f67a1)
Location: include/linux/atomic/atomic-instrumented.h:3561
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
Location: include/linux/atomic/atomic-instrumented.h:3561
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f472c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffff800010115128)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffff800010197b00)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
```
In kernel/audit_tree.c (ffff8000101f5640)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/ring_buffer.c (ffff8000102186e0)
Location: include/asm-generic/atomic-long.h:158
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
In kernel/bpf/syscall.c (ffff8000102657d4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffff80001029f180)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/ring_buffer.c (ffff8000102a2838)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102b2910)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffff8000102ccb44)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffff8000102d3218)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffff8000102f04c0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffff8000102f0660)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffff8000102f4af8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffff8000103040a4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffff800010306f5c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/msync.c:__arm64_sys_msync
```
```
In mm/rmap.c (ffff80001030a288)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffff8000114588d4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffff80001031e188)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
```
```
In mm/swapfile.c (ffff8000103260e4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffff80001034b638)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffff8000103518b4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffff80001035fc2c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffff800010365d3c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_write
```
```
In mm/memory-failure.c (ffff8000103705b0)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffff8000103781b0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/select.c (ffff8000103a1e50)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffff8000103ac6ec)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In fs/file.c (ffff8000103b29f4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffff8000103e9494)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffff8000103f1b30)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In fs/io_uring.c (ffff800010403c48)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
```
```
In fs/proc/fd.c (ffff800010446fa0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffff8000105286fc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffff8000105adcec)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0824)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffff8000105e87fc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In block/genhd.c (ffff8000105faafc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In drivers/tty/tty_io.c (ffff800010852574)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffff8000109249ac)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffff8000109656dc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffff800010afad08)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffff800010bbde7c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffff800010bd2468)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffff800010c30c50)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffff800010c35f28)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffff800010ca4fc0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffff800010cee690)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffff800010cf0d58)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffff800010cf47b4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffff800010cfc76c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffff800010d20b1c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffff800010d26b50)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffff800010d2cb40)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffff800010d3a594)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffff800010d581d0)
Location: include/asm-generic/atomic-long.h:158
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
In kernel/fork.c (c0352f2c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (c036af64)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (c03e2e1c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/audit_tree.c (c043578c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/ring_buffer.c (c0458830)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_discard_commit
  - kernel/trace/ring_buffer.c:ring_buffer_lock_reserve
  - kernel/trace/ring_buffer.c:__rb_reserve_next
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_commit
  - kernel/trace/ring_buffer.c:rb_start_commit
  - kernel/trace/ring_buffer.c:rb_start_commit
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
  - kernel/trace/ring_buffer.c:rb_move_tail
```
```
In kernel/bpf/syscall.c (c04939bc)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_task_fd_query
```
```
In kernel/events/core.c (c04ceabc)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/ring_buffer.c (c04d2400)
Location: include/asm-generic/atomic-long.h:652
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
In kernel/events/uprobes.c (c04d4c50)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c04dfb68)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (c04e447c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (c04f67b0)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (c04fb1a0)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (c0513b8c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (c0513c30)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (c05167d4)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (c05228c8)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (c0524b90)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/rmap.c (c0526878)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (c05345a4)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:free_highmem_page
```
```
In mm/memblock.c (c1532858)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (c053827c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/swapfile.c (c053d92c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (c054f680)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/memcontrol.c (c055cc38)
Location: include/asm-generic/atomic-long.h:652
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
In mm/zsmalloc.c (c0560f70)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (c0563b04)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (c0584b6c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (c058d658)
Location: include/asm-generic/atomic-long.h:652
Inline: True
```
```
In fs/file.c (c0591cc0)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (c05c0888)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (c05c751c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (c05d7b30)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/proc/fd.c (c060bfb4)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (c06e1bdc)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
```
```
In security/integrity/ima/ima_queue.c (c075d3e4)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (c075feec)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (c0795174)
Location: include/asm-generic/atomic-long.h:652
Inline: True
```
```
In block/genhd.c (c07a5c88)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In drivers/tty/tty_io.c (c095d4c0)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (c0a08144)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (c0a3bbfc)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (c0bdb79c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (c0cda31c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (c0ced05c)
Location: include/asm-generic/atomic-long.h:652
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
In net/core/filter.c (c0d18648)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (c0d47a5c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (c0db18d0)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (c0df64ec)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (c0df7834)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (c0dfb4f4)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (c0e03be4)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (c0e25238)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e2bc2c)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (c0e30a10)
Location: include/asm-generic/atomic-long.h:652
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
In net/ipv6/mcast.c (c0e33954)
Location: include/asm-generic/atomic-long.h:652
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
In net/ipv6/tcp_ipv6.c (c0e3ad00)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (c0e3ca78)
Location: include/asm-generic/atomic-long.h:652
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (c0e5a040)
Location: include/asm-generic/atomic-long.h:652
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013a690)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (c00000000015d0d8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (c0000000001f7d0c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/audit_tree.c (c00000000026ac4c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/bpf/syscall.c (c00000000030a300)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (c0000000003585e8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c000000000368ba8)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (c00000000038a344)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (c000000000391c74)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (c0000000003b4f1c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (c0000000003b5004)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (c0000000003baa70)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (c0000000003d0e04)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (c0000000003d50a0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/rmap.c (c0000000003d9d08)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (c000000001382130)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (c0000000003f257c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/swapfile.c (c0000000003fc630)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (c00000000042ac64)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (c000000000437e8c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (c00000000044a9a8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (c00000000045af94)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (c000000000466774)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (c00000000046a8fc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (c00000000049b948)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (c0000000004a7968)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In fs/file.c (c0000000004ae974)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (c0000000004efe6c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (c0000000004f9438)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In fs/io_uring.c (c000000000510b18)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/proc/fd.c (c00000000055ce6c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (c0000000006731c4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (c00000000072c884)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (c000000000730524)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (c00000000077dacc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
```
```
In drivers/tty/tty_io.c (c0000000008f0dd4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (c0000000009c88d0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (c000000000a1bf68)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (c000000000be8d74)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (c000000000c976b0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (c000000000cb0aac)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (c000000000d299d8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (c000000000d2e0e0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (c000000000db8c80)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (c000000000e13328)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (c000000000e146d4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (c000000000e1a77c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (c000000000e24320)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (c000000000e4ef98)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c000000000e5787c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (c000000000e5e61c)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (c000000000e6d79c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (c000000000e93240)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffe0000d214e)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffe000128cd8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffe000168810)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/trace/ring_buffer.c (ffffffe000176afe)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/core.c (ffffffe0001ce75e)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_output_sample
```
```
In kernel/events/ring_buffer.c (ffffffe0001d146a)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffe0001eb544)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffe0001ee3ce)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffe000203e62)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffe000203f0c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffe000205c94)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffe000210948)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffe0002124de)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/msync.c:__se_sys_msync
```
```
In mm/rmap.c (ffffffe000214030)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffe000016f58)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffe000221234)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
```
```
In mm/swapfile.c (ffffffe000226440)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffe00023ccec)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/memcontrol.c (ffffffe000248c0e)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffe00024feaa)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffe00026a6fe)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffe000270cd6)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/inode.c:drop_nlink
```
```
In fs/file.c (ffffffe000276a1a)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffe00029dc84)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffe0002a4364)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffe0002b1350)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
```
In fs/proc/fd.c (ffffffe0002dcd6e)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffe00038bd76)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In security/integrity/ima/ima_queue.c (ffffffe0003f6064)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffe0003f83d8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffe000429796)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
```
```
In block/genhd.c (ffffffe000436e56)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - block/genhd.c:part_inc_in_flight
  - block/genhd.c:part_inc_in_flight
```
```
In drivers/tty/tty_io.c (ffffffe00052f80e)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffe0005a1aca)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffe0005d1faa)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffe0006ec5c2)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffe00074c646)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffe00075c970)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffe0007a6b5c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (ffffffe0008008da)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b856)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffe00083d0e0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffe0008405de)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffe00084700a)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffe000862b9c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffe000868b24)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffe00086cdc6)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffe000877238)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffe00088f410)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b307c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81129360)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff811788f2)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/bpf/syscall.c (ffffffff811da6b9)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff81212a35)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121de49)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81233f78)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81238518)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff81250ce3)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81250d83)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81254c3a)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126546d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8126955c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8126ccd8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828c86f2)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8127c4c3)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81283067)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812a2148)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a989f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b68bd)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812c0c03)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812c912d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812cac26)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812ed41c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812f4ebf)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In fs/file.c (ffffffff812f9030)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813258d7)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8132c32d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8133e22d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81372fd2)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81438517)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814ade5c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814b0b7f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff814e29b1)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8164a6fb)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff816f2e36)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171956f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff8184bca9)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff818c369d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818d4106)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81928907)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8192b35a)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff8198ef26)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff819ceb92)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff819d0115)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819d3905)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff819dacd7)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff819fa97b)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a0114f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a06287)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a111ec)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a29eb0)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810a19ac)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff8111bbf0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff8116ba92)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/bpf/syscall.c (ffffffff811cd479)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff812057af)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81210fff)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81226fe8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff8122b519)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff81243c23)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff81243cc3)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff81247a7a)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8125788d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff8125b84c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8125ed14)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828c0e17)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8126e373)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81274ff4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff81293c28)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8129b1ff)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812a7a8d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812b1c7b)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812ba16d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812bbbb0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812de04c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812e5adf)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In fs/file.c (ffffffff812e9c50)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff81316477)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8131d691)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8132eeed)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81363aa2)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81428f87)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149e87c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814a159f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff814d3341)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162ab4b)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff816ccf36)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f29df)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/net/vxlan.c (ffffffff81772f72)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
```
```
In drivers/md/md-bitmap.c (ffffffff818132c9)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8187d5dd)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff8188df96)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff818e26b7)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff818e510a)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff819489e6)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b956)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff8198ced5)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff819906c5)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81997a97)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff819b773b)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff819bdf0f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff819c3047)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff819cdfac)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819e70a0)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810b25dc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff81127080)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff811766c2)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/bpf/syscall.c (ffffffff811d8489)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff812107d5)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121bbe9)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81231d18)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff812362b8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff8124ea83)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff8124eb23)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812529da)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8126320d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812672fc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8126aa78)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828db472)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8127a263)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81280e77)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff8129ff58)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812a76af)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812b46cd)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812bea13)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812c6f3d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812c8a36)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812eb22c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff812f2ccf)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In fs/file.c (ffffffff812f6e40)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813233a7)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff81329dfd)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_insert
```
```
In fs/io_uring.c (ffffffff8133bcfd)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81370aa2)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff814346b7)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814a9efc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814acc0f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff814dea41)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81678abb)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff81720516)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8175833f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff8189b2d9)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8191469d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81925106)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff81979a97)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8197c4ea)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff819f97c6)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81a39612)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a3ab95)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a3e385)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a45757)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a653fb)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a6bbcf)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a70d07)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a7bc6c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a95a60)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sys.c (ffffffff810babdc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/kcmp.c (ffffffff811336c8)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
```
In kernel/audit_tree.c (ffffffff81183f92)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In kernel/bpf/syscall.c (ffffffff811e6817)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/events/uprobes.c (ffffffff8121f6e6)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8122ac47)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81241178)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
```
```
In mm/shmem.c (ffffffff81246593)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_fault
```
```
In mm/workingset.c (ffffffff8125e3fc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
```
```
In mm/prfile.c (ffffffff8125e4a3)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812623aa)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff81272bcd)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81276c9c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/msync.c:__ia32_sys_msync
  - mm/msync.c:__x64_sys_msync
```
```
In mm/rmap.c (ffffffff8127a3e1)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/memblock.c (ffffffff828e0893)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff81289e43)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
```
In mm/swapfile.c (ffffffff81290b84)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_page_of_type
```
```
In mm/slub.c (ffffffff812b0098)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812b79b5)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/khugepaged.c (ffffffff812c507e)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812cf483)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In mm/zsmalloc.c (ffffffff812d62ab)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In mm/userfaultfd.c (ffffffff812d972e)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/select.c (ffffffff812fc21c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff813043df)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In fs/file.c (ffffffff813080b0)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:__close_fd_get_file
  - fs/file.c:dup_fd
```
```
In fs/notify/mark.c (ffffffff813350f7)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
```
In fs/eventpoll.c (ffffffff8133c8c4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
```
```
In fs/io_uring.c (ffffffff8134eead)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
```
```
In fs/proc/fd.c (ffffffff81384482)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8144b7d9)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/integrity/ima/ima_queue.c (ffffffff814c294c)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff814c565f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff814f78b1)
Location: include/asm-generic/atomic-long.h:158
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff816926f4)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff8173b8d6)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8177381f)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_mmap
```
```
In drivers/md/md-bitmap.c (ffffffff818b7439)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff8193586d)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff819465e6)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/core/gro_cells.c (ffffffff8199bfb9)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/compat.c (ffffffff8199ea3a)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
```
In net/ipv4/icmp.c (ffffffff81a03ab6)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81a45042)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81a45e15)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81a49e45)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81a51427)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81a7196e)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81a781df)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81a7d317)
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
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
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81a884bc)
Location: include/asm-generic/atomic-long.h:158
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81aa26a0)
Location: include/asm-generic/atomic-long.h:158
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
