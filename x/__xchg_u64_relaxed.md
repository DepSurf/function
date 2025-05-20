# Function: <code>__xchg_u64_relaxed</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/smp.c (c0000000000553e0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:smp_ipi_demux_relaxed
```
```
In arch/powerpc/sysdev/xive/common.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000db434)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_tce_xchg
```
```
In arch/powerpc/kvm/book3s_hv_rm_xive.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/panic.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/exit.c (c0000000001442e0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sysctl.c (c00000000014b868)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_do_cad_pid
```
```
In kernel/sys.c (c00000000015d0f0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/umh.c (c0000000001626b4)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/kthread.c (c000000000173aac)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kthread.c:kthread
```
```
In kernel/smpboot.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/sched/core.c (c000000000188568)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_ttwu_pending
```
```
In kernel/sched/loadavg.c (c00000000018db64)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
```
In kernel/sched/fair.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/locking/osq_lock.c (c0000000001c24a4)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_unlock
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/dma.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/smp.c (c000000000222b08)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/module.c (c000000000229634)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/module.c:do_free_init
```
```
In kernel/acct.c (c0000000002304f8)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/kexec.c (c000000000232cd4)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
```
```
In kernel/kexec_file.c (c0000000002349c0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
```
In kernel/audit.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/hung_task.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/trace/blktrace.c (c0000000002c1fec)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:__blk_trace_remove
```
```
In kernel/irq_work.c (c0000000002fec24)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/bpf/arraymap.c (c0000000003239d8)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:fd_array_map_delete_elem
  - kernel/bpf/arraymap.c:bpf_fd_array_map_update_elem
```
```
In kernel/bpf/local_storage.c (c000000000328bf4)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/devmap.c (c000000000331a44)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_update_elem
  - kernel/bpf/devmap.c:dev_map_delete_elem
```
```
In kernel/bpf/cpumap.c (c000000000332de8)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In kernel/bpf/xskmap.c (c0000000003343e0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/bpf/xskmap.c:xsk_map_delete_elem
```
```
In kernel/bpf/stackmap.c (c000000000337604)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
```
In kernel/events/core.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In mm/vmscan.c (c0000000003828b4)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - mm/vmscan.c:do_shrink_slab
```
```
In mm/vmalloc.c (c0000000003de778)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_work
```
```
In mm/swap_state.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In mm/hugetlb.c (c00000000040991c)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - mm/hugetlb.c:free_hpage_workfn
```
```
In mm/huge_memory.c (c00000000043b090)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In mm/page_counter.c (c00000000044bf2c)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:propagate_protected_usage
  - mm/page_counter.c:propagate_protected_usage
```
```
In mm/memcontrol.c (c00000000044d6e8)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:memory_max_write
```
```
In fs/file_table.c (c00000000047b64c)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - fs/file_table.c:delayed_fput
```
```
In fs/file.c (c0000000004adb98)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In fs/namespace.c (c0000000004b294c)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - fs/namespace.c:delayed_mntput
```
```
In fs/eventpoll.c (c0000000004faa14)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
```
In fs/aio.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In fs/posix_acl.c (c000000000535b84)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/proc/kcore.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In fs/ext4/page-io.c (c0000000005d0ab8)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
```
```
In lib/debug_locks.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In lib/generic-radix-tree.c (c0000000007deccc)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
```
```
In lib/sbitmap.c (c000000000820204)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_resize
```
```
In drivers/tty/tty_buffer.c (c0000000008fcb80)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/tty/tty_audit.c (c0000000009022ac)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_exit
```
```
In drivers/tty/vt/vt.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In net/socket.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In net/core/sock.c (c000000000c7e5a4)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_dst_check
```
```
In net/core/datagram.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In net/core/stream.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In net/core/gen_estimator.c (c000000000c988bc)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_kill_estimator
```
```
In net/core/net_namespace.c (c000000000c9b8b0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
```
```
In net/core/dev.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In net/core/filter.c (c000000000cde6d4)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/core/filter.c:bpf_setsockopt
```
```
In net/core/skmsg.c (c000000000cfbfa0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
```
In net/core/sock_map.c (c000000000d140f8)
Location: arch/powerpc/include/asm/cmpxchg.h:141
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
In net/sched/act_api.c (c000000000d44f0c)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
```
```
In net/netfilter/nf_log.c (c000000000d55824)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/ipv4/route.c (c000000000d5ed14)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/ip_sockglue.c (c000000000d6cd9c)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72264)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
```
```
In net/ipv4/tcp.c (c000000000d756fc)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In net/ipv4/tcp_cong.c (c000000000da0934)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_cong.c:tcp_set_default_congestion_control
```
```
In net/ipv4/datagram.c (c000000000da7588)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/datagram.c:__ip4_datagram_connect
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/raw.c (c000000000da7b34)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/udp.c (c000000000daabb0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
  - net/ipv4/udp.c:udp_sendmsg
```
```
In net/ipv4/af_inet.c (c000000000dc282c)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv4/ping.c (c000000000ddc864)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_bind
```
```
In net/ipv4/cipso_ipv4.c (c000000000df5e2c)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
```
```
In net/unix/af_unix.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In net/ipv6/af_inet6.c (c000000000e1bd3c)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_destroy_sock
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/route.c (c000000000e41728)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (c000000000e47b44)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4c11c)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
  - net/ipv6/ipv6_sockglue.c:ipv6_update_options
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b6ac)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/datagram.c (c000000000e71b78)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_local_rxpmtu
```
```
In net/ipv6/calipso.c (c000000000e85d8c)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
```
```
In net/packet/af_packet.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7ad8)
Location: arch/powerpc/include/asm/cmpxchg.h:141
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_ops_register
```
</details>
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
