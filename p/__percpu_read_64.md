# Function: <code>__percpu_read_64</code>

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
In arch/arm64/kernel/traps.c (ffff8000100955c4)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:handle_bad_stack
```
```
In kernel/cpu.c (ffff800011442210)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/trace/trace.c (ffff800010221f68)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_syscalls.c (ffff80001023e0dc)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
```
In kernel/trace/trace_kprobe.c (ffff800010251744)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffff80001025a75c)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
```
```
In kernel/bpf/helpers.c (ffff800010276924)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_local_storage
```
```
In mm/slub.c (ffff80001034c900)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc_track_caller
  - mm/slub.c:kfree
  - mm/slub.c:__kmalloc_node
  - mm/slub.c:__kmalloc
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_alloc_node_trace
  - mm/slub.c:kmem_cache_alloc_node
  - mm/slub.c:kmem_cache_alloc_trace
  - mm/slub.c:kmem_cache_alloc
  - mm/slub.c:put_cpu_partial
```
```
In drivers/dma/dmaengine.c (ffff8000107fbf78)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_find_channel
```
```
In net/ipv4/tcp_output.c (ffff800010c82978)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8c534)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/icmp.c (ffff800010ca4acc)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/icmp.c:icmp_push_reply
```
```
In net/ipv6/route.c (ffff800010d14850)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/icmp.c (ffff800010d2c5f4)
Location: arch/arm64/include/asm/percpu.h:111
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
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
