# Function: <code>cpuhp_setup_state_nocalls</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81f87f39)
Location: include/linux/cpuhotplug.h:135
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
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
In arch/x86/xen/enlighten.c (ffffffff8108297c)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81fd07b5)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/kvm.c (ffffffff81fd8387)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff81fe00f4)
Location: include/linux/cpuhotplug.h:184
Inline: True
```
```
In kernel/printk/printk.c (ffffffff81fe39c8)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/page_alloc.c (ffffffff81feda05)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/vmscan.c (ffffffff81fee6c2)
Location: include/linux/cpuhotplug.h:184
Inline: True
```
```
In mm/vmstat.c (ffffffff81fee859)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:setup_vmstat
```
```
In mm/compaction.c (ffffffff81ff0d60)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/slub.c (ffffffff81ff38ba)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff81ff4637)
Location: include/linux/cpuhotplug.h:184
Inline: True
```
```
In fs/buffer.c (ffffffff81ff7108)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff8200317d)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In block/blk-mq.c (ffffffff820031c7)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In lib/radix-tree.c (ffffffff8200681a)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
```
```
In lib/percpu_counter.c (ffffffff82006a05)
Location: include/linux/cpuhotplug.h:184
Inline: True
```
```
In lib/irq_poll.c (ffffffff820073e0)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff8200c8e8)
Location: include/linux/cpuhotplug.h:184
Inline: True
```
```
In drivers/xen/events/events_fifo.c (ffffffff8200ea6b)
Location: include/linux/cpuhotplug.h:184
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81743b82)
Location: include/linux/cpuhotplug.h:184
Inline: True
```
```
In net/core/dev.c (ffffffff820275a2)
Location: include/linux/cpuhotplug.h:184
Inline: True
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
In arch/x86/xen/enlighten.c (ffffffff8101986c)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff820b1170)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/kvm.c (ffffffff820b91d7)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff820c0f08)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In kernel/printk/printk.c (ffffffff820c4464)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/page_alloc.c (ffffffff820cf64a)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/vmscan.c (ffffffff820d0716)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In mm/vmstat.c (ffffffff820d08f1)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff820d318f)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/slub.c (ffffffff820d6064)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff820d6e23)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In fs/buffer.c (ffffffff820d98ac)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff820e6a46)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffff820e7a4b)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In lib/irq_poll.c (ffffffff820e8416)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff820ee1a0)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In drivers/xen/events/events_fifo.c (ffffffff820f0525)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In net/core/dev.c (ffffffff8210ab3d)
Location: include/linux/cpuhotplug.h:197
Inline: True
```
```
In lib/radix-tree.c (ffffffff821118d2)
Location: include/linux/cpuhotplug.h:197
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/xen/enlighten.c (ffffffff8101a14c)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826b7982)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/kvm.c (ffffffff826bfb02)
Location: include/linux/cpuhotplug.h:225
Inline: True
```
```
In kernel/softirq.c (ffffffff826c9103)
Location: include/linux/cpuhotplug.h:225
Inline: True
```
```
In kernel/printk/printk.c (ffffffff826cc703)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/page_alloc.c (ffffffff826d806f)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/vmscan.c (ffffffff826d914f)
Location: include/linux/cpuhotplug.h:225
Inline: True
```
```
In mm/vmstat.c (ffffffff826d9328)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff826dbbb4)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/slub.c (ffffffff826decac)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff826dfa8e)
Location: include/linux/cpuhotplug.h:225
Inline: True
```
```
In fs/buffer.c (ffffffff826e25a6)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff826ef7c7)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffff826f07bb)
Location: include/linux/cpuhotplug.h:225
Inline: True
```
```
In lib/irq_poll.c (ffffffff826f11fb)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff826f78c2)
Location: include/linux/cpuhotplug.h:225
Inline: True
```
```
In drivers/xen/events/events_fifo.c (ffffffff826f9d2f)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In net/core/dev.c (ffffffff827144e6)
Location: include/linux/cpuhotplug.h:225
Inline: True
```
```
In lib/radix-tree.c (ffffffff8271bcdb)
Location: include/linux/cpuhotplug.h:225
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/xen/enlighten.c (ffffffff8101ab25)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff826e1694)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/kvm.c (ffffffff826e9973)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff826f32a6)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff826f68a2)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/page_alloc.c (ffffffff82702513)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/vmscan.c (ffffffff827035f9)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (ffffffff827037f3)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff82706091)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/slub.c (ffffffff827090f5)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff82709f8b)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff8270cb50)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff82719c32)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffff8271ac26)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff8271b135)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff82721967)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_fifo.c (ffffffff827240e5)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In net/core/dev.c (ffffffff8273e6f7)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffff82746555)
Location: include/linux/cpuhotplug.h:224
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/xen/enlighten.c (ffffffff8101b2f5)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82897656)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/kvm.c (ffffffff828a05be)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff828aa095)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff828ad7dc)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/page_alloc.c (ffffffff828b9c39)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/vmscan.c (ffffffff828bad22)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (ffffffff828baf1c)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828bd836)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/slub.c (ffffffff828c039a)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff828c1118)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff828c3d76)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff828d1c2b)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffff828d2b55)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff828d305a)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff828d9a7a)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_fifo.c (ffffffff828dc2be)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In net/core/dev.c (ffffffff828f878a)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffff829007f3)
Location: include/linux/cpuhotplug.h:230
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/xen/enlighten.c (ffffffff8101ce15)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828af205)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/kvm.c (ffffffff828b877b)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff828c2890)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff828c6196)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmscan.c (ffffffff828d21ac)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (ffffffff828d237d)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828d4e2d)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff828d6d6b)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff828d9729)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff828da49f)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff828dd166)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff828ebc26)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffff828ecbb1)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff828ed08e)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff828f38a5)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_fifo.c (ffffffff828f6ba2)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In net/core/dev.c (ffffffff829141fb)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffff8291d412)
Location: include/linux/cpuhotplug.h:235
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/xen/enlighten.c (ffffffff8101d795)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b253e)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd857)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/kvm.c (ffffffff828bec56)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff828cae99)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff828ce7db)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmscan.c (ffffffff828da62a)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (ffffffff828da7ef)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828dd2bc)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff828df1fc)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff828e1b7c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff828e2946)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff828e58d8)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff828f47f5)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffff828f5cf6)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff828f61c7)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff828fcab7)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_fifo.c (ffffffff828ffbf9)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In net/core/dev.c (ffffffff8291df7e)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffff82927294)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/xen/enlighten.c (ffffffff8101fc05)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82cd7684)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff82cd8587)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1c0f)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/kvm.c (ffffffff82ce2f51)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff82ced1c5)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff82cefc2f)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmstat.c (ffffffff82cf8c24)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff82cfa741)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff82cfc5a7)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff82cff13b)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff82cffa1d)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff82d00faf)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff82d08bc5)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffff82d093b0)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff82d098bb)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In lib/radix-tree.c (ffffffff82d0d071)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
```
```
In drivers/acpi/processor_driver.c (ffffffff82d13333)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_fifo.c (ffffffff82d16fa2)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In net/core/dev.c (ffffffff82d2d084)
Location: include/linux/cpuhotplug.h:242
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
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
In arch/x86/xen/enlighten.c (ffffffff810206ac)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff82fc36bd)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff82fc4959)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup
```
```
In arch/x86/kernel/kvm.c (ffffffff82fd0243)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff82fd981f)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff82fdc480)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmstat.c (ffffffff82fe58fc)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff82fe743d)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff82fe8fc2)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff82febae7)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff82fec3d9)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff82fee1ee)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-mq.c (ffffffff82ff618c)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In lib/percpu_counter.c (ffffffff82ff69ab)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff82ff6e60)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In lib/radix-tree.c (ffffffff82ffaa75)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
```
```
In drivers/acpi/processor_driver.c (ffffffff83000e07)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_base.c (ffffffff83004957)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In net/core/dev.c (ffffffff8301bb6c)
Location: include/linux/cpuhotplug.h:247
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
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
In arch/x86/xen/enlighten.c (ffffffff81022a4c)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff831cdc9f)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff831cf21e)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
```
In arch/x86/kernel/kvm.c (ffffffff831daf7a)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff831e4173)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff831e71e0)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmstat.c (ffffffff831eff02)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff831f1b75)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff831f37fc)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff831f6531)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff831f6c07)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff831f8a2b)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-mq.c (ffffffff83200e5e)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In lib/percpu_counter.c (ffffffff83201693)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff83201b45)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In lib/radix-tree.c (ffffffff8320568c)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
```
```
In drivers/acpi/processor_driver.c (ffffffff8320beee)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_base.c (ffffffff8320f40f)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In net/core/dev.c (ffffffff83226ca9)
Location: include/linux/cpuhotplug.h:255
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
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
In arch/x86/xen/enlighten.c (ffffffff810268ec)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff832afe01)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff832b15bf)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
```
In arch/x86/kernel/kvm.c (ffffffff832be2a3)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff832c7d50)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff832cb371)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmstat.c (ffffffff832d567c)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff832d770b)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff832d9a38)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff832dcb95)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/migrate.c (ffffffff832dd2ba)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_on_reclaim_init
```
```
In mm/memcontrol.c (ffffffff832dd733)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff832df9a3)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-mq.c (ffffffff832e8534)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In lib/percpu_counter.c (ffffffff832e8cff)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff832e921c)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In lib/radix-tree.c (ffffffff832ed366)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
```
```
In drivers/acpi/processor_driver.c (ffffffff832f467a)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_base.c (ffffffff832f83b6)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In net/core/dev.c (ffffffff83310ffe)
Location: include/linux/cpuhotplug.h:314
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
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
In arch/x86/xen/enlighten.c (ffffffff8102aa8c)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83460ea3)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff834628a1)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
```
In arch/x86/kernel/kvm.c (ffffffff8346fe82)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff8347ad6f)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff8347ea11)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmstat.c (ffffffff83489ecc)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff8348c29f)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff8348e9fd)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff83492545)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff83492f7c)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff834956c3)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-mq.c (ffffffff8349fb59)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In lib/percpu_counter.c (ffffffff834a044f)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff834a0950)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In lib/radix-tree.c (ffffffff834a5134)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
```
```
In drivers/acpi/processor_driver.c (ffffffff834ac90f)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_base.c (ffffffff834b0bee)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In net/core/dev.c (ffffffff834cad60)
Location: include/linux/cpuhotplug.h:320
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
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
In arch/x86/xen/enlighten.c (ffffffff810316ac)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff83e7b725)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff83e82cd1)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff83e84cc4)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
```
In arch/x86/kernel/kvm.c (ffffffff83e96697)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff83ea5975)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff83eaa7e2)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmstat.c (ffffffff83eba826)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff83ebd5b5)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff83ec0c99)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff83ec6195)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff83ec6ef5)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff83eca1ec)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-mq.c (ffffffff83ed86c6)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In lib/percpu_counter.c (ffffffff83ed92bb)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff83ed99f3)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff83ee52fc)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_base.c (ffffffff83eeaa1f)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In net/core/dev.c (ffffffff83f0cc35)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffff83f1c3d4)
Location: include/linux/cpuhotplug.h:324
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/xen/enlighten.c (ffffffff810316ac)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8369dde4)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff836a601d)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff836a81c7)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
```
In arch/x86/kernel/kvm.c (ffffffff836ba217)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff836ca045)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff836cf7a2)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmstat.c (ffffffff836dfe36)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff836e5a65)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff836e65c5)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init_cpuhp
```
```
In mm/slub.c (ffffffff836eb2a5)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff836ebf05)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff836ef22c)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-mq.c (ffffffff836fd9f6)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In lib/percpu_counter.c (ffffffff836fed2b)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff836ff493)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff8370acf1)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_base.c (ffffffff8371040f)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In net/core/dev.c (ffffffff83732fd5)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffff83742c64)
Location: include/linux/cpuhotplug.h:322
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/xen/enlighten.c (ffffffff8103799c)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff838cd9a4)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_register
```
```
In arch/x86/kernel/cpu/vmware.c (ffffffff838d8705)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/vmware.c:vmware_platform_setup
```
```
In arch/x86/kernel/kvm.c (ffffffff838eab47)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff838facf5)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff83900bb2)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/time/tick-sched.c (ffffffff8390585b)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/crash_core.c (ffffffff83906385)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_hotplug_init
```
```
In mm/vmstat.c (ffffffff839126e6)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff83918295)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff83918e25)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init_cpuhp
```
```
In mm/slub.c (ffffffff8391a525)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff8391eec5)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff8392227c)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-mq.c (ffffffff839310b5)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init
```
```
In lib/percpu_counter.c (ffffffff8393266b)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff83932ce3)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff8393e191)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_base.c (ffffffff83943d8f)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In net/core/dev.c (ffffffff839674b5)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffff83977754)
Location: include/linux/cpuhotplug.h:307
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/arm64/kernel/fpsimd.c (ffff800011433894)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/arm64/kernel/fpsimd.c:fpsimd_init
```
```
In arch/arm64/kernel/armv8_deprecated.c (ffff800011436580)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/arm64/kernel/armv8_deprecated.c:armv8_deprecated_init
```
```
In virt/kvm/kvm_main.c (ffff8000100b6b58)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_init
```
```
In kernel/softirq.c (ffff800011442438)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffff800011446018)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmscan.c (ffff8000114531f0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (ffff8000114533fc)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffff800011455df4)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffff800011457fec)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffff80001145ae70)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffff80001145bbd0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffff80001145f014)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffff80001146ec2c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffff80001146feac)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffff800011470530)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/irqchip/irq-gic.c (ffff800011471638)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:__gic_init_bases
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800011472ec4)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
```
In drivers/acpi/processor_driver.c (ffff80001147f6e0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/soc/fsl/qbman/bman_portal.c (ffff80001148fd50)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_driver_init
```
```
In drivers/soc/fsl/qbman/qman_portal.c (ffff80001148fddc)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_driver_init
```
```
In drivers/xen/events/events_fifo.c (ffff800011491aa8)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In drivers/perf/arm-cci.c (ffff800010b9090c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
```
```
In net/core/dev.c (ffff8000114ae950)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffff8000114b8534)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/vfp/vfpmodule.c (c150385c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/arm/vfp/vfpmodule.c:vfp_init
```
```
In arch/arm/kernel/smp_twd.c (c1505e18)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/arm/kernel/smp_twd.c:twd_local_timer_of_register
```
```
In arch/arm/mm/cache-l2x0-pmu.c (c150b260)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_init
```
```
In arch/arm/common/bL_switcher.c (c150be10)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_init
  - arch/arm/common/bL_switcher.c:bL_switcher_init
```
```
In arch/arm/mach-mvebu/coherency.c (c150dbf4)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/coherency.c:coherency_init
```
```
In arch/arm/mach-mvebu/platsmp.c (c150e4b0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus
```
```
In arch/arm/mach-omap2/omap-wakeupgen.c (c1515150)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
```
```
In arch/arm/mach-shmobile/platsmp-scu.c (c151a58c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/platsmp-scu.c:shmobile_smp_scu_prepare_cpus
```
```
In kernel/softirq.c (c151c448)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (c15206a8)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmscan.c (c152df0c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (c152e110)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (c1530ec0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (c1531f38)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (c1533abc)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (c1534194)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (c153789c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (c1547aa4)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (c1549060)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (c1549648)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/irqchip/irq-gic.c (c154abbc)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:__gic_init_bases
```
```
In drivers/irqchip/irq-gic-v3.c (c154ba58)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
```
In drivers/irqchip/irq-armada-370-xp.c (c154d5a8)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
```
```
In drivers/cpuidle/coupled.c (c15a44d0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_coupled_init
  - drivers/cpuidle/coupled.c:cpuidle_coupled_init
```
```
In drivers/perf/arm-cci.c (c0c7abd4)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
```
```
In net/core/dev.c (c15b35d8)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (c15bdac0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/watchdog.c (c00000000134cc4c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:watchdog_nmi_probe
```
```
In arch/powerpc/mm/numa.c (c000000001357b94)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:initmem_init
```
```
In kernel/softirq.c (c0000000013660d4)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (c00000000136ac8c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmscan.c (c00000000137b530)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (c00000000137b7f4)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (c00000000137ed04)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (c000000001381798)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (c0000000013850f0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (c000000001386644)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (c00000000138a00c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (c00000000139eae8)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (c0000000013a0420)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (c0000000013a0b88)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/cpuidle/cpuidle-pseries.c (c0000000013b8da4)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-pseries.c:pseries_processor_idle_init
  - drivers/cpuidle/cpuidle-pseries.c:pseries_processor_idle_init
```
```
In drivers/cpuidle/cpuidle-powernv.c (c0000000013b916c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-powernv.c:powernv_processor_idle_init
  - drivers/cpuidle/cpuidle-powernv.c:powernv_processor_idle_init
```
```
In net/core/dev.c (c0000000013be93c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (c0000000013cb428)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe000004972)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffe000007c02)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmscan.c (ffffffe000012544)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (ffffffe000012710)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffe000014db6)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffe0000168cc)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffe000018f04)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffe0000194c0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffe00001bc50)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffe0000291f8)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffe00002a33e)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffe00002a88a)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In net/core/dev.c (ffffffe00003dbd4)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffe000046e4c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/xen/enlighten.c (ffffffff8101d795)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828a055d)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/kvm.c (ffffffff828a9c2c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff828b3c8c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff828b74d3)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmscan.c (ffffffff828c34de)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (ffffffff828c36a3)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828c6170)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff828c80b0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff828caa30)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff828cb7fa)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff828ce78c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff828dd6a9)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffff828debaa)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff828df07b)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff828e4f81)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_fifo.c (ffffffff828e7416)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In net/core/dev.c (ffffffff82902c82)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffff8290bf98)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8289876a)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/kvm.c (ffffffff828a1d1c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff828abe0d)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff828af75e)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In kernel/time/tick-sched.c (ffffffff828b265b)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In mm/vmscan.c (ffffffff828bbc03)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (ffffffff828bbdc8)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828be895)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff828c07d5)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff828c3155)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff828c3f1f)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff828c6ea8)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff828d5dc5)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffff828d72c6)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff828d7797)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff828dd011)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In net/core/dev.c (ffffffff828fafd0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffff829042e6)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/xen/enlighten.c (ffffffff8101d755)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b3520)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/kvm.c (ffffffff828bcb2b)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff828c6b8b)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff828ca40f)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmscan.c (ffffffff828d625e)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (ffffffff828d6423)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828d8ef0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff828dae30)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff828dd7b0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff828de57a)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff828e150c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff828f041d)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffff828f1949)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff828f1e1a)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff828f86b3)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_fifo.c (ffffffff828faf1c)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In net/core/dev.c (ffffffff82918289)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffff829218e2)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
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
In arch/x86/xen/enlighten.c (ffffffff8101d9a5)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
  - arch/x86/xen/enlighten.c:xen_cpuhp_setup
```
```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff828b354e)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be884)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/kvm.c (ffffffff828bfc83)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
```
In kernel/softirq.c (ffffffff828cbed6)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/softirq.c:spawn_ksoftirqd
```
```
In kernel/printk/printk.c (ffffffff828cf7c1)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:printk_late_init
```
```
In mm/vmscan.c (ffffffff828db67f)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
```
```
In mm/vmstat.c (ffffffff828db844)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828de311)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/page_alloc.c (ffffffff828e0251)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
```
```
In mm/slub.c (ffffffff828e2bc7)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff828e3991)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/buffer.c (ffffffff828e6922)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - fs/buffer.c:buffer_init
```
```
In block/blk-softirq.c (ffffffff828f583f)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_init
```
```
In lib/percpu_counter.c (ffffffff828f6d4a)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/percpu_counter.c:percpu_counter_startup
```
```
In lib/irq_poll.c (ffffffff828f721b)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_setup
```
```
In drivers/acpi/processor_driver.c (ffffffff828fdb0b)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
  - drivers/acpi/processor_driver.c:acpi_processor_driver_init
```
```
In drivers/xen/events/events_fifo.c (ffffffff82900c4d)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - drivers/xen/events/events_fifo.c:xen_evtchn_fifo_init
```
```
In net/core/dev.c (ffffffff8291efe0)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - net/core/dev.c:net_dev_init
```
```
In lib/radix-tree.c (ffffffff82928306)
Location: include/linux/cpuhotplug.h:236
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_init
```
</details>
</li>
</ul>

## Differences
