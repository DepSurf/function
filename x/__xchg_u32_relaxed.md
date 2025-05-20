# Function: <code>__xchg_u32_relaxed</code>

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
In arch/powerpc/kernel/smp.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bd18c)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_scan_interrupts
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In arch/powerpc/kvm/book3s_hv_rm_xive.c (c00000000012437c)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_scan_interrupts
```
```
In kernel/panic.c (c00000000013be44)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/exit.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/sysctl.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/sys.c (c00000000015b96c)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_umask
```
```
In kernel/umh.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/kthread.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/smpboot.c (c000000000179164)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/sched/core.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/sched/loadavg.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/sched/fair.c (c000000000193350)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/locking/osq_lock.c (c0000000001c2274)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (c0000000001d0484)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (c0000000001ec3e0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/dma.c (c000000000222974)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/dma.c:free_dma
  - kernel/dma.c:request_dma
```
```
In kernel/smp.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/module.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/acct.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/kexec.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/audit.c (c00000000025d330)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (c000000000271f80)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (c0000000002832f4)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/blktrace.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/irq_work.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/bpf/helpers.c (c00000000031ef88)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In kernel/events/core.c (c00000000033e438)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/vmscan.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In mm/swap_state.c (c0000000003f76dc)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/hugetlb.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In mm/page_counter.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In fs/file_table.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In fs/file.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In fs/namespace.c (c0000000004b2e08)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
```
```
In fs/eventpoll.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In fs/aio.c (c000000000502a10)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In fs/posix_acl.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In fs/proc/kcore.c (c000000000565098)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/ext4/page-io.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In lib/debug_locks.c (c0000000007cbdd4)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In lib/generic-radix-tree.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In drivers/tty/tty_buffer.c (c0000000008fcbe0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/tty/tty_audit.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In drivers/tty/vt/vt.c (c000000000917d90)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:tioclinux
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092e048)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/socket.c (c000000000c7877c)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - net/socket.c:do_recvmmsg
```
```
In net/core/sock.c (c000000000c81e24)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/datagram.c (c000000000c95f5c)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/core/datagram.c:__skb_wait_for_more_packets
```
```
In net/core/stream.c (c000000000c961ec)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_error
  - net/core/stream.c:sk_stream_wait_connect
```
```
In net/core/gen_estimator.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/core/dev.c (c000000000ca3fe0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/core/filter.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/core/skmsg.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/core/sock_map.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/sched/act_api.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/netfilter/nf_log.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv4/route.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv4/tcp.c (c000000000d785a8)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/tcp_input.c (c000000000d7ee0c)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_syn_flood_action
```
```
In net/ipv4/tcp_cong.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv4/datagram.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv4/udp.c (c000000000dab604)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/ipv4/af_inet.c (c000000000dbfd98)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
```
In net/ipv4/ping.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/unix/af_unix.c (c000000000e18bb0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_seqpacket_sendmsg
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv6/route.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv6/ip6_fib.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv6/datagram.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
```
```
In net/packet/af_packet.c (c000000000e962d4)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: arch/powerpc/include/asm/cmpxchg.h:106
Inline: True
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
