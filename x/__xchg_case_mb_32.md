# Function: <code>__xchg_case_mb_32</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In virt/kvm/kvm_main.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/panic.c (ffff8000100f61d4)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - kernel/panic.c:add_taint
```
```
In kernel/exit.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/sysctl.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/sys.c (ffff800010114064)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_umask
```
```
In kernel/umh.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/kthread.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/smpboot.c (ffff80001012facc)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/sched/core.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/sched/loadavg.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/sched/fair.c (ffff800010143ca8)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/locking/osq_lock.c (ffff80001016a5b8)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffff800010176af4)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffff80001018c0b0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/smp.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/module.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/acct.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/kexec.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/audit.c (ffff8000101ebcb4)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffff8000101fa26c)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffff800010206db0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/blktrace.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/irq_work.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/bpf/xskmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In kernel/events/core.c (ffff800010293a18)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In kernel/events/ring_buffer.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In mm/vmscan.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In mm/vmalloc.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In mm/swap_state.c (ffff800010321e04)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/hugetlb.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In mm/huge_memory.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In mm/page_counter.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In mm/memcontrol.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In fs/file_table.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In fs/file.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In fs/namespace.c (ffff8000103b66b0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
```
```
In fs/eventpoll.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In fs/aio.c (ffff8000103fac58)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In fs/posix_acl.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In fs/proc/kcore.c (ffff80001044d950)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/page-io.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In lib/debug_locks.c (ffff800010629fc8)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
```
```
In lib/generic-radix-tree.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In lib/sbitmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c824)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/acpi/apei/ghes.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In drivers/xen/events/events_2l.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In drivers/xen/events/events_fifo.c (ffff800010833de0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
  - drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events
```
```
In drivers/tty/tty_buffer.c (ffff80001085d8a8)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/tty/tty_audit.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In drivers/tty/vt/vt.c (ffff80001087614c)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010887554)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac49b8)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In drivers/perf/arm-ccn.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/socket.c (ffff800010ba4f58)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (ffff800010bab520)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (ffff800010bbce40)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (ffff800010bbd378)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/gen_estimator.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/core/dev.c (ffff800010bcb0b8)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/filter.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/core/skmsg.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/core/sock_map.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/sched/act_api.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv4/route.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv4/tcp.c (ffff800010c71288)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (ffff800010c78ad8)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
```
```
In net/ipv4/tcp_cong.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv4/datagram.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv4/udp.c (ffff800010c99fac)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (ffff800010cab4f4)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/ping.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/unix/af_unix.c (ffff800010cf267c)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv6/route.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv6/datagram.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
```
In net/packet/af_packet.c (ffff800010d5d6b8)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:59
Inline: False
```
**Symbols:**

```
ffff80001018c0b0-ffff80001018c0d0: __xchg_case_mb_32.constprop.0 (STB_LOCAL)
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
