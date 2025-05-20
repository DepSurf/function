# Function: <code>__xchg_mb</code>

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
In virt/kvm/kvm_main.c (ffff8000100bae84)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
```
```
In kernel/panic.c (ffff8000100f61d4)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In kernel/exit.c (ffff8000100fd434)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sysctl.c (ffff800010103a1c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_cad_pid
```
```
In kernel/sys.c (ffff800010115138)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/sys.c:__arm64_sys_umask
```
```
In kernel/umh.c (ffff80001011add4)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/kthread.c (ffff800010129214)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kthread.c:kthread
```
```
In kernel/smpboot.c (ffff80001012facc)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/sched/core.c (ffff80001013aaa8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/loadavg.c (ffff80001013eba8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (ffff800010143ca8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/locking/osq_lock.c (ffff80001016a7bc)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffff800010176af4)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffff8000101910a8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/smp.c (ffff8000101bd93c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (ffff8000101c3084)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/acct.c (ffff8000101c78ec)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/acct.c:__arm64_sys_acct
```
```
In kernel/kexec.c (ffff8000101ca22c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (ffff8000101caecc)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
```
```
In kernel/audit.c (ffff8000101ebcb4)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffff8000101fa26c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffff800010206db0)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/blktrace.c (ffff800010236050)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
```
```
In kernel/irq_work.c (ffff80001025b020)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
```
```
In kernel/bpf/arraymap.c (ffff80001027b62c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:fd_array_map_delete_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_update_elem
```
```
In kernel/bpf/local_storage.c (ffff80001027eb60)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/devmap.c (ffff8000102867e4)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
```
```
In kernel/bpf/cpumap.c (ffff800010287a84)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
```
```
In kernel/bpf/xskmap.c (ffff8000102890a0)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
```
```
In kernel/bpf/stackmap.c (ffff80001028b9f4)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In kernel/events/core.c (ffff800010294178)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/events/core.c:task_clock_event_read
  - kernel/events/core.c:task_clock_event_stop
  - kernel/events/core.c:cpu_clock_event_update
  - kernel/events/core.c:perf_poll
  - kernel/events/core.c:__perf_event_task_sched_out
```
```
In kernel/events/ring_buffer.c (ffff8000102a27bc)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_output_begin
  - kernel/events/ring_buffer.c:perf_output_begin_backward
  - kernel/events/ring_buffer.c:perf_output_begin_forward
```
```
In mm/vmscan.c (ffff8000102c7c68)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (ffff80001030db84)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/swap_state.c (ffff800010321e04)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/hugetlb.c (ffff800010330adc)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/huge_memory.c (ffff800010354388)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
```
```
In mm/page_counter.c (ffff800010360d18)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (ffff800010363c38)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
```
```
In fs/file_table.c (ffff800010385664)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - fs/file_table.c:delayed_fput
```
```
In fs/file.c (ffff8000103b1e94)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
```
```
In fs/namespace.c (ffff8000103b66b0)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:delayed_mntput
```
```
In fs/eventpoll.c (ffff8000103f16a8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/aio.c (ffff8000103fac58)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In fs/posix_acl.c (ffff800010426650)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/proc/kcore.c (ffff80001044d950)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/page-io.c (ffff8000104a3a4c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
```
```
In lib/debug_locks.c (ffff800010629fc8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
```
```
In lib/generic-radix-tree.c (ffff800010638528)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
```
```
In lib/sbitmap.c (ffff800010669cc8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c824)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (ffff8000107afd4c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
```
In drivers/xen/events/events_2l.c (ffff800010832ed8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - drivers/xen/events/events_2l.c:evtchn_2l_handle_events
```
```
In drivers/xen/events/events_fifo.c (ffff800010833de0)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_buffer.c (ffff80001085d858)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/tty/tty_audit.c (ffff80001086346c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_exit
```
```
In drivers/tty/vt/vt.c (ffff80001087614c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010887554)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac49b8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In drivers/perf/arm-ccn.c (ffff800010b930a8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update
```
```
In net/socket.c (ffff800010ba4f58)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffff800010bab520)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/datagram.c (ffff800010bbce40)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffff800010bbd378)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/gen_estimator.c (ffff800010bbf628)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
```
```
In net/core/net_namespace.c (ffff800010bc0e24)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (ffff800010bcb0b8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/filter.c (ffff800010bfdf94)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/skmsg.c (ffff800010c0fd58)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (ffff800010c21b14)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_map_prog_update
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:sock_hash_release_progs
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_release_progs
  - net/core/sock_map.c:sock_map_free
```
```
In net/sched/act_api.c (ffff800010c4671c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_set_action_cookie
```
```
In net/netfilter/nf_log.c (ffff800010c55970)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/ipv4/route.c (ffff800010c5c8f4)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (ffff800010c68434)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6cc50)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (ffff800010c71288)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffff800010c78ad8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
```
```
In net/ipv4/tcp_cong.c (ffff800010c91244)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
```
In net/ipv4/datagram.c (ffff800010c95d48)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (ffff800010c96bbc)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (ffff800010c99778)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (ffff800010cab4f4)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (ffff800010cc12a8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd62fc)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
```
```
In net/unix/af_unix.c (ffff800010cf267c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/ipv6/af_inet6.c (ffff800010cf65a4)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/route.c (ffff800010d1496c)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffff800010d18f60)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1deb8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38ca8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/datagram.c (ffff800010d3d794)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
```
```
In net/ipv6/calipso.c (ffff800010d4d5a4)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
```
```
In net/packet/af_packet.c (ffff800010d5d6b8)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6ac18)
Location: arch/arm64/include/asm/cmpxchg.h:88
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_ops_register
```
</details>
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
