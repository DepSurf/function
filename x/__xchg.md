# Function: <code>__xchg</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/arm64/mm/context.c (ffff8000100aff18)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1318)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_get_and_clear
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
```
```
In kernel/fork.c (ffff8000100f3060)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/locking/qspinlock.c (ffff80001016aa7c)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
```
```
In mm/vmstat.c (ffff8000102dace0)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/memory.c (ffff8000102fa044)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffff80001030524c)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff80001030618c)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffff800010308464)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
```
```
In mm/vmalloc.c (ffff80001030c7c0)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
```
```
In mm/madvise.c (ffff80001031ec38)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffff800010357f90)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffff800010367ee0)
Location: arch/arm64/include/asm/cmpxchg.h:85
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (c0354540)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
```
```
In kernel/exit.c (c035a55c)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sysctl.c (c035fa5c)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_cad_pid
```
```
In kernel/sys.c (c036af84)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/sys.c:__se_sys_umask
```
```
In kernel/umh.c (c036f360)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/kthread.c (c037b7ac)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
Direct callers:
  - kernel/kthread.c:kthread
```
```
In kernel/smpboot.c (c037f644)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/sched/core.c (c038a504)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/loadavg.c (c038eacc)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/locking/osq_lock.c (c03b67c4)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (c03c8a2c)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (c03dc8dc)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/smp.c (c04058bc)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (c040a280)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/acct.c (c040ef24)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/kexec.c (c04110b4)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/audit.c (c042b8e0)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (c043a77c)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (c0445b50)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/blktrace.c (c0472498)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
```
```
In kernel/irq_work.c (c048e0c4)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
```
```
In kernel/bpf/helpers.c (c04a8fdc)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/arraymap.c (c04ad670)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:fd_array_map_delete_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_update_elem
```
```
In kernel/bpf/local_storage.c (c04b0244)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/devmap.c (c04b7418)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
```
```
In kernel/bpf/cpumap.c (c04b7be0)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_replace
```
```
In kernel/bpf/xskmap.c (c04b8e14)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
```
```
In kernel/bpf/stackmap.c (c04bb0bc)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In kernel/events/core.c (c04c4a98)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In kernel/events/ring_buffer.c (c04d237c)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmscan.c (c04f16bc)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (c05295dc)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/swap_state.c (c053a4c8)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/page_counter.c (c055343c)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (c0555c30)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
```
```
In fs/file_table.c (c056e828)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - fs/file_table.c:delayed_fput
```
```
In fs/file.c (c0591338)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
```
```
In fs/namespace.c (c0594994)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:delayed_mntput
```
```
In fs/eventpoll.c (c05c8388)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/aio.c (c05cee24)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In fs/posix_acl.c (c05ef260)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/ext4/page-io.c (c0665950)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
```
```
In lib/debug_locks.c (c07d1298)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
```
```
In lib/generic-radix-tree.c (c07dde68)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
```
```
In lib/sbitmap.c (c0812bdc)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_resize
```
```
In drivers/tty/tty_buffer.c (c096557c)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/tty/tty_audit.c (c096918c)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_exit
```
```
In drivers/tty/vt/vt.c (c0976dec)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (c0985d34)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
```
```
In net/socket.c (c0cc5cd8)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (c0cca114)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/datagram.c (c0cd8fc4)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c0cd92dc)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/gen_estimator.c (c0cdb518)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
```
```
In net/core/net_namespace.c (c0cdbfc8)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/filter.c (c0d14e50)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/skmsg.c (c0d27b54)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (c0d39144)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_free
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
```
```
In net/sched/act_api.c (c0d58160)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_set_action_cookie
```
```
In net/netfilter/nf_log.c (c0d653a4)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/ipv4/route.c (c0d6bf9c)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (c0d774b8)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c0d7b984)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (c0d803ac)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (c0d86e00)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
```
```
In net/ipv4/tcp_cong.c (c0d9fe94)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
```
In net/ipv4/datagram.c (c0da44d8)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c0da5410)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (c0da9844)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c0db8028)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (c0dcd1fc)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/cipso_ipv4.c (c0de0168)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
```
```
In net/unix/af_unix.c (c0dfa620)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/ipv6/af_inet6.c (c0dfcea0)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/route.c (c0e1a618)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (c0e1f5d0)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (c0e224b0)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/tcp_ipv6.c (c0e3b06c)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/datagram.c (c0e40974)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
```
```
In net/ipv6/calipso.c (c0e4f9c4)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
```
```
In net/packet/af_packet.c (c0e5d314)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/netlabel/netlabel_calipso.c (c0e69174)
Location: arch/arm/include/asm/cmpxchg.h:28
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_ops_register
```
**Symbols:**

```
c037ad94-c037adc0: __xchg.constprop.0 (STB_LOCAL)
c03dc8dc-c03dc908: __xchg.constprop.0 (STB_LOCAL)
c0e2152c-c0e21554: __xchg.constprop.0 (STB_LOCAL)
```
</details>
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
