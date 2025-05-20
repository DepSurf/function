# Function: <code>arch_atomic_long_inc</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073706)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
```
In kernel/fork.c (ffffffff810b4eab)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff8113d554)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/audit_tree.c (ffffffff811baa72)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff8129d7d0)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff812b64dc)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff812bda26)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff812c0605)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff812d6fe3)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff812dd302)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff812ef2fb)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff812f3ce4)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff832da26c)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_free_late
```
```
In mm/madvise.c (ffffffff8130d104)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
```
```
In mm/slub.c (ffffffff81335025)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff8133c959)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff8135bf09)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81360c84)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
  - mm/memory-failure.c:page_handle_poison
```
```
In mm/zsmalloc.c (ffffffff81365488)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
```
```
In fs/select.c (ffffffff8138cc4c)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff813949cf)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
```
```
In fs/file.c (ffffffff81399bd9)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff813c7fac)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
```
```
In fs/io_uring.c (ffffffff813e7379)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_file_register
  - fs/io_uring.c:__io_sqe_files_scm
```
```
In fs/proc/fd.c (ffffffff8142e30e)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8150c8cb)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff81597844)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff81598cdc)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff8159c5b5)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff815d21d7)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - block/blk-ioc.c:get_task_io_context
```
```
In drivers/tty/tty_io.c (ffffffff817b76ff)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/block/loop.c (ffffffff8186e03e)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/net/tun.c (ffffffff8191024a)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81a8d015)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/core/dev.c (ffffffff81a9f95d)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/core/gro_cells.c (ffffffff81b04809)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/ipv4/icmp.c (ffffffff81b94387)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/xfrm/xfrm_device.c (ffffffff81be3364)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/unix/af_unix.c (ffffffff81be6315)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81bead65)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81bf38be)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81c17bb0)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81c1e85a)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81c238b1)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81c306d8)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81c5105c)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810c954a)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81160946)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff811da1a9)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff811eddd2)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff812f4886)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8131197e)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff81319799)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff8131d0c5)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff81336843)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff8133cfec)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff81352729)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff81357b11)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff8348f2fc)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/madvise.c (ffffffff813786e6)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/slub.c (ffffffff813ad46c)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:allocate_slab
```
```
In mm/kfence/core.c (ffffffff813afd79)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff813d5802)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff813d8b3e)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff8140df2c)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff81416baf)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
```
```
In fs/file.c (ffffffff8141c689)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff83495644)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff8144efd8)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/coredump.c (ffffffff81484a32)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff814a7a37)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff8159e87a)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff81639348)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff8163d6fe)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff816415f4)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff8167dd85)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In io_uring/io_uring.c (ffffffff816d3cc2)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff818f2cfa)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819edad8)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/net/tun.c (ffffffff81a63f18)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/vfio/vfio.c (ffffffff81a76e56)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_open
```
```
In drivers/md/md-bitmap.c (ffffffff81b6c580)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81c02905)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81c95827)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/icmp.c (ffffffff81d25c46)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/unix/af_unix.c (ffffffff81d7ed65)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81d83015)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c495)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81db3998)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81dbb0aa)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81dc07e2)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81dcde16)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81df2508)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
```
```
In kernel/fork.c (ffffffff810e6aa6)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff81193e86)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:prb_reserve
```
```
In kernel/cgroup/misc.c (ffffffff8121f729)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
```
In kernel/audit_tree.c (ffffffff81234402)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tree_lookup
```
```
In mm/filemap.c (ffffffff8135e9c6)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81384fa9)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/shmem.c (ffffffff8138d74b)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/util.c (ffffffff813909f5)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/util.c:vma_set_file
```
```
In mm/prfile.c (ffffffff813adaad)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/prfile.c:vma_do_get_file
  - mm/prfile.c:vma_do_get_file
```
```
In mm/memory.c (ffffffff813b4bc6)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory.c:fault_dirty_shared_page
```
```
In mm/mmap.c (ffffffff813cc735)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:mmap_region
```
```
In mm/msync.c (ffffffff813d22b7)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/memblock.c (ffffffff83ec17cf)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_late
```
```
In mm/madvise.c (ffffffff813f5ef8)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
```
In mm/slub.c (ffffffff81427c43)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/kfence/core.c (ffffffff81430379)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
```
```
In mm/memcontrol.c (ffffffff8145b29d)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup
```
```
In mm/memory-failure.c (ffffffff81463e65)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:action_result
  - mm/memory-failure.c:page_handle_poison
```
```
In fs/select.c (ffffffff81498a5c)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/select.c:__pollwait
```
```
In fs/inode.c (ffffffff814a203f)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
```
```
In fs/file.c (ffffffff814a8799)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/file.c:f_dupfd
  - fs/file.c:receive_fd
  - fs/file.c:do_dup2
  - fs/file.c:dup_fd
```
```
In fs/init.c (ffffffff83eca138)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/init.c:init_dup
```
```
In fs/notify/mark.c (ffffffff814dd7c6)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/notify/mark.c:__fsnotify_recalc_mask
```
```
In fs/coredump.c (ffffffff81517f28)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/coredump.c:dump_vma_snapshot
```
```
In fs/proc/fd.c (ffffffff8153d437)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - fs/proc/fd.c:seq_show
```
```
In ipc/shm.c (ffffffff81647f3a)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
```
```
In security/landlock/fs.c (ffffffff816f09a8)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - security/landlock/fs.c:release_inode
```
```
In security/integrity/ima/ima_queue.c (ffffffff816f522e)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_api.c (ffffffff816f95e4)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
```
In block/blk-ioc.c (ffffffff8173a9d5)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_find_get_icq
```
```
In io_uring/msg_ring.c (ffffffff81798c7d)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
```
```
In io_uring/rsrc.c (ffffffff817a1591)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - io_uring/rsrc.c:__io_scm_file_account
```
```
In drivers/tty/tty_io.c (ffffffff81a4b32d)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:redirected_tty_write
```
```
In drivers/base/memory.c (ffffffff81b1705d)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/base/memory.c:memblk_nr_poison_inc
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b6ae15)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/net/tun.c (ffffffff81bf3100)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/md/md-bitmap.c (ffffffff81d08654)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In net/core/scm.c (ffffffff81db1da5)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/core/scm.c:scm_fp_dup
```
```
In net/sched/sch_generic.c (ffffffff81e51387)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dev_watchdog
```
```
In net/ipv4/icmp.c (ffffffff81eed59f)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
  - net/ipv4/icmp.c:icmp_out_count
```
```
In net/ipv4/ipmr.c (ffffffff81f1ec34)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:reg_vif_xmit
```
```
In net/unix/af_unix.c (ffffffff81f4c0f5)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
```
```
In net/unix/garbage.c (ffffffff81f50675)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/unix/garbage.c:inc_inflight
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a455)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff81f83338)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (ffffffff81f8b17f)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/icmp.c (ffffffff81f90f6d)
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
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
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ping.c (ffffffff81f9f02e)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_sendmsg
```
```
In net/ipv6/ip6mr.c (ffffffff81faca6e)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/packet/af_packet.c (ffffffff81fc6618)
Location: include/linux/atomic/atomic-long.h:159
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
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
