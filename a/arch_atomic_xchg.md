# Function: <code>arch_atomic_xchg</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b765d)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810e4e26)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff810f5345)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff81105057)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
```
```
In kernel/audit.c (ffffffff81151bae)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8115eed5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff81169b9f)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8118dad5)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811d2d2e)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff81247ff2)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff812f508a)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In net/core/dev.c (ffffffff8188ce25)
Location: arch/x86/include/asm/atomic.h:200
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
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
In kernel/smpboot.c (ffffffff810c075d)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810f0406)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff81100ae5)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff811108f8)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
```
```
In kernel/audit.c (ffffffff8115e86d)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8116bbff)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff81176a41)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8119b4b5)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811e30be)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8125c5d2)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff8130a17a)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81552328)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff816366ba)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff818ae075)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
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
In kernel/smpboot.c (ffffffff810c684d)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810f8a72)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff811092a3)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff8111a318)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
```
```
In kernel/audit.c (ffffffff8116ae70)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81178a23)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8118382a)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811a9075)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811fa28f)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff812777be)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff8132bfda)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582273)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8166a908)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff818f99a5)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81a57a25)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In kernel/smpboot.c (ffffffff810cf92d)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff81104882)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff81115683)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff8112987a)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffffffff81176d1b)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81184870)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8118f69a)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811b48a5)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8120735f)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff812872ae)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff8133ee2a)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3cad)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8168cff8)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff8192bb05)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81a8cf85)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In kernel/smpboot.c (ffffffff810d982d)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f3ed)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8110f632)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff81120f6e)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff81135754)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
```
```
In kernel/audit.c (ffffffff8118954e)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff811988b1)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811a451a)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811cd2a9)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8123082f)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff812b9acc)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/page_reporting.c (ffffffff8130cfb6)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff81378d5a)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c91b)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8173f0c8)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff819ff305)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81b8a035)
Location: arch/x86/include/asm/atomic.h:208
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104bd39)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In kernel/smpboot.c (ffffffff810d49dd)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c5ad)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8110c7f2)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff8111bbce)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff81130f12)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff81186f58)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81195a11)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811a166a)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811ca799)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8123a48f)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff812c553c)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff813044da)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
```
```
In mm/page_reporting.c (ffffffff81318f06)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff81386a9a)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670c6b)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8175aff8)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/iova.c (ffffffff817c1034)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In net/core/dev.c (ffffffff819ff055)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81b99b55)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104d869)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In kernel/smpboot.c (ffffffff810d65fd)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e3e1)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8110e622)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff8111c031)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff81131722)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff81187f82)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff811969b1)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811a22cc)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811cba3e)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8123ecbf)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff812cc1ee)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff8130bfda)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
```
```
In mm/page_reporting.c (ffffffff8131f0f6)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff8138df1a)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81653127)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8173ee98)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/iova.c (ffffffff817a4484)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In net/core/dev.c (ffffffff819e58f5)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81b88043)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81054f8d)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In kernel/smpboot.c (ffffffff810e99c7)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112db22)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8112dd8d)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff811536d9)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff811b03e2)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff811bfd6f)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811cbaab)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811f7ece)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff812796ef)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff813113fb)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff813572da)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/page_reporting.c (ffffffff8136c4d9)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff813db74a)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In block/blk-throttle.c (ffffffff815f662f)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:tg_may_dispatch
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4e97)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff817bf628)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/iova.c (ffffffff8182dbef)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In net/core/dev.c (ffffffff81a95da5)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81c50772)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In kernel/smpboot.c (ffffffff81104647)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/percpu-rwsem.c (ffffffff81f25df7)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8114ed9d)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff8117bf23)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff811e256b)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff811f3270)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811ff86b)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81231b7d)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff812cc884)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8137c4c3)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff813d01f0)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/page_reporting.c (ffffffff813ead77)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff814615aa)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eaba0)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff818fbb28)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196aeef)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In net/core/dev.c (ffffffff81c0ea55)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df1329)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In kernel/smpboot.c (ffffffff81129e87)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/sched/build_utility.c (ffffffff8116a3ea)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_poll_worker
```
```
In kernel/locking/percpu-rwsem.c (ffffffff820d1868)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8117dfdd)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff811b51a3)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff8122840f)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81239ffd)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8124728b)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8127e18d)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/bpf/memalloc.c (ffffffff8131c12e)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In kernel/events/core.c (ffffffff81334754)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff813f9c83)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff81455564)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/page_reporting.c (ffffffff81472f44)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff814f156a)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In io_uring/io_uring.c (ffffffff81788785)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_ops
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910dd0)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81a54f1e)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad53cf)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In net/core/dev.c (ffffffff81dbeb65)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc4f99)
Location: arch/x86/include/asm/atomic.h:206
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In kernel/cpu.c (ffffffff810fa375)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_ap_sync_alive
  - kernel/cpu.c:cpuhp_ap_report_dead
```
```
In kernel/sched/build_utility.c (ffffffff8117ab03)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_rtpoll_work
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82155bd8)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8118ec7d)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff811c9bf3)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff8123e9d9)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8125100d)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8125e31b)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8129ac0d)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/bpf/memalloc.c (ffffffff8134bc03)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In kernel/events/core.c (ffffffff81365494)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8142cbe3)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff8148b387)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/zsmalloc.c (ffffffff8149eed5)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
```
```
In mm/page_reporting.c (ffffffff814a76b2)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff81528b0a)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In io_uring/io_uring.c (ffffffff817c8e65)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_ops
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819544f0)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f4fe)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23b7f)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In net/core/dev.c (ffffffff81e2e875)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202a955)
Location: arch/x86/include/asm/atomic.h:119
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
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_ap_sync_alive
  - kernel/cpu.c:cpuhp_ap_report_dead
```
```
In kernel/sched/core.c (ffffffff811595d0)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_starting
```
```
In kernel/sched/build_utility.c (ffffffff81188533)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_rtpoll_work
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82238a18)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8119d62d)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff811d8f90)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff812588e1)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8126ae5d)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8127825b)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff812b628d)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/bpf/memalloc.c (ffffffff81372a17)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In kernel/events/core.c (ffffffff8138e5b4)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8146633c)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff814bac87)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/zsmalloc.c (ffffffff814ce635)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
```
```
In mm/page_reporting.c (ffffffff814d86e2)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff8155dc0a)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In io_uring/io_uring.c (ffffffff8180da15)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_ops
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d980)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1efe)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b795e6)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:queue_iova
```
```
In net/core/dev.c (ffffffff81eece05)
Location: arch/x86/include/asm/atomic.h:119
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fa445)
Location: arch/x86/include/asm/atomic.h:119
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c9cad)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810fdb92)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff8110dc63)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff81121e5a)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffffffff8116f33b)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8117ce90)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff81187cba)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811acec5)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811ff97f)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In fs/aio.c (ffffffff8133740a)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815974bd)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81652a78)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff818cbb05)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81a2c615)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In kernel/smpboot.c (ffffffff810b84cd)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/sched/core.c (ffffffff810c6afe)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_starting
```
```
In kernel/locking/osq_lock.c (ffffffff810edd92)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff810fe9c3)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff8111448a)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffffffff811624db)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81170003)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8117adfa)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8119fd55)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811f26cf)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8127171e)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff8132813a)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8158664d)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81632eb8)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff81885a45)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff819e9805)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In kernel/smpboot.c (ffffffff810c91dd)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810fad52)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff8110bb53)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff8111fd4a)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffffffff8116d10b)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8117ac60)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff81185a8a)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811aac95)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811fd74f)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8127d69e)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff81334eda)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815979fd)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81680e38)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff8191cb05)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81a981c5)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In kernel/smpboot.c (ffffffff810d174d)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff81105f22)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff81117063)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff8112bef1)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffffffff8117a901)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81188590)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811933d4)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811b8af5)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8120c58f)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8128d24e)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff813437da)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1e3d)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8169b488)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188c2c3)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In net/core/dev.c (ffffffff8193dfd5)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81aa4a35)
Location: arch/x86/include/asm/atomic.h:203
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
</details>
</li>
</ul>

## Differences
