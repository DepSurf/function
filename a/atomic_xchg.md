# Function: <code>atomic_xchg</code>

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
In kernel/smpboot.c (ffffffff810a4010)
Location: arch/x86/include/asm/atomic.h:180
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/mutex.c (ffffffff81821a5c)
Location: arch/x86/include/asm/atomic.h:180
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
```
In kernel/locking/osq_lock.c (ffffffff810ca326)
Location: arch/x86/include/asm/atomic.h:180
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/debug/debug_core.c (ffffffff8112fdaf)
Location: arch/x86/include/asm/atomic.h:180
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8113a459)
Location: arch/x86/include/asm/atomic.h:180
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81158a27)
Location: arch/x86/include/asm/atomic.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811788f8)
Location: arch/x86/include/asm/atomic.h:180
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff811d2cbb)
Location: arch/x86/include/asm/atomic.h:180
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In fs/aio.c (ffffffff8125b488)
Location: arch/x86/include/asm/atomic.h:180
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In net/core/dev.c (ffffffff8171506a)
Location: arch/x86/include/asm/atomic.h:180
Inline: True
Inline callers:
  - net/core/dev.c:net_enable_timestamp
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
In kernel/smpboot.c (ffffffff810a7750)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/mutex.c (ffffffff8189bebc)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
```
In kernel/locking/osq_lock.c (ffffffff810cecb6)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk.c (ffffffff810dd079)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff810eb0c4)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff811380b3)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8114297f)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811632b0)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff81188ecb)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff811f0aad)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In fs/aio.c (ffffffff8128407a)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In net/core/dev.c (ffffffff8177d0ac)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - net/core/dev.c:net_enable_timestamp
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
In kernel/smpboot.c (ffffffff810ad400)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810d58d2)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk.c (ffffffff810e371d)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff810f2a97)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
```
```
In kernel/debug/debug_core.c (ffffffff81141e47)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8114c75f)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8116e5e0)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8119829b)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff812014ad)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In fs/aio.c (ffffffff81297cea)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In net/core/dev.c (ffffffff817aa6e6)
Location: arch/x86/include/asm/atomic.h:189
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
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
In kernel/smpboot.c (ffffffff810a9fd0)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810d4852)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff810e4cbb)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff810f3557)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
```
```
In kernel/audit.c (ffffffff811363d5)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81143684)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8114e6c8)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81171820)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8119ff2c)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8120c348)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In fs/aio.c (ffffffff812a5b7a)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In net/core/dev.c (ffffffff817c8d46)
Location: arch/x86/include/asm/atomic.h:195
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
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
In kernel/smpboot.c (ffffffff810b0830)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810dc7d6)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff810ecf41)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff810fcf77)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
```
```
In kernel/audit.c (ffffffff8114355d)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81150338)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8115af58)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8117e9b0)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811b384f)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff81225a42)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In fs/aio.c (ffffffff812c909a)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In net/core/dev.c (ffffffff818429e6)
Location: arch/x86/include/asm/atomic.h:196
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
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
In kernel/smpboot.c (ffffffff810b765d)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810e4e26)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff810f5345)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff81105057)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
```
```
In kernel/audit.c (ffffffff81151bae)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8115eed5)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff81169b9f)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8118dad5)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811d2d2e)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff81247ff2)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff812f508a)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In net/core/dev.c (ffffffff8188ce25)
Location: include/asm-generic/atomic-instrumented.h:43
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
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810f0406)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff81100ae5)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff811108f8)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
```
```
In kernel/audit.c (ffffffff8115e86d)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8116bbff)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff81176a41)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8119b4b5)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811e30be)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8125c5d2)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff8130a17a)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81552328)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff816366ba)
Location: include/asm-generic/atomic-instrumented.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff818ae075)
Location: include/asm-generic/atomic-instrumented.h:43
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
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810f8a72)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff811092a3)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff8111a318)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
```
```
In kernel/audit.c (ffffffff8116ae70)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81178a23)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8118382a)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811a9075)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811fa28f)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff812777be)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff8132bfda)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582273)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8166a908)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff818f99a5)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81a57a25)
Location: include/asm-generic/atomic-instrumented.h:611
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
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff81104882)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff81115683)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff8112987a)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffffffff81176d1b)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81184870)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8118f69a)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811b48a5)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8120735f)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff812872ae)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff8133ee2a)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3cad)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8168cff8)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff8192bb05)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81a8cf85)
Location: include/asm-generic/atomic-instrumented.h:611
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
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110f3ed)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8110f632)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff81120f6e)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff81135754)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
```
```
In kernel/audit.c (ffffffff8118954e)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff811988b1)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811a451a)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811cd2a9)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8123082f)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff812b9acc)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/page_reporting.c (ffffffff8130cfb6)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff81378d5a)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c91b)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8173f0c8)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff819ff305)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81b8a035)
Location: include/asm-generic/atomic-instrumented.h:612
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
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In kernel/smpboot.c (ffffffff810d49dd)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c5ad)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8110c7f2)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff8111bbce)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff81130f12)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff81186f58)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81195a11)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811a166a)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811ca799)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8123a48f)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff812c553c)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff813044da)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
```
```
In mm/page_reporting.c (ffffffff81318f06)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff81386a9a)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670c6b)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8175aff8)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/iova.c (ffffffff817c1034)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In net/core/dev.c (ffffffff819ff055)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81b99b55)
Location: include/asm-generic/atomic-instrumented.h:612
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
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In kernel/smpboot.c (ffffffff810d65fd)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e3e1)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8110e622)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff8111c031)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff81131722)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff81187f82)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff811969b1)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811a22cc)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811cba3e)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8123ecbf)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff812cc1ee)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff8130bfda)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
```
```
In mm/page_reporting.c (ffffffff8131f0f6)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff8138df1a)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81653127)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8173ee98)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/iova.c (ffffffff817a4484)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In net/core/dev.c (ffffffff819e58f5)
Location: include/asm-generic/atomic-instrumented.h:612
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81b88043)
Location: include/asm-generic/atomic-instrumented.h:612
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
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_cpu
```
```
In kernel/smpboot.c (ffffffff810e99c7)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112db22)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8112dd8d)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff811536d9)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff811b03e2)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff811bfd6f)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811cbaab)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811f7ece)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff812796ef)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff813113fb)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff813572da)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/page_reporting.c (ffffffff8136c4d9)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff813db74a)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In block/blk-throttle.c (ffffffff815f662f)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:throtl_downgrade_check
  - block/blk-throttle.c:tg_may_dispatch
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4e97)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff817bf628)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/iova.c (ffffffff8182dbef)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - drivers/iommu/iova.c:queue_iova
```
```
In net/core/dev.c (ffffffff81a95da5)
Location: include/linux/atomic/atomic-instrumented.h:445
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81c50772)
Location: include/linux/atomic/atomic-instrumented.h:445
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
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/percpu-rwsem.c (ffffffff81f25df7)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8114ed9d)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff8117bf23)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff811e256b)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff811f3270)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811ff86b)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff81231b7d)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff812cc884)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8137c4c3)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff813d01f0)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/page_reporting.c (ffffffff813ead77)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff814615aa)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eaba0)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff818fbb28)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196aeef)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In net/core/dev.c (ffffffff81c0ea55)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df1329)
Location: include/linux/atomic/atomic-instrumented.h:470
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
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/sched/build_utility.c (ffffffff8116a3ea)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_poll_worker
```
```
In kernel/locking/percpu-rwsem.c (ffffffff820d1868)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8117dfdd)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff811b51a3)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff8122840f)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81239ffd)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8124728b)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8127e18d)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/bpf/memalloc.c (ffffffff8131c12e)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In kernel/events/core.c (ffffffff81334754)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff813f9c83)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff81455564)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/page_reporting.c (ffffffff81472f44)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff814f156a)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In io_uring/io_uring.c (ffffffff81788785)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_ops
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910dd0)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81a54f1e)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad53cf)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In net/core/dev.c (ffffffff81dbeb65)
Location: include/linux/atomic/atomic-instrumented.h:470
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc4f99)
Location: include/linux/atomic/atomic-instrumented.h:470
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
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_ap_sync_alive
  - kernel/cpu.c:cpuhp_ap_report_dead
```
```
In kernel/sched/build_utility.c (ffffffff8117ab03)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_rtpoll_work
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82155bd8)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8118ec7d)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff811c9bf3)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff8123e9d9)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8125100d)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8125e31b)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8129ac0d)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/bpf/memalloc.c (ffffffff8134bc03)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In kernel/events/core.c (ffffffff81365494)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8142cbe3)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff8148b387)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/zsmalloc.c (ffffffff8149eed5)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
```
```
In mm/page_reporting.c (ffffffff814a76b2)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff81528b0a)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In io_uring/io_uring.c (ffffffff817c8e65)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_ops
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819544f0)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f4fe)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23b7f)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In net/core/dev.c (ffffffff81e2e875)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
```
```
In net/packet/af_packet.c (ffffffff8202a955)
Location: include/linux/atomic/atomic-instrumented.h:1116
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
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_ap_sync_alive
  - kernel/cpu.c:cpuhp_ap_report_dead
```
```
In kernel/sched/core.c (ffffffff811595d0)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_starting
```
```
In kernel/sched/build_utility.c (ffffffff81188533)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_rtpoll_work
```
```
In kernel/locking/percpu-rwsem.c (ffffffff82238a18)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
```
In kernel/locking/osq_lock.c (ffffffff8119d62d)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/rcu/tree.c (ffffffff811d8f90)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/audit.c (ffffffff812588e1)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8126ae5d)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8127825b)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff812b628d)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/bpf/memalloc.c (ffffffff81372a17)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In kernel/events/core.c (ffffffff8138e5b4)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8146633c)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/memcontrol.c (ffffffff814bac87)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
```
In mm/zsmalloc.c (ffffffff814ce635)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
```
```
In mm/page_reporting.c (ffffffff814d86e2)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/aio.c (ffffffff8155dc0a)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In io_uring/io_uring.c (ffffffff8180da15)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_ops
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d980)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81af1efe)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b795e6)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:queue_iova
```
```
In net/core/dev.c (ffffffff81eece05)
Location: include/linux/atomic/atomic-instrumented.h:1116
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820fa445)
Location: include/linux/atomic/atomic-instrumented.h:1116
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffff80001012facc)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffff80001016a5b8)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffff800010176af4)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffff8000101910a8)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffff8000101ebcb4)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffff8000101fa26c)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffff800010206db0)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/events/core.c (ffff800010293a18)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffff800010321e04)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffff8000103fac58)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c824)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffff80001085d8a8)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac49b8)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In net/core/dev.c (ffff800010bcb0b8)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffff800010d5d6b8)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffe0000e350a)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/printk/printk_safe.c (ffffffe000111d4e)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffe00012454e)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffffffe000160406)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/hung_task.c (ffffffe0001695fc)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/bpf/helpers.c (ffffffe0001aed50)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:copy_map_value_locked
  - kernel/bpf/helpers.c:bpf_spin_lock
```
```
In kernel/events/core.c (ffffffe0001c3a4c)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffe000222ea4)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffe0002aa684)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d90ba)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffe000536656)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/packet/af_packet.c (ffffffe000892d56)
Location: arch/riscv/include/asm/atomic.h:301
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
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
In kernel/smpboot.c (ffffffff810c9cad)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810fdb92)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff8110dc63)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff81121e5a)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffffffff8116f33b)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8117ce90)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff81187cba)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811acec5)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811ff97f)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In fs/aio.c (ffffffff8133740a)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815974bd)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81652a78)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff818cbb05)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81a2c615)
Location: include/asm-generic/atomic-instrumented.h:611
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
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/sched/core.c (ffffffff810c6afe)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_starting
```
```
In kernel/locking/osq_lock.c (ffffffff810edd92)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff810fe9c3)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff8111448a)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffffffff811624db)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81170003)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff8117adfa)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff8119fd55)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811f26cf)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8127171e)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff8132813a)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8158664d)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81632eb8)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff81885a45)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff819e9805)
Location: include/asm-generic/atomic-instrumented.h:611
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
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff810fad52)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff8110bb53)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff8111fd4a)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffffffff8116d10b)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff8117ac60)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff81185a8a)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811aac95)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff811fd74f)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8127d69e)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff81334eda)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815979fd)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff81680e38)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In net/core/dev.c (ffffffff8191cb05)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81a981c5)
Location: include/asm-generic/atomic-instrumented.h:611
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
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/smpboot.c:cpu_set_state_online
```
```
In kernel/locking/osq_lock.c (ffffffff81105f22)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/locking/osq_lock.c:osq_lock
```
```
In kernel/printk/printk_safe.c (ffffffff81117063)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
```
In kernel/rcu/tree.c (ffffffff8112bef1)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In kernel/audit.c (ffffffff8117a901)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
```
In kernel/debug/debug_core.c (ffffffff81188590)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/debug_core.c:kgdb_cpu_enter
```
```
In kernel/hung_task.c (ffffffff811933d4)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff811b8af5)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_read
```
```
In kernel/events/core.c (ffffffff8120c58f)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swap_state.c (ffffffff8128d24e)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - mm/swap_state.c:swap_cluster_readahead
```
```
In fs/aio.c (ffffffff813437da)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - fs/aio.c:kill_ioctx
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1e3d)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
```
In drivers/tty/tty_buffer.c (ffffffff8169b488)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_free_all
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188c2c3)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
```
```
In net/core/dev.c (ffffffff8193dfd5)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - net/core/dev.c:netstamp_clear
```
```
In net/packet/af_packet.c (ffffffff81aa4a35)
Location: include/asm-generic/atomic-instrumented.h:611
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
</details>
</li>
</ul>

## Differences
