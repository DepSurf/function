# Function: <code>raw_atomic_long_inc</code>

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
In arch/x86/kernel/nmi.c (ffffffff8213de6a)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096d46)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810f2460)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a56e6)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff8123589b)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff8124b0f2)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff8139175e)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff813b6b09)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
```
```
In mm/shmem.c (ffffffff813c0106)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff813c32f5)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff813e9bc9)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff813fea85)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
```
```
In mm/msync.c (ffffffff81406e7c)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff836e6fdf)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/madvise.c (ffffffff81428dbc)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/slub.c (ffffffff8145d1bb)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/kfence/core.c (ffffffff81465cf2)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In mm/memcontrol.c (ffffffff81490f0d)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff8149997c)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff814cdafc)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff814d71cf)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
```
```
In fs/file.c (ffffffff814dd789)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff836ef178)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff81514026)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/coredump.c (ffffffff8154f825)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff81575713)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81680450)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff8172ae44)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8172f32e)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81733757)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff817770d5)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In io_uring/msg_ring.c (ffffffff817d998e)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/rsrc.c (ffffffff817e2799)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/tty/tty_io.c (ffffffff81a953cd)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/base/memory.c (ffffffff81b65dcd)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_inc
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbe232)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/net/tun.c (ffffffff81c4a372)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/md-bitmap.c (ffffffff81d717e4)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81e22348)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81eacbd3)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/icmp.c (ffffffff81f4cf5f)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/ipmr.c (ffffffff81f7e734)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff81fabed5)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81faffe5)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81fba140)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81fe364b)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81feb846)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81ff185d)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81fffb7b)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffffffff8200d47e)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff820272dd)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
```
```
In net/handshake/netlink.c (ffffffff82092685)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e2b6)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810fc030)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b51d6)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/audit_tree.c (ffffffff81264ff2)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff813bb4cc)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff813df9c9)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
```
```
In mm/shmem.c (ffffffff813e7740)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/shmem.c:shmem_falloc_wait
```
```
In mm/util.c (ffffffff813ede15)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/memory.c (ffffffff81414d37)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff8142af23)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/mmap.c:copy_vma
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__split_vma
```
```
In mm/msync.c (ffffffff8143352c)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff8391958f)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/slub.c (ffffffff814578bb)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/madvise.c (ffffffff814625ec)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/zswap.c (ffffffff814703e3)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/zswap.c:shrink_memcg_cb
  - mm/zswap.c:zswap_folio_swapin
```
```
In mm/kfence/core.c (ffffffff81494f70)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In mm/memcontrol.c (ffffffff814c087a)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff814c911d)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff8150043c)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff8150954f)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
```
```
In fs/file.c (ffffffff815101d9)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff839221c8)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff815484f6)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/backing-file.c (ffffffff81581864)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
```
```
In fs/coredump.c (ffffffff81585664)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff815ae070)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff816bc840)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff8176c964)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8176fcbc)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff81774177)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff817b9305)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In io_uring/msg_ring.c (ffffffff8181dcae)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In drivers/tty/tty_io.c (ffffffff81ae7dab)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/base/memory.c (ffffffff81bb9c4d)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_inc
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c12982)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81cacccb)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/virtio_net.c (ffffffff81d06fd7)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/skbuff.c (ffffffff81ed2ee4)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_try_coalesce
```
```
In net/core/scm.c (ffffffff81ee0288)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81f6f690)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/icmp.c (ffffffff8201306f)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034313)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff82044ddf)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff820792f5)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff8207d645)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff820875a1)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff820b1555)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff820b9511)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff820bf45c)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff820ce971)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffffffff820dc448)
Location: include/linux/atomic/atomic-long.h:495
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff820f67a1)
Location: include/linux/atomic/atomic-long.h:495
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
Location: include/linux/atomic/atomic-long.h:495
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
