# Function: <code>__hlist_del</code>

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
In arch/x86/kernel/kprobes/core.c (ffffffff8105f3f7)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff810638fa)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/user.c (ffffffff8108c7ce)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8109a033)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:put_unbound_pool
```
```
In kernel/pid.c (ffffffff8109dfb2)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
  - kernel/pid.c:__change_pid
```
```
In kernel/sched/core.c (ffffffff810a4a85)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/time/timer.c (ffffffff810eb9fd)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/time/timer.c:detach_if_pending
  - kernel/time/timer.c:migrate_timer_list
  - kernel/time/timer.c:run_timer_softirq
```
```
In kernel/time/posix-timers.c (ffffffff810f10d2)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup.c (ffffffff81114c04)
Location: include/linux/list.h:614
Inline: True
```
```
In kernel/kprobes.c (ffffffff8112cc6e)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:cleanup_rp_inst
```
```
In kernel/trace/ftrace.c (ffffffff81140460)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:free_ftrace_hash
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
```
```
In kernel/trace/trace_output.c (ffffffff81154164)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811629bb)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/hashtab.c (ffffffff81177558)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
```
```
In kernel/events/core.c (ffffffff811786b0)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff81189725)
Location: include/linux/list.h:614
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff811e3d33)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff811e4ed0)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:run_store
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__ksm_exit
```
```
In mm/huge_memory.c (ffffffff811f430e)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - mm/huge_memory.c:collect_mm_slot
  - mm/huge_memory.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8120e977)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812236d5)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:d_delete
```
```
In fs/inode.c (ffffffff812266f6)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8122be8b)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:attach_recursive_mnt
```
```
In fs/fs_pin.c (ffffffff81241f32)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/inode_mark.c (ffffffff8124fed0)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
```
```
In fs/notify/mark.c (ffffffff81250623)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
```
```
In fs/notify/vfsmount_mark.c (ffffffff81250c9c)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
```
```
In fs/locks.c (ffffffff8125f0e2)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_unlink_lock_ctx
```
```
In fs/quota/dquot.c (ffffffff81271498)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:dquot_disable
```
```
In fs/fat/inode.c (ffffffff812fb4ec)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff8130b611)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff81340216)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff8139d9ed)
Location: include/linux/list.h:614
Inline: True
```
```
In block/elevator.c (ffffffff813b38f5)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff813bec99)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff813d69b7)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff813d84bb)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81505238)
Location: include/linux/list.h:614
Inline: True
```
```
In drivers/net/tun.c (ffffffff815edfca)
Location: include/linux/list.h:614
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816e45fc)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_reparent
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:__clk_put
```
```
In net/core/dev.c (ffffffff81713942)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:dev_change_name
```
```
In net/core/flow.c (ffffffff8173466e)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/core/flow.c:__flow_cache_shrink
  - net/core/flow.c:flow_cache_flush_tasklet
```
```
In net/sched/sch_api.c (ffffffff817426f5)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/act_api.c (ffffffff817474fb)
Location: include/linux/list.h:614
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81749f07)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81762441)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81763639)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177ab17)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff817843bb)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/devinet.c (ffffffff8178f7af)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81799ade)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8179c44c)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff817a0c5e)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1c6f)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b0e2c)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff817b8cd8)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff817bfd49)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/addrconf.c (ffffffff817cdf4c)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff817d2726)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/packet/af_packet.c (ffffffff8180586e)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In arch/x86/events/amd/uncore.c (ffffffff81008da4)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f1fc)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81063538)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/user.c (ffffffff8108f83e)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8109e22a)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810a170f)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
  - kernel/pid.c:free_pid
```
```
In kernel/sched/core.c (ffffffff810a81d5)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/time/timer.c (ffffffff810f5926)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff810f80e2)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup.c (ffffffff81fab410)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8113529b)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8114c902)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:free_ftrace_hash
```
```
In kernel/trace/trace_output.c (ffffffff8115d374)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff8116d18b)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/hashtab.c (ffffffff81186afd)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In kernel/events/core.c (ffffffff81188b50)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff8119be05)
Location: include/linux/list.h:614
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff812027d3)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff81203d21)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/khugepaged.c (ffffffff812196ee)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812353aa)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8124a6f1)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff8124edb6)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8125667f)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff8126a282)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/inode_mark.c (ffffffff81278630)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
```
```
In fs/notify/mark.c (ffffffff81278c97)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
```
```
In fs/notify/vfsmount_mark.c (ffffffff8127949c)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
```
```
In fs/locks.c (ffffffff8128aba8)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In fs/quota/dquot.c (ffffffff8129fe1f)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff8132f1dc)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff8133f877)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff813758b6)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff813da94d)
Location: include/linux/list.h:614
Inline: True
```
```
In block/elevator.c (ffffffff813f7855)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff81402c69)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff8141c674)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff8141e1fd)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815569a8)
Location: include/linux/list.h:614
Inline: True
```
```
In drivers/net/tun.c (ffffffff8164d0ba)
Location: include/linux/list.h:614
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8174d27a)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In net/core/dev.c (ffffffff8177b5a4)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/flow.c (ffffffff817a0d2a)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_tasklet
  - net/core/flow.c:__flow_cache_shrink
```
```
In net/sched/sch_api.c (ffffffff817af5a5)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/act_api.c (ffffffff817b46c0)
Location: include/linux/list.h:614
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817b6e17)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce570)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfae9)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea37f)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff817f197b)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff817f3f59)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/devinet.c (ffffffff817fcd4f)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81807781)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8180a05d)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff8180ecbb)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/inet_fragment.c (ffffffff8180f931)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181dd7c)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81826bab)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff8182da08)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8183b3ec)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff818407a2)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/packet/af_packet.c (ffffffff8187642e)
Location: include/linux/list.h:614
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In arch/x86/events/amd/uncore.c (ffffffff81008de4)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106229c)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff810669f8)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff810893da)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810947be)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810a2d8a)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810a67cf)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
  - kernel/pid.c:free_pid
```
```
In kernel/ucount.c (ffffffff810ad61f)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810ae075)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/time/timer.c (ffffffff810fc966)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff81105a72)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup.c (ffffffff81fe7686)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8113f01b)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811567f2)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:ftrace_hash_move
  - kernel/trace/ftrace.c:free_ftrace_hash
```
```
In kernel/trace/trace_output.c (ffffffff81167de4)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff8117845b)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/hashtab.c (ffffffff8119388f)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
```
```
In kernel/events/core.c (ffffffff81197f30)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff811ab7e5)
Location: include/linux/list.h:630
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff81214613)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff81215d41)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:remove_rmap_item_from_tree
```
```
In mm/khugepaged.c (ffffffff8122bc6e)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81247f4a)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8125d671)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81261dc6)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8126a1fb)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff8127d232)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/inode_mark.c (ffffffff8128c314)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_destroy_inode_mark
```
```
In fs/notify/mark.c (ffffffff8128c8c7)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
```
```
In fs/notify/vfsmount_mark.c (ffffffff8128d060)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/notify/vfsmount_mark.c:fsnotify_destroy_vfsmount_mark
```
```
In fs/locks.c (ffffffff8129f938)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In fs/quota/dquot.c (ffffffff812b530c)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/fat/inode.c (ffffffff81344f3c)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff813555fb)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff8138c1e6)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff813f228d)
Location: include/linux/list.h:630
Inline: True
```
```
In block/elevator.c (ffffffff814113e6)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff8141c999)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff81437bb4)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff814397bd)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffff81535aea)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815831a8)
Location: include/linux/list.h:630
Inline: True
```
```
In drivers/net/tun.c (ffffffff8167edfa)
Location: include/linux/list.h:630
Inline: True
```
```
In net/core/dev.c (ffffffff817a8c14)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/flow.c (ffffffff817cf95a)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_tasklet
  - net/core/flow.c:__flow_cache_shrink
```
```
In net/sched/sch_api.c (ffffffff817dec95)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/act_api.c (ffffffff817e3f70)
Location: include/linux/list.h:630
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff817e6897)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fe380)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff8d9)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818b74)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff818226fb)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81825169)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/devinet.c (ffffffff8182dcaf)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff8183880e)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8183b16d)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff818401e9)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/inet_fragment.c (ffffffff81840e81)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184f5fc)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818583bb)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff8185f4cc)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8186cdca)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81872422)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/packet/af_packet.c (ffffffff818aa92e)
Location: include/linux/list.h:630
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In arch/x86/events/amd/uncore.c (ffffffff81008b34)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810611c2)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81065d08)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff81086102)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810918af)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810a00bd)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810a373f)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
  - kernel/pid.c:free_pid
```
```
In kernel/ucount.c (ffffffff810aa1f8)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810aab25)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/time/timer.c (ffffffff810fedb6)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff81107c62)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff820c7c11)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff81142d34)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81159bde)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff8116aff4)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff8117b14b)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/events/core.c (ffffffff8119fa50)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff811b2c55)
Location: include/linux/list.h:643
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8121fa93)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8122143b)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff8123779e)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8125375a)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8126b04f)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff8126f686)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff81277a14)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff8128adc2)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff8129964e)
Location: include/linux/list.h:643
Inline: True
```
```
In fs/locks.c (ffffffff812ae7a8)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In fs/quota/dquot.c (ffffffff812c1af7)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffffffff812d43e6)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff813599ac)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff8136a1fb)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff813a1f36)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff813fe57e)
Location: include/linux/list.h:643
Inline: True
```
```
In block/elevator.c (ffffffff8141eee1)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff8142a8c9)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff81445344)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff81446fbe)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffff81548e7a)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815975f1)
Location: include/linux/list.h:643
Inline: True
```
```
In drivers/dax/super.c (ffffffff8163d38b)
Location: include/linux/list.h:643
Inline: True
```
```
In drivers/net/tun.c (ffffffff816940da)
Location: include/linux/list.h:643
Inline: True
```
```
In net/core/dev.c (ffffffff817c72b4)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/flow.c (ffffffff817eed62)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_tasklet
  - net/core/flow.c:__flow_cache_shrink
```
```
In net/sched/sch_api.c (ffffffff817fe2c5)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/act_api.c (ffffffff81803936)
Location: include/linux/list.h:643
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff81806696)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181e754)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181faf9)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81839357)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff8184334b)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81845ef4)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff8184f17f)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff8185a14e)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8185ca29)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81861833)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/inet_fragment.c (ffffffff81862730)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff818730dc)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8187c227)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff81882d7e)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff818916fd)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81897192)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f2ae)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff818d143f)
Location: include/linux/list.h:643
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In arch/x86/events/amd/uncore.c (ffffffff81008d54)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105b230)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81065011)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a2dd)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff8108cd83)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff8109873f)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810a6ddb)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810a9f2f)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810b0a58)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810b1835)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff81103174)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_all
  - kernel/livepatch/shadow.c:klp_shadow_free
```
```
In kernel/time/timer.c (ffffffff81109b35)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff81112de2)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff826d028f)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8114f9e4)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811666de)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff811780d4)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811889d8)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/events/core.c (ffffffff811b33c0)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff811c68a5)
Location: include/linux/list.h:644
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8123aca6)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8123c74b)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff81256b2e)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812757dd)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8128d8cf)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81291fa6)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8129a454)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff812ad902)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff812bc9be)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/locks.c (ffffffff812d2198)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In fs/quota/dquot.c (ffffffff812e591c)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffffffff812f8c16)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff8137e6bc)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff8138edab)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff813c7d36)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff81426b3e)
Location: include/linux/list.h:644
Inline: True
```
```
In block/elevator.c (ffffffff814499bd)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff81455ab9)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff81471e14)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff81473ba1)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffff815ac3ea)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff815fc231)
Location: include/linux/list.h:644
Inline: True
```
```
In drivers/dax/super.c (ffffffff816a60cb)
Location: include/linux/list.h:644
Inline: True
```
```
In drivers/net/tun.c (ffffffff816fe0da)
Location: include/linux/list.h:644
Inline: True
```
```
In net/core/dev.c (ffffffff81840e94)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/sched/sch_api.c (ffffffff8187bed5)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/netlink/af_netlink.c (ffffffff818853d6)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189d674)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189ea59)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8b00)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff818c2d1b)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818c5924)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff818cedaf)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff818da06e)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff818dc919)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff818e194d)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2855)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_worker
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f3aec)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff818fcf57)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff8190512e)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8191332d)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819186c6)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff8191a9fe)
Location: include/linux/list.h:644
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff8192189e)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff8195635f)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In arch/x86/events/amd/uncore.c (ffffffff81008fca)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8105e174)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81067bb5)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff8106cf54)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/cpu.c (ffffffff8109077d)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff8109be85)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810acca8)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810b0b66)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810b786b)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810b87ec)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff8110b6cc)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff81115151)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff8111e8da)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff826fa9ce)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8115e528)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811753f5)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff811872eb)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff81197e50)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/sockmap.c (ffffffff811d02e2)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sock_hash_delete_elem
  - kernel/bpf/sockmap.c:sock_hash_free
  - kernel/bpf/sockmap.c:bpf_tcp_close
```
```
In kernel/events/core.c (ffffffff811d2b28)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff811e6ded)
Location: include/linux/list.h:644
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8125e06b)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8125fcdf)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff8127ab01)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8129cae8)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812b4bbb)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812b930d)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812c04af)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff812d56b6)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff812e5562)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/locks.c (ffffffff812fe64c)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
```
In fs/quota/dquot.c (ffffffff81312f9d)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffffffff81326512)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff813af310)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff813bde57)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff813f7395)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff81459a3d)
Location: include/linux/list.h:644
Inline: True
```
```
In block/elevator.c (ffffffff8147c6be)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff81488efd)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff814a5bb8)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff814a8016)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffff815e434d)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816355b3)
Location: include/linux/list.h:644
Inline: True
```
```
In drivers/dax/super.c (ffffffff816e1e7e)
Location: include/linux/list.h:644
Inline: True
```
```
In drivers/net/tun.c (ffffffff8173c2e4)
Location: include/linux/list.h:644
Inline: True
```
```
In net/core/dev.c (ffffffff81890ec3)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/sched/sch_api.c (ffffffff818ce76d)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/netlink/af_netlink.c (ffffffff818d8dce)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2357)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f34b1)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190dfc0)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff8191880f)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8191d999)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff819251f2)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81930b22)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff819334f1)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81938455)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a400)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819539de)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff8195a77b)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/addrconf.c (ffffffff8196ab1c)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff8196ff0f)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff81971896)
Location: include/linux/list.h:644
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81979cc7)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff819b1789)
Location: include/linux/list.h:644
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In arch/x86/events/amd/uncore.c (ffffffff8100960a)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81063e04)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106da75)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81073124)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff810940f7)
Location: include/linux/list.h:697
Inline: True
```
```
In kernel/cpu.c (ffffffff8109883d)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810a4090)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810b6528)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810b9c3f)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810c096b)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810c190c)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff81116ebc)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff81120791)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff8112a0aa)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828b18ca)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8116b0a0)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81183035)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff81194c5b)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811a5fa0)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/events/core.c (ffffffff811e2e28)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff811f7a1d)
Location: include/linux/list.h:697
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff812728ea)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8127441f)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff8128f111)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812b1ca8)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812c9fcb)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812ce4fd)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812d56ff)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff812eaa86)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff812fa1af)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/crypto/keyinfo.c (ffffffff81311054)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In fs/locks.c (ffffffff8131408e)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81329f2d)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffffffff8133d3ca)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff813c87b0)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff813d7497)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff81412e45)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff81476f8d)
Location: include/linux/list.h:697
Inline: True
```
```
In block/elevator.c (ffffffff8149a6ae)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814a2d9d)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff814bf891)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff814c1cc0)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffff815fe73d)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81653883)
Location: include/linux/list.h:697
Inline: True
```
```
In drivers/dax/super.c (ffffffff8170529e)
Location: include/linux/list.h:697
Inline: True
```
```
In drivers/net/tun.c (ffffffff8175fc24)
Location: include/linux/list.h:697
Inline: True
```
```
In net/core/dev.c (ffffffff818b14a3)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff818f3418)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/sch_api.c (ffffffff818f99bd)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/netlink/af_netlink.c (ffffffff819055be)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191fd57)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920fd1)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c3b0)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff81946fdf)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8194c249)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81954002)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff8195ffa2)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff819629e1)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81967e5c)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c384)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff8198638e)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff8198f46b)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff81993e66)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff8199faec)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a5b2f)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff819a8966)
Location: include/linux/list.h:697
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff819af8b7)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff819e8b69)
Location: include/linux/list.h:697
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In arch/x86/events/amd/uncore.c (ffffffff81009aee)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810674c7)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071bad)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81076d85)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff81098af4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109cdfc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810a8d74)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810bc337)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810bfb4e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810c6a73)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810c7a0c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff8112113c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff8112b07c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff811349d9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828ca5d4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff81177f2c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8118fdb9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff811a294b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b3ea0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/events/core.c (ffffffff811f9fd8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff8120f85d)
Location: include/linux/list.h:757
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8128dea9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8129058f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff812a99d7)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812cea38)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812e6a4e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812eb3dd)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812f3894)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff813094f9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff8131abaf)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/crypto/keyinfo.c (ffffffff813383d3)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In fs/locks.c (ffffffff8133b981)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81351a9c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffffffff813656e1)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff813f3340)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff81401de9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff814408d5)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff814a4c99)
Location: include/linux/list.h:757
Inline: True
```
```
In block/elevator.c (ffffffff814c8787)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814d0e4d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff814ee0cb)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff814f0372)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffff81630dc2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81688281)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/dax/super.c (ffffffff8173f10e)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/net/tun.c (ffffffff8179d334)
Location: include/linux/list.h:757
Inline: True
```
```
In net/core/dev.c (ffffffff818fe254)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff819458ec)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81952c7c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff819591ad)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/netlink/af_netlink.c (ffffffff8196674e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982667)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819839a1)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a07e4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff819ab65f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819b0c79)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff819b8a62)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff819c49a7)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff819c812d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff819cdfe9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/nexthop.c (ffffffff819d527f)
Location: include/linux/list.h:757
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e56b0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819f01b1)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff819fac7d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff819ff8f6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81a0bdd2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a120a1)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff81a16466)
Location: include/linux/list.h:757
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1da08)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81a58edb)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a747c3)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/events/amd/uncore.c (ffffffff81009ede)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067e07)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81072b5a)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81077dd5)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff8109f0b6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a334c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810af344)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c25f6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810c5f1f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810cfb43)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810d0aec)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff8112d75c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff8113701c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff811409ec)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828d2ad2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff81183e28)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8119bd89)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff811ae34b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811bf4d0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff811ff273)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff812070a8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff8121ce8d)
Location: include/linux/list.h:757
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8129dd9f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff812a030f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff812baf47)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812e04b8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812f869e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812fcf1d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff81305459)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff8131c569)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff8132d71f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e560)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81353ed1)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81369e1c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffffffff8137d971)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff8140d220)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff8141bcd9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff8145a1a5)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff814bf929)
Location: include/linux/list.h:757
Inline: True
```
```
In block/elevator.c (ffffffff814e18a7)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814ea20a)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff8150752b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff8150981f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffff81652b82)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816aa921)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/dax/super.c (ffffffff8176331e)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/net/tun.c (ffffffff817c0dd4)
Location: include/linux/list.h:757
Inline: True
```
```
In net/core/dev.c (ffffffff81930584)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff8197a90c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81988fcc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff8198f64d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff819953e4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff8199d1de)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b8ee3)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba191)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d73b8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff819e232f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819e7bcc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff819ef762)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff819fb547)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff819fecdd)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a04bab)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/nexthop.c (ffffffff81a0bddf)
Location: include/linux/list.h:757
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c6e0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a27081)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff81a3190d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff81a364d6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81a42a82)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a48cc1)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff81a4d0a6)
Location: include/linux/list.h:757
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a54638)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81a8efeb)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81aab179)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/events/amd/uncore.c (ffffffff8100b0b2)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8106eeed)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81079bb2)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f042)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:kvm_async_pf_queue_task
```
```
In kernel/fork.c (ffffffff810a612e)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810aa384)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810b704d)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c8abe)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810cdc9e)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810d9a3f)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810da905)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff8113bed9)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff81145cdb)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff8114fbaf)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff82cf348d)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff81195e4f)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:do_unoptimize_kprobes
```
```
In kernel/trace/ftrace.c (ffffffff811b0e62)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff811c6714)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d8dd8)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/trampoline.c (ffffffff8121f154)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/bpf/devmap.c (ffffffff8122661c)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_remove_netdev
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff812305b0)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff81249205)
Location: include/linux/list.h:806
Inline: True
```
```
In kernel/watch_queue.c (ffffffff8124d43a)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff812d1c3b)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mn_hlist_release
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff812d6c23)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff812efe05)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81317171)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff813315e8)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81335b56)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff81340997)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff813562a4)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff813677ba)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/io_uring.c (ffffffff8137eb14)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/io_uring.c:__io_poll_remove_one
  - fs/io_uring.c:io_async_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813945cc)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8139abbc)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff813af28e)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff813b9e88)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813be957)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff813c8c17)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff8145af4c)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff8146a96f)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff814adac6)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In crypto/algapi.c (ffffffff8151fc9d)
Location: include/linux/list.h:806
Inline: True
```
```
In block/elevator.c (ffffffff815406b0)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff815491a6)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff81568b2c)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - block/bsg.c:bsg_put_device
```
```
In block/blk-cgroup.c (ffffffff81569c31)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/keyslot-manager.c (ffffffff815816e7)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/clk/clk.c (ffffffff8170271a)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175d398)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/dax/super.c (ffffffff818231bb)
Location: include/linux/list.h:806
Inline: True
```
```
In drivers/net/tun.c (ffffffff8188b188)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/interconnect/core.c (ffffffff819dceff)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/dev.c (ffffffff81a0d8c9)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81a4ea49)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60c69)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff81a67515)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff81a6e230)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff81a76416)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa39a3)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_put_port
  - net/ipv4/inet_hashtables.c:__inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4c1d)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5e2a)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff81acf92b)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ad4b4c)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81add6bf)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae9cc2)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81aee239)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81af45d4)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_free
```
```
In net/ipv4/nexthop.c (ffffffff81afca55)
Location: include/linux/list.h:806
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0da9c)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b18311)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff81b25e16)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff81b2c023)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81b3949b)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f58d)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_del
```
```
In net/ipv6/route.c (ffffffff81b42cba)
Location: include/linux/list.h:806
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4b9a3)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81b8b3cb)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba7618)
Location: include/linux/list.h:806
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/events/amd/uncore.c (ffffffff8100a042)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81070494)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8107ec72)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:kvm_async_pf_queue_task
```
```
In kernel/fork.c (ffffffff810a1efc)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a5c14)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810b220d)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c3c1e)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810c8768)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810d4bef)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810d6bd5)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff811365e9)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff811422d6)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff8114be2f)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff82fdff67)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff81192b19)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:do_unoptimize_kprobes
```
```
In kernel/trace/ftrace.c (ffffffff811ae8d2)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff811c3d44)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d5ef8)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/trampoline.c (ffffffff81222a01)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/bpf/devmap.c (ffffffff8122d20c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_remove_netdev
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122fbf9)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/events/core.c (ffffffff8123a210)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff81253785)
Location: include/linux/list.h:833
Inline: True
```
```
In kernel/watch_queue.c (ffffffff8125789a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff812dd63b)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:mn_hlist_release
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff812e27ac)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff812fb5c4)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81322681)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8133cf78)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff813414d6)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8134ca27)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff81362be4)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff81374b1a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventpoll.c (ffffffff8137adbe)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/io_uring.c (ffffffff8138ccd4)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/io_uring.c:__io_poll_remove_one
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a5a9c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff813ac67c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff813c087e)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff813cb918)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813d0727)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff813dac07)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff8147729c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff814853df)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff814cb546)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In crypto/algapi.c (ffffffff8153cb0d)
Location: include/linux/list.h:833
Inline: True
```
```
In block/elevator.c (ffffffff8155ce50)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff81564f86)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff8158345c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/bsg.c:bsg_put_device
```
```
In block/blk-cgroup.c (ffffffff81584541)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/keyslot-manager.c (ffffffff8159e717)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/clk/clk.c (ffffffff8171f9fa)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81778268)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/dax/super.c (ffffffff81831efb)
Location: include/linux/list.h:833
Inline: True
```
```
In drivers/net/tun.c (ffffffff81899328)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/interconnect/core.c (ffffffff819dc61f)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/dev.c (ffffffff81a05af2)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81a54a29)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/sch_api.c (ffffffff81a6fc35)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff81a76c00)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff81a7f186)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aadfe3)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_put_port
  - net/ipv4/inet_hashtables.c:__inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf27d)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1a5a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff81adc20b)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ae108c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81aea3ef)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81af6b22)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81afb199)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81b013d4)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_free
```
```
In net/ipv4/nexthop.c (ffffffff81b0a8d5)
Location: include/linux/list.h:833
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bcac)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b26c91)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff81b347b4)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff81b3aa43)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81b4819b)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81b4e02d)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
  - net/ipv6/addrlabel.c:ip6addrlbl_del
```
```
In net/ipv6/route.c (ffffffff81b514ba)
Location: include/linux/list.h:833
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5a5e3)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81b9a39b)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb6481)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/events/amd/uncore.c (ffffffff8100a7c2)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81070d44)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8107f902)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810a28b9)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a6a54)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810b384d)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c543e)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810ca211)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810d6baf)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810d88b5)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff811373d9)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff811434c6)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff8114d2df)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff831eab59)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff81193a57)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811af281)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff811c4e54)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d7538)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812251ac)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/bpf/trampoline.c (ffffffff812271a1)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/bpf/devmap.c (ffffffff81232648)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff8123ea40)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff81257da5)
Location: include/linux/list.h:833
Inline: True
```
```
In kernel/watch_queue.c (ffffffff8125bcfa)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff812e4dbb)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff812e9f39)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff81302394)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff813285f9)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff813433f8)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81347a86)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff813535f5)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff81369684)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff8137b4da)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380bfc)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8138192a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/io_uring.c (ffffffff81397558)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_remove_waitqs
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813acafc)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff813b3d2c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff813c758e)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff813d2908)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff813d7627)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff813e1827)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff8147cd0c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff8148acff)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff814d1b76)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In crypto/algapi.c (ffffffff815451ed)
Location: include/linux/list.h:833
Inline: True
```
```
In block/elevator.c (ffffffff815656e0)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff8156d5f6)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff8158a29c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff8158b341)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/keyslot-manager.c (ffffffff815a5560)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/clk/clk.c (ffffffff81700c4a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175bec8)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/dax/super.c (ffffffff8181562b)
Location: include/linux/list.h:833
Inline: True
```
```
In drivers/net/tun.c (ffffffff8187b708)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/interconnect/core.c (ffffffff819c289f)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/dev.c (ffffffff819ec43c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81a50649)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/sch_api.c (ffffffff81a58525)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff81a5e9d0)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff81a68026)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a990c3)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a58d)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abca7a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff81ac717b)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81accfec)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81ad5b3f)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae2272)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae6739)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81aeca9a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/ipv4/nexthop.c (ffffffff81af7feb)
Location: include/linux/list.h:833
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0999f)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81b148b1)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff81b225c3)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff81b28723)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81b35d9b)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81b3c12f)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff81b3f3da)
Location: include/linux/list.h:833
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b487b3)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81b89300)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba5441)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/apic/vector.c (ffffffff8107c9e3)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8108e6e2)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810b3fe0)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810b836c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810c59ed)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810d802e)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810dd02f)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810e9eb3)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810ec175)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff8115a089)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff81166a89)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff811713df)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff832cf48e)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff811bc964)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811d90b1)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff811f0394)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff812044f8)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d140)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/bpf/trampoline.c (ffffffff8125f2a1)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/bpf/devmap.c (ffffffff8126b9d4)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff81279500)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff81293915)
Location: include/linux/list.h:833
Inline: True
```
```
In kernel/watch_queue.c (ffffffff81297baa)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff8132cbcb)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff81331e5c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff8134c104)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff81375bc9)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff81390d38)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81395686)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff813a1a45)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff813b8384)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff813c821a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cdbbc)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff813ceb6a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/io_uring.c (ffffffff813ee1bd)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc46c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81403a1a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81417afe)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff81423e58)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff81428d67)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff81433337)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff814d442c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff814e253f)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff8152a907)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In crypto/algapi.c (ffffffff815a594d)
Location: include/linux/list.h:833
Inline: True
```
```
In block/elevator.c (ffffffff815c9ad0)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff815d1be6)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-cgroup.c (ffffffff815f036a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/keyslot-manager.c (ffffffff8160e030)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/clk/clk.c (ffffffff8177b45a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff817dfad8)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/dax/super.c (ffffffff8189fdcb)
Location: include/linux/list.h:833
Inline: True
```
```
In drivers/net/tun.c (ffffffff8190cc29)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/interconnect/core.c (ffffffff81a7214f)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/dev.c (ffffffff81a9d32c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81b091d7)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/sch_api.c (ffffffff81b11505)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff81b17ba0)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff81b21546)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54540)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b559fd)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7980a)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff81b8599b)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81b8b96c)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81b94b71)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba1a42)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba62db)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81bacd94)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/ipv4/nexthop.c (ffffffff81bb8d59)
Location: include/linux/list.h:833
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcc928)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd88b1)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff81be9319)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff81bee6e3)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81bfc4fb)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81c02a1f)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff81c0599a)
Location: include/linux/list.h:833
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81c0fa83)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81c55410)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c72fc1)
Location: include/linux/list.h:833
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/kernel/apic/vector.c (ffffffff8108bf13)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff8109f1d7)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810ca2ff)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810cebcd)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810dcfef)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810ee8ff)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810f68ef)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff81104b39)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff811071d5)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff81183509)
Location: include/linux/list.h:879
Inline: True
```
```
In kernel/time/timer.c (ffffffff8119a1ac)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff811a5c5b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff834831d3)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff811ef9c0)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8120fd8f)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff81228a74)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123f9b8)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7280)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/bpf/trampoline.c (ffffffff812a9913)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_put
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:bpf_trampoline_link_prog
```
```
In kernel/bpf/devmap.c (ffffffff812ba89b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff812cc555)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff812e93e5)
Location: include/linux/list.h:879
Inline: True
```
```
In kernel/watch_queue.c (ffffffff812ede76)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff8139cf10)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff813a2fca)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff813c37ae)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff813f3f59)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff81411fb6)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff81417618)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff81425452)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff8143dc32)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff8144f377)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81455e08)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff814576aa)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f91a)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff814778c9)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff8148f41e)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff8149c9ad)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff814a2061)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff814ad258)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff8155ed1c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff815707cf)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff815c02d0)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In crypto/algapi.c (ffffffff8164c6dd)
Location: include/linux/list.h:879
Inline: True
```
```
In block/elevator.c (ffffffff81674df3)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff8167db06)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-cgroup.c (ffffffff816a15ba)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-crypto-profile.c (ffffffff816c2b56)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff816d1dbf)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_remove_all
  - io_uring/io_uring.c:io_apoll_task_func
  - io_uring/io_uring.c:io_poll_task_func
```
```
In drivers/clk/clk.c (ffffffff818b1cb7)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8191d59c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/net/tun.c (ffffffff81a611dd)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81b3eed5)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
```
In drivers/interconnect/core.c (ffffffff81be3c3c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/dev.c (ffffffff81c16b23)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81c8f267)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/sch_api.c (ffffffff81c98635)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff81c9fa1e)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff81caf911)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_clear_multicast_users
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce12c3)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce365d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09566)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81d18d0b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81d26621)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34082)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81d38cad)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81d3fcbe)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/ipv4/nexthop.c (ffffffff81d4cc81)
Location: include/linux/list.h:879
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62638)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6f3ed)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff81d80496)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff81d86c43)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81d95e32)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c641)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff81d9ffca)
Location: include/linux/list.h:879
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81daac73)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81df51b1)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e16d4f)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff81e37c00)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/route.c (ffffffff81e39fe6)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
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
In arch/x86/kernel/apic/vector.c (ffffffff810a0426)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810b6733)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810e7952)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810ecfcf)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810fd1ef)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8110ffaf)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff81118fbb)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff8112a429)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff8112d105)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/printk/printk.c (ffffffff8118d947)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_force_preferred_locked
  - kernel/printk/printk.c:unregister_console_locked
```
```
In kernel/livepatch/shadow.c (ffffffff811be689)
Location: include/linux/list.h:879
Inline: True
```
```
In kernel/time/timer.c (ffffffff811d88b6)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff811e573b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff83eb0994)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8123766b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8125914f)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff81274154)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128d4a8)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81305950)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/bpf/trampoline.c (ffffffff81309b18)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
```
```
In kernel/bpf/devmap.c (ffffffff8131dd67)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/cgroup.c (ffffffff81327c83)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff81334335)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff81353155)
Location: include/linux/list.h:879
Inline: True
```
```
In kernel/watch_queue.c (ffffffff81358296)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff8141c340)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff81422c67)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff81446b7e)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff8147cf23)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff8149cd96)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff814a2d88)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff814b1bd2)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff814cc5d2)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff814ddbe7)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e4d76)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff814e695a)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_remove
```
```
In fs/crypto/keyring.c (ffffffff814fe672)
Location: include/linux/list.h:879
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff815010ea)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8150a139)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81522ece)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff815313ad)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff81537151)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff815436c8)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff81600f3c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff816157cb)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff8166c810)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
```
```
In crypto/algapi.c (ffffffff8170599d)
Location: include/linux/list.h:879
Inline: True
```
```
In block/elevator.c (ffffffff81730b73)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff8173a726)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-cgroup.c (ffffffff8176042a)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-crypto-profile.c (ffffffff81783ee6)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff8178b95f)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
```
```
In io_uring/net.c (ffffffff817966f4)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
```
```
In io_uring/poll.c (ffffffff8179d25a)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
```
In drivers/clk/clk.c (ffffffff819fe2e7)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81a7976c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/net/tun.c (ffffffff81bec4d8)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81cd5285)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
```
In drivers/interconnect/core.c (ffffffff81d8f96c)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - drivers/interconnect/core.c:icc_put
```
```
In net/core/dev.c (ffffffff81dd0e10)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81e4a4c7)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/sch_api.c (ffffffff81e54605)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff81e5bcce)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff81e668a1)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea4b18)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5e9f)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ece80a)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/udp.c (ffffffff81edf416)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/devinet.c (ffffffff81eedee1)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81efc532)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0152d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81f088ee)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/ipv4/nexthop.c (ffffffff81f16521)
Location: include/linux/list.h:879
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d138)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3ab5d)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff81f4b747)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/anycast.c (ffffffff81f547f3)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81f646e2)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81f6b331)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff81f6f1da)
Location: include/linux/list.h:879
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7a543)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81fc7b31)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81fee71f)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff82010e82)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/route.c (ffffffff8201364b)
Location: include/linux/list.h:879
Inline: True
Inline callers:
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
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
In arch/x86/kernel/apic/vector.c (ffffffff810a33a6)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810b9843)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810f3503)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810f8aef)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff811091ef)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff81120b2f)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff81126477)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff81137479)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff8113a5c5)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/printk/printk.c (ffffffff8119f0ed)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_force_preferred_locked
  - kernel/printk/printk.c:unregister_console_locked
```
```
In kernel/irq/resend.c (ffffffff811abf75)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/irq/resend.c:clear_irq_resend
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/livepatch/shadow.c (ffffffff811d10b9)
Location: include/linux/list.h:894
Inline: True
```
```
In kernel/module/main.c (ffffffff811e06f9)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
```
```
In kernel/time/timer.c (ffffffff811ecce6)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff811fa4b9)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_unhash_and_free
```
```
In kernel/cgroup/cgroup.c (ffffffff836d5984)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8124e72b)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8127051f)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:match_records
  - kernel/trace/ftrace.c:dup_hash
```
```
In kernel/trace/trace_output.c (ffffffff8128ba84)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff812aa428)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5316)
Location: include/linux/list.h:894
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81333ec2)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
```
```
In kernel/bpf/trampoline.c (ffffffff81338958)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
```
```
In kernel/bpf/devmap.c (ffffffff8134daa5)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/cgroup.c (ffffffff81357fd4)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff813650b5)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff81384355)
Location: include/linux/list.h:894
Inline: True
```
```
In kernel/watch_queue.c (ffffffff81389ac2)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff8144f8f0)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff81457cd2)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff8147c2d1)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff814b1cf3)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff814d21b6)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff814d7ed8)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff814e6c21)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/fs_pin.c (ffffffff81502812)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff815143cc)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151bdc6)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff8151d570)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/eventpoll.c:__ep_remove
```
```
In fs/crypto/keyring.c (ffffffff81535ef7)
Location: include/linux/list.h:894
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff8153877a)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff815418b9)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff8155b0c0)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff8156955d)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff8156f341)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff8157bb28)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff81638e2c)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff8164d85b)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff816a58a2)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_ss_reset
```
```
In crypto/algapi.c (ffffffff8173fc2d)
Location: include/linux/list.h:894
Inline: True
```
```
In block/elevator.c (ffffffff8176cdd3)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff81776e3e)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-cgroup.c (ffffffff8179f7a2)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-crypto-profile.c (ffffffff817c41c7)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/poll.c (ffffffff817de48a)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
```
In drivers/clk/clk.c (ffffffff81a46f67)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac4eac)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/net/tun.c (ffffffff81c44b58)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81d3cf15)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
```
In drivers/interconnect/core.c (ffffffff81dfdf4c)
Location: include/linux/list.h:894
Inline: True
```
```
In net/core/dev.c (ffffffff81e41a3e)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/sock_map.c (ffffffff81ea5bd7)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/sch_api.c (ffffffff81eafea5)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff81eb84cc)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff81ec2661)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f033a6)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f0464f)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2dbca)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff81f3bb1d)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3e8de)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/devinet.c (ffffffff81f4d8a1)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5bf52)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81f60f9d)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81f683fe)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/ipv4/ping.c (ffffffff81f6b569)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff81f761d1)
Location: include/linux/list.h:894
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cc38)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9a57d)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff81fab4e7)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/anycast.c (ffffffff81fb4203)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff81fc47d2)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81fcb4e7)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff81fcf26d)
Location: include/linux/list.h:894
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81fda753)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff82028ac1)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8206a818)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff8208dc42)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/route.c (ffffffff8209046b)
Location: include/linux/list.h:894
Inline: True
Inline callers:
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
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
In arch/x86/kernel/apic/vector.c (ffffffff810aa2e6)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0c6f)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
  - arch/x86/kernel/kvm.c:apf_task_wake_all
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait_schedule
```
```
In kernel/fork.c (ffffffff810fc8b3)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff81101eff)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff81112b7f)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff8112a3df)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff81130a7f)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff81142659)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff811454d5)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/printk/printk.c (ffffffff811ae1dd)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_force_preferred_locked
  - kernel/printk/printk.c:unregister_console_locked
```
```
In kernel/irq/resend.c (ffffffff811bbb75)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/irq/resend.c:clear_irq_resend
  - kernel/irq/resend.c:resend_irqs
```
```
In kernel/livepatch/shadow.c (ffffffff811e5d39)
Location: include/linux/list.h:983
Inline: True
```
```
In kernel/module/main.c (ffffffff811f6429)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
```
```
In kernel/time/timer.c (ffffffff81202e40)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:__run_timers
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff812106a9)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_timer_unhash_and_free
```
```
In kernel/cgroup/cgroup.c (ffffffff83907cf4)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8126865b)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8128a9be)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:enter_record
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff812a6e54)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c6138)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1d4b)
Location: include/linux/list.h:983
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813585b2)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In kernel/bpf/trampoline.c (ffffffff8135ea88)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_unlink_prog
  - kernel/bpf/trampoline.c:__bpf_trampoline_link_prog
```
```
In kernel/bpf/devmap.c (ffffffff81374fc5)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/bpf/cgroup.c (ffffffff81380b54)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (ffffffff8138e085)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff813ad765)
Location: include/linux/list.h:983
Inline: True
```
```
In kernel/watch_queue.c (ffffffff813b3512)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:watch_queue_clear
  - kernel/watch_queue.c:remove_watch_from_object
  - kernel/watch_queue.c:remove_watch_from_object
```
```
In mm/mmu_notifier.c (ffffffff814895d0)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_remove
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
  - mm/mmu_notifier.c:mn_itree_inv_end
```
```
In mm/ksm.c (ffffffff814927a2)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_node_dup
  - mm/ksm.c:unmerge_and_remove_all_rmap_items
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff814ab3a1)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff814e3b55)
Location: include/linux/list.h:983
Inline: True
```
```
In fs/dcache.c (ffffffff815063ab)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__dentry_kill
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff8150a6b8)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/namespace.c (ffffffff8151aa61)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
```
```
In fs/libfs.c (ffffffff8152251b)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
  - fs/libfs.c:scan_positives
```
```
In fs/fs_pin.c (ffffffff81537462)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff8154889c)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff815503c6)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/eventpoll.c (ffffffff81551b50)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/eventpoll.c:__ep_remove
```
```
In fs/crypto/keyring.c (ffffffff8156af07)
Location: include/linux/list.h:983
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d8fa)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81576d99)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81591afb)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/quota/dquot.c:dqcache_shrink_scan
  - fs/quota/dquot.c:invalidate_dquots
```
```
In fs/proc/inode.c (ffffffff815a1b7d)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
```
```
In fs/proc/base.c (ffffffff815a7d00)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_evict_inode
```
```
In fs/proc/proc_sysctl.c (ffffffff815b43d8)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff8167231c)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff81686dbb)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff816e22e2)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_ss_reset
```
```
In crypto/algapi.c (ffffffff81780aad)
Location: include/linux/list.h:983
Inline: True
```
```
In block/elevator.c (ffffffff817af003)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_del
```
```
In block/blk-ioc.c (ffffffff817b906e)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/blk-cgroup.c (ffffffff817e3272)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-crypto-profile.c (ffffffff81808e57)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/uring_cmd.c (ffffffff81819a40)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_done
```
```
In io_uring/poll.c (ffffffff8182285a)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_disarm
  - io_uring/poll.c:io_poll_remove_all_table
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/kbuf.c (ffffffff818259b4)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_kbuf_mmap_list_free
```
```
In io_uring/waitid.c (ffffffff8182ad33)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_complete
```
```
In io_uring/futex.c (ffffffff8182ee5a)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - io_uring/futex.c:io_futexv_complete
  - io_uring/futex.c:io_futex_complete
```
```
In drivers/clk/clk.c (ffffffff81a92a07)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b17eac)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/net/tun.c (ffffffff81cfa6b8)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81df3875)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_unregister
```
```
In drivers/interconnect/core.c (ffffffff81eb49ac)
Location: include/linux/list.h:983
Inline: True
```
```
In net/core/dev.c (ffffffff81ef71cd)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:netdev_name_node_alt_destroy
```
```
In net/core/page_pool_user.c (ffffffff81f4578a)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/core/page_pool_user.c:page_pool_netdevice_event
  - net/core/page_pool_user.c:page_pool_unlist
```
```
In net/core/sock_map.c (ffffffff81f68697)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/sched/sch_api.c (ffffffff81f72915)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff81f7b59c)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff81f859b1)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc75eb)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc896f)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff73d4)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_clear_md5_list
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff82001c3d)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff82004c2e)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/devinet.c (ffffffff820139b1)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff820224b2)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8202756d)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff8202ea2e)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
```
```
In net/ipv4/ping.c (ffffffff82031949)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffff8203c9a1)
Location: include/linux/list.h:983
Inline: True
```
```
In net/ipv4/tcp_ao.c (ffffffff82055045)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_del_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_copy_all_matching
  - net/ipv4/tcp_ao.c:tcp_ao_connect_init
  - net/ipv4/tcp_ao.c:tcp_ao_destroy_sock
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a5c8)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
  - net/xfrm/xfrm_policy.c:xfrm_dst_hash_transfer
```
```
In net/xfrm/xfrm_state.c (ffffffff820678dd)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff820788d7)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/anycast.c (ffffffff82081ab3)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
```
In net/ipv6/addrconf.c (ffffffff82091d82)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff82098cc7)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
  - net/ipv6/addrlabel.c:ip6addrlbl_net_init
```
```
In net/ipv6/route.c (ffffffff8209cacd)
Location: include/linux/list.h:983
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff820a81a3)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff820f8501)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8213e449)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff82164102)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
```
```
In net/mctp/route.c (ffffffff821669ab)
Location: include/linux/list.h:983
Inline: True
Inline callers:
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
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
In arch/arm64/kernel/probes/kprobes.c (0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/kprobes.c:trampoline_probe_handler
```
```
In virt/kvm/eventfd.c (ffff8000100c0f8c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_unregister_irq_ack_notifier
```
```
In virt/kvm/irqchip.c (0)
Location: include/linux/list.h:757
Inline: True
```
```
In kernel/fork.c (ffff8000100f4160)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffff8000100f8a88)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffff80001010a42c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffff80001011e4b8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffff8000101245b8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffff80001013009c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffff80001013147c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/time/timer.c (ffff8000101a0344)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffff8000101ab884)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffff80001144b070)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffff8000101f847c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
```
```
In kernel/trace/ftrace.c (ffff800010214c08)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffff80001022b76c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffff80001023eb48)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffff800010287274)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffff800010290c8c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In mm/mmu_notifier.c (ffff80001033cf38)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffff80001033fb48)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffff80001035c6b0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffff800010388114)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffff8000103a5df4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffff8000103ad34c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffff8000103b8b10)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffff8000103d3f44)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffff8000103e9ba0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f91c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffff80001041658c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffff800010431f58)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffff80001044aa20)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffff8000104ede98)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffff8000104fd184)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffff800010546928)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffff8000105b8e08)
Location: include/linux/list.h:757
Inline: True
```
```
In block/elevator.c (ffff8000105de9a4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffff8000105e8528)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffff8000106097d8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffff80001060c5f8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffff8000107c3440)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffff800010884ee0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/dax/super.c (ffff800010962fdc)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/net/tun.c (ffff8000109db228)
Location: include/linux/list.h:757
Inline: True
```
```
In net/core/dev.c (ffff800010bcc4e4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffff800010c21ce4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/bpf_sk_storage.c (ffff800010c31328)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffff800010c3b598)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffff800010c41fe8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffff800010c4a730)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6a7dc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bbf0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c1e4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffff800010c96da0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffff800010c9bb44)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffff800010ca55d4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7220)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffff800010cbd764)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/nexthop.c (ffff800010cc515c)
Location: include/linux/list.h:757
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd894c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffff800010ce5fb8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffff800010cf2b68)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffff800010cf7024)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffff800010d05028)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffff800010d0c10c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffff800010d0ea2c)
Location: include/linux/list.h:757
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffff800010d5c210)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffff800010d7f078)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/arm/probes/kprobes/core.c (c0ea0a40)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/core.c:trampoline_handler
```
```
In kernel/fork.c (c03520f8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (c0356ce8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (c0363474)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (c03702c8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (c03776f4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (c037f8e4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/time/timer.c (c03e9fc4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (c03f63e8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (c1525494)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (c0436d08)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (c045395c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (c0468d50)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (c047a1b0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (c04b7378)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (c04c0370)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In mm/mmu_notifier.c (c054368c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (c0545e54)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/super.c (c056ec24)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (c05874d4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (c058bf2c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (c0596464)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (c05ae134)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (c05c0c88)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/crypto/keysetup_v1.c (c05dc1b0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (c05e202c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (c05fa164)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (c060f8c8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (c06a9410)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (c06ba7d4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (c06fc300)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (c0767928)
Location: include/linux/list.h:757
Inline: True
```
```
In block/elevator.c (c078b944)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (c0794f5c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (c07b4ca0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (c07b7d68)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (c08eee30)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (c0982ff0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/dax/super.c (c0a39f58)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/net/tun.c (c0ac17d8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_delete
```
```
In net/core/dev.c (c0ce45d0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (c0d39298)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/bpf_sk_storage.c (c0d480c4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (c0d4d300)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (c0d53d78)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (c0d5b22c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (c0d798bc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c0d7aab0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (c0d99d28)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (c0da4abc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c0da79d8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (c0db1f10)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (c0dbecc4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (c0dc2734)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (c0dc9110)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/nexthop.c (c0dd0bd0)
Location: include/linux/list.h:757
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c0de2520)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (c0deced8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (c0df890c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (c0dfd510)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (c0e0c1ac)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (c0e11e84)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (c0e15f98)
Location: include/linux/list.h:757
Inline: True
```
```
In net/ipv6/ip6_fib.c (c0e1eaa8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (c0e5c220)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c0e7922c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/powerpc/kernel/kprobes.c (c0000000000572c0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/powerpc/kernel/kprobes.c:trampoline_probe_handler
```
```
In kernel/fork.c (c000000000139860)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (c00000000013f544)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (c000000000151394)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (c000000000169400)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (c00000000016e23c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (c000000000179494)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (c00000000017ab40)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (c0000000001f237c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (c000000000201300)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (c00000000020eba4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (c000000001370874)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (c00000000026cd38)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (c000000000296000)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (c0000000002b3768)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (c0000000002cea70)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (c00000000033167c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (c00000000033db88)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In mm/mmu_notifier.c (c000000000418394)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (c00000000041c3f4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (c000000000445df4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (c00000000047c0a8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (c00000000049f160)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (c0000000004a8bd0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (c0000000004b5b88)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (c0000000004d6a98)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (c0000000004f0304)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/crypto/keysetup_v1.c (c00000000051d2b0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (c000000000525320)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (c0000000005431c0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (c000000000561198)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (c00000000062cc84)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (c0000000006403e4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (c00000000069d138)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (c00000000073e708)
Location: include/linux/list.h:757
Inline: True
```
```
In block/elevator.c (c000000000770700)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (c00000000077d150)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (c0000000007a5f9c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (c0000000007a9450)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/tty/serial/8250/8250_core.c (c00000000092bf98)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/dax/super.c (c000000000a19310)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/net/tun.c (c000000000a9cc40)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_delete
```
```
In net/core/dev.c (c000000000cab694)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (c000000000d14388)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/bpf_sk_storage.c (c000000000d2a2d8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (c000000000d34740)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (c000000000d3df9c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (c000000000d48390)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (c000000000d6f958)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d7114c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97e3c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (c000000000da78dc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c000000000dab728)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (c000000000db9464)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (c000000000dca78c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (c000000000dcf6a4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (c000000000dd796c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/nexthop.c (c000000000de157c)
Location: include/linux/list.h:757
Inline: True
```
```
In net/xfrm/xfrm_policy.c (c000000000df9160)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
  - net/xfrm/xfrm_policy.c:xfrm_bydst_resize
```
```
In net/xfrm/xfrm_state.c (c000000000e07718)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (c000000000e17fc0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (c000000000e1d884)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (c000000000e2ef60)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (c000000000e36a18)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (c000000000e3bed8)
Location: include/linux/list.h:757
Inline: True
```
```
In net/ipv6/ip6_fib.c (c000000000e4699c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (c000000000e97c58)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c000000000ebf2d4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/fork.c (ffffffe0000c0156)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffe0000c385e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffe0000cce84)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffe0000d7d06)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffe0000dc60e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffe0000e35aa)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/time/timer.c (ffffffe00012c65e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffe0001360bc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffe00000c430)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/trace/ftrace.c (ffffffe000174a7a)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffe0001857e8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffe0001940cc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffe0001bb596)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffe0001c3686)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In mm/mmu_notifier.c (ffffffe0002328b6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffe0002343dc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In fs/super.c (ffffffe000259bb8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffe00026cc86)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffe000271e24)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffe00027af3a)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffe00028e5ac)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffe00029e548)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b83b2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffe0002bd5ac)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffe0002ce40e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffffffe0002dfd6e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffe00035e320)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffe00036b87e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffe0003a2068)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_flush
  - security/selinux/avc.c:avc_alloc_node
```
```
In crypto/algapi.c (ffffffe0003ff4e2)
Location: include/linux/list.h:757
Inline: True
```
```
In block/elevator.c (ffffffe00042159a)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffe000429174)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffe000443220)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffe0004450a6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffe000510e26)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffe00055081e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial_do_unlink
```
```
In drivers/dax/super.c (ffffffe0005d06c0)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/net/tun.c (ffffffe000625932)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_delete
```
```
In net/core/dev.c (ffffffe000757f56)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffe00079aad6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a70ac)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffe0007ac1fc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffe0007b1826)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffe0007b7980)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d02ce)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d15e6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb362)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffe0007f53c4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffe0007f9dbc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffe000800ed0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b62e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffe00080e5b4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffe000813a4a)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/nexthop.c (ffffffe00081905c)
Location: include/linux/list.h:757
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828e6e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffe000831e72)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffe00083e1e4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffe00084250c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffe00084f5d6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffe000852fbc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffe00085500e)
Location: include/linux/list.h:757
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffe00085d892)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffe0008923ca)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffe0008ac20e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/events/amd/uncore.c (ffffffff81009ede)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810678f7)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071b5a)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81076dd5)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff810989d6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109cc6c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810a96b4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810bc966)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810c029e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810c9ec3)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810cae6c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff81125d3c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff8112f7cc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff8113919c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828bb983)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8117c448)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811943a9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff811a696b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b7af0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff811f7893)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811ff6c8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff812154dd)
Location: include/linux/list.h:757
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8129637f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff812988ef)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff812b3527)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812d8a98)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812f0c7e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812f54fd)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812fda39)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff81314b49)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff81325cff)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346b40)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8134c4b1)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff813623fc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffffffff81375f51)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff81405800)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff814142b9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff81452785)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff814b7f09)
Location: include/linux/list.h:757
Inline: True
```
```
In block/elevator.c (ffffffff814d9e87)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814e27ea)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff814ffb0b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff81501dff)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffff81618be2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81670391)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/dax/super.c (ffffffff81717a0e)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/net/tun.c (ffffffff817858a4)
Location: include/linux/list.h:757
Inline: True
```
```
In net/core/dev.c (ffffffff818d0584)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff8191a77c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81928e3c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff8192f4bd)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff81935254)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff8193d04e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958d53)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a001)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977228)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff8198219f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81987a3c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff8198f502)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff8199b2e7)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8199ea7d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff819a494b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/nexthop.c (ffffffff819abb7f)
Location: include/linux/list.h:757
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbd70)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff819c6711)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff819d0f9d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff819d5b66)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff819e2112)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819e8351)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff819ec736)
Location: include/linux/list.h:757
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff819f3cc8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81a2e67b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a4a509)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/events/amd/uncore.c (ffffffff8100849e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81057c67)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81061b6a)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81066e23)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff81087440)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8108b69c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff81098074)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810ab1c6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810aeaaf)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810b86e3)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810b966c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff8111879c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff8112224c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff8112bbec)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828b4016)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8116f5e8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff811874b9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff811998eb)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811aa8d0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff811ea5e3)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811f2418)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff8120823d)
Location: include/linux/list.h:757
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff81287f8f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff8128a4af)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff812a48a7)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812c9718)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812e18ae)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812e611d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812ee659)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff81305759)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff8131689f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/crypto/keysetup_v1.c (ffffffff81337820)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8133d191)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff8135309c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffffffff81366a21)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff813f6280)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff81404d39)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff814431d5)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff814a8929)
Location: include/linux/list.h:757
Inline: True
```
```
In block/elevator.c (ffffffff814ca837)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814d317a)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff814f001b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff814f230f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffff8160d112)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8164f4ab)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/dax/super.c (ffffffff816eff3e)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/net/tun.c (ffffffff817651f4)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/net/vxlan.c (ffffffff817709a0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_sock_release
  - drivers/net/vxlan.c:vxlan_sock_release
  - drivers/net/vxlan.c:vxlan_fdb_destroy
```
```
In net/core/dev.c (ffffffff8188a464)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff818d452c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff818e2bec)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff818e8fbd)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff818eed54)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff818f6b4e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff81912843)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913af1)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930ce8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff8193bc5f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819414fc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81948fc2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81954da7)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff8195853d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff8195e40b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/nexthop.c (ffffffff8196563f)
Location: include/linux/list.h:757
Inline: True
```
```
In net/ipv4/ip_tunnel.c (ffffffff819669ed)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_uninit
  - net/ipv4/ip_tunnel.c:ip_tunnel_dellink
  - net/ipv4/ip_tunnel.c:ip_tunnel_update
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978b60)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81983501)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff8198dd5d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff81992926)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff8199eed2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff819a5111)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff819a94f6)
Location: include/linux/list.h:757
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0a88)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff819eb86b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a070f9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/events/amd/uncore.c (ffffffff81009e9e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81067da7)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071b0a)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81076d85)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff81098986)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff8109cc1c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810a8c14)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810bbec6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810bf7ef)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810c93f3)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810ca38c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff81123c2c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff8112d4ec)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff81136ebc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828ce706)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff8117a218)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff81192179)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff811a473b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b58c0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff811f5663)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff811fd498)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff8121327d)
Location: include/linux/list.h:757
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff8129418f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff812966ff)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff812b1337)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812d68a8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812eea8e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff812f330d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff812fb829)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff81312939)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff813237cf)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/crypto/keysetup_v1.c (ffffffff81344610)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff81349f81)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff8135fecc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffffffff81373a21)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff81402b80)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff81411639)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff8144e825)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff814b3f99)
Location: include/linux/list.h:757
Inline: True
```
```
In block/elevator.c (ffffffff814d5f17)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814de87a)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff814fbb9b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff814fde8f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffff816469c2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8169e761)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/dax/super.c (ffffffff817567de)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/net/tun.c (ffffffff817b5c54)
Location: include/linux/list.h:757
Inline: True
```
```
In net/core/dev.c (ffffffff81921584)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff8196b90c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff81979fcc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff8198064d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff819863e4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff8198e1de)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199b052)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_rcv_nl_event
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b6d7)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__instance_destroy
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a21de)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_unlink_expect_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_unlink_expect_report
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a3633)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_unregister
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3523)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c47d1)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e19f8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff819ec96f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819f220c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff819f9da2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81a05b87)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0931d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a0f1eb)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/nexthop.c (ffffffff81a1641f)
Location: include/linux/list.h:757
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a267f0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a31191)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff81a3ba1d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff81a405e6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81a4cb92)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a52dd1)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff81a571b6)
Location: include/linux/list.h:757
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5e748)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81a9a22b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ab63b9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In arch/x86/events/amd/uncore.c (ffffffff81009ffe)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:uncore_online
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81069457)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:free_moved_vector
  - arch/x86/kernel/apic/vector.c:clear_irq_vector
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81073b7e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
```
In arch/x86/kernel/kvm.c (ffffffff81078de2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
```
```
In kernel/fork.c (ffffffff810a05ad)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/cpu.c (ffffffff810a49bb)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_state_remove_instance
```
```
In kernel/user.c (ffffffff810b0d14)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/user.c:free_uid
```
```
In kernel/workqueue.c (ffffffff810c0e94)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:process_one_work
```
```
In kernel/pid.c (ffffffff810c7bfe)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/pid.c:__change_pid
```
```
In kernel/ucount.c (ffffffff810d1953)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/ucount.c:put_ucounts
```
```
In kernel/sched/core.c (ffffffff810d288c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/sched/core.c:preempt_notifier_unregister
```
```
In kernel/livepatch/shadow.c (ffffffff8113026c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free_struct
```
```
In kernel/time/timer.c (ffffffff81139e03)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_dead_cpu
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:run_timer_softirq
  - kernel/time/timer.c:detach_if_pending
```
```
In kernel/time/posix-timers.c (ffffffff8114394c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:release_posix_timer
```
```
In kernel/cgroup/cgroup.c (ffffffff828d3b00)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
```
```
In kernel/kprobes.c (ffffffff81187b48)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:cleanup_rp_inst
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:recycle_rp_inst
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/trace/ftrace.c (ffffffff8119fd09)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_set_hash
  - kernel/trace/ftrace.c:ftrace_set_hash
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_func_mapper_remove_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
```
```
In kernel/trace/trace_output.c (ffffffff811b24cb)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_output.c:unregister_trace_event
```
```
In kernel/trace/trace_event_perf.c (ffffffff811c3960)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_del
```
```
In kernel/bpf/devmap.c (ffffffff81203bbd)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_free
```
```
In kernel/events/core.c (ffffffff8120c1f8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_del
```
```
In kernel/user-return-notifier.c (ffffffff8122221d)
Location: include/linux/list.h:757
Inline: True
```
```
In mm/mmu_notifier.c (ffffffff812a3fbf)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_put
  - mm/mmu_notifier.c:mmu_notifier_unregister
  - mm/mmu_notifier.c:__mmu_notifier_release
```
```
In mm/ksm.c (ffffffff812a64eb)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:remove_node_from_stable_tree
```
```
In mm/khugepaged.c (ffffffff812c1677)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In fs/super.c (ffffffff812e6778)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/super.c:generic_shutdown_super
```
```
In fs/dcache.c (ffffffff812ff06e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/inode.c (ffffffff8130307d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/inode.c:__remove_inode_hash
```
```
In fs/namespace.c (ffffffff8130cb66)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:unhash_mnt
  - fs/namespace.c:unhash_mnt
```
```
In fs/fs_pin.c (ffffffff81324179)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fs_pin.c:pin_remove
  - fs/fs_pin.c:pin_remove
```
```
In fs/notify/mark.c (ffffffff8133547c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/crypto/keysetup_v1.c (ffffffff813578f0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
```
```
In fs/locks.c (ffffffff8135cca2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
```
In fs/quota/dquot.c (ffffffff81372988)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dqcache_shrink_scan
```
```
In fs/proc/proc_sysctl.c (ffffffff81386fb1)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/proc/proc_sysctl.c:proc_sys_evict_inode
```
```
In fs/fat/inode.c (ffffffff81416530)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_detach
  - fs/fat/inode.c:fat_detach
```
```
In fs/ecryptfs/messaging.c (ffffffff814272a9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
```
```
In security/selinux/avc.c (ffffffff81465bf5)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_node_delete
```
```
In crypto/algapi.c (ffffffff814cca19)
Location: include/linux/list.h:757
Inline: True
```
```
In block/elevator.c (ffffffff814eeb17)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_reposition
```
```
In block/blk-ioc.c (ffffffff814f76da)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_destroy_icq
```
```
In block/bsg.c (ffffffff81514c4b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/blk-cgroup.c (ffffffff8151766f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_destroy
```
```
In drivers/clk/clk.c (ffffffff81660f52)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_reparent
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816b8bc6)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/dax/super.c (ffffffff81771bce)
Location: include/linux/list.h:757
Inline: True
```
```
In drivers/net/tun.c (ffffffff817cfff4)
Location: include/linux/list.h:757
Inline: True
```
```
In net/core/dev.c (ffffffff8193be66)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/dev.c:napi_hash_del
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:unlist_netdevice
  - net/core/dev.c:unlist_netdevice
```
```
In net/core/sock_map.c (ffffffff8198dd7c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
```
```
In net/core/bpf_sk_storage.c (ffffffff8199c4fc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_unlink_map
  - net/core/bpf_sk_storage.c:__selem_unlink_sk
```
```
In net/sched/sch_api.c (ffffffff819a2bbd)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_class_hash_remove
```
```
In net/sched/cls_api.c (ffffffff819a93e4)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_destroy
```
```
In net/netlink/af_netlink.c (ffffffff819b0a7e)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_update_subscriptions
  - net/netlink/af_netlink.c:netlink_remove
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd1f6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_put_port
  - net/ipv4/inet_hashtables.c:inet_put_port
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce251)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_bind_unhash
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb728)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_del
```
```
In net/ipv4/raw.c (ffffffff819f685f)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819f95fc)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/devinet.c (ffffffff81a040b2)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_hash_remove
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10157)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_fib_net_exit
```
```
In net/ipv4/fib_semantics.c (ffffffff81a13acd)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:fib_release_info
```
```
In net/ipv4/fib_trie.c (ffffffff81a19a3b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_table_flush
  - net/ipv4/fib_trie.c:fib_table_flush_external
  - net/ipv4/fib_trie.c:fib_trie_unmerge
  - net/ipv4/fib_trie.c:fib_table_delete
```
```
In net/ipv4/nexthop.c (ffffffff81a20e5f)
Location: include/linux/list.h:757
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31ca0)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:__xfrm_policy_unlink
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
  - net/xfrm/xfrm_policy.c:xfrm_hash_resize
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3ca91)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/unix/af_unix.c (ffffffff81a46d6d)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/anycast.c (ffffffff81a4bfa6)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_del_acaddr_hash
```
```
In net/ipv6/addrconf.c (ffffffff81a58b02)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:ipv6_del_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81a5ed4c)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_net_exit
```
```
In net/ipv6/route.c (ffffffff81a63266)
Location: include/linux/list.h:757
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6abc8)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_net_exit
```
```
In net/packet/af_packet.c (ffffffff81aa6f5b)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ac24d9)
Location: include/linux/list.h:757
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
