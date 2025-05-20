# Function: <code>__xchg_case_mb_8</code>

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
In virt/kvm/kvm_main.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/panic.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/exit.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/sysctl.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/sys.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/umh.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/kthread.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/smpboot.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/sched/core.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/sched/loadavg.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/sched/fair.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/locking/osq_lock.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/printk/printk_safe.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/rcu/tree.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/smp.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/module.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/acct.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/kexec.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/kexec_file.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/audit.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/debug/debug_core.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/hung_task.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/trace/blktrace.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/irq_work.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/bpf/xskmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/bpf/stackmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/events/core.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In mm/vmscan.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In mm/vmalloc.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In mm/swap_state.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In mm/hugetlb.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In mm/huge_memory.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In mm/page_counter.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In mm/memcontrol.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In fs/file_table.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In fs/file.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In fs/namespace.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In fs/eventpoll.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In fs/aio.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In fs/posix_acl.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In fs/proc/kcore.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In fs/ext4/page-io.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In lib/debug_locks.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In lib/generic-radix-tree.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In lib/sbitmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In drivers/acpi/apei/ghes.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In drivers/xen/events/events_2l.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In drivers/xen/events/events_fifo.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In drivers/tty/tty_buffer.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In drivers/tty/tty_audit.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In drivers/tty/vt/vt.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In drivers/media/cec/cec-pin.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In drivers/perf/arm-ccn.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/socket.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/core/sock.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/core/datagram.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/core/stream.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/core/gen_estimator.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/core/net_namespace.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/core/dev.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/core/filter.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/core/skmsg.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/core/sock_map.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/sched/act_api.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/netfilter/nf_log.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/route.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/ip_sockglue.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/tcp.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/tcp_input.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/tcp_cong.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/datagram.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/raw.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/udp.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/af_inet.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/ping.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/unix/af_unix.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv6/af_inet6.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv6/route.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv6/ip6_fib.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv6/datagram.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/ipv6/calipso.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/packet/af_packet.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:57
Inline: False
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
