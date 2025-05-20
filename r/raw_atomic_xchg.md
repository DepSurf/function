# Function: <code>raw_atomic_xchg</code>

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
In kernel/cpu.c (ffffffff810fa375)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_ap_sync_alive
  - kernel/cpu.c:cpuhp_ap_report_dead
```
```
In kernel/sched/build_utility.c (ffffffff8117ab03)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_rtpoll_work
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82155bd8)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8118ec7d)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff811c9bf3)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff8123e9d9)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8125100d)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8125e31b)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8129ac0d)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/bpf/memalloc.c (ffffffff8134bc03)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In kernel/events/core.c (ffffffff81365494)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8142cbe3)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff8148b387)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/zsmalloc.c (ffffffff8149eed5)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
```
```
In mm/page_reporting.c (ffffffff814a76b2)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff81528b0a)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In io_uring/io_uring.c (ffffffff817c8e65)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_ops
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819544f0)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f4fe)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23b7f)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In net/core/dev.c (ffffffff81e2e875)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202a955)
Location: include/linux/atomic/atomic-arch-fallback.h:1901
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In kernel/cpu.c (ffffffff81103795)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_ap_sync_alive
  - kernel/cpu.c:cpuhp_ap_report_dead
```
```
In kernel/sched/core.c (ffffffff811595d0)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_starting
```
```
In kernel/sched/build_utility.c (ffffffff81188533)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_rtpoll_work
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82238a18)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8119d62d)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff811d8f90)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff812588e1)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8126ae5d)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8127825b)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff812b628d)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/bpf/memalloc.c (ffffffff81372a17)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In kernel/events/core.c (ffffffff8138e5b4)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8146633c)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff814bac87)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/zsmalloc.c (ffffffff814ce635)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
```
```
In mm/page_reporting.c (ffffffff814d86e2)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff8155dc0a)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In io_uring/io_uring.c (ffffffff8180da15)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_ops
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d980)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1efe)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b795e6)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:queue_iova
```
```
In net/core/dev.c (ffffffff81eece05)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fa445)
Location: include/linux/atomic/atomic-arch-fallback.h:1910
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
