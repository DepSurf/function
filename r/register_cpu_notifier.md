# Function: <code>register_cpu_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_cpu_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081230)
Location: kernel/cpu.c:196
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_cluster_probe
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/cpu.c:smpboot_thread_init
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/printk/printk.c:printk_late_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/time/timer.c:init_timers
  - kernel/time/hrtimer.c:hrtimers_init
  - kernel/smp.c:call_function_init
  - kernel/relay.c:relay_init
  - kernel/padata.c:padata_alloc
  - mm/page_alloc.c:page_alloc_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-iopoll.c:blk_iopoll_setup
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq-cpu.c:blk_mq_cpu_init
  - lib/radix-tree.c:radix_tree_init
  - lib/percpu_counter.c:percpu_counter_startup
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
```
**Symbols:**

```
ffffffff81081230-ffffffff8108126b: register_cpu_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_cpu_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810837b0)
Location: kernel/cpu.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - kernel/printk/printk.c:printk_late_init
  - kernel/relay.c:relay_init
  - kernel/padata.c:padata_alloc
  - mm/page_alloc.c:page_alloc_init
  - mm/page-writeback.c:page_writeback_init
  - mm/vmscan.c:kswapd_init
  - mm/compaction.c:kcompactd_init
  - mm/slub.c:kmem_cache_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/buffer.c:buffer_init
  - block/blk-softirq.c:blk_softirq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq-cpu.c:blk_mq_cpu_init
  - lib/radix-tree.c:radix_tree_init
  - lib/percpu_counter.c:percpu_counter_startup
  - lib/irq_poll.c:irq_poll_setup
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_probe
```
**Symbols:**

```
ffffffff810837b0-ffffffff810837eb: register_cpu_notifier (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
