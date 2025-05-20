# Function: <code>hweight_long</code>

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
In arch/x86/events/amd/core.c (ffffffff81007c98)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810519a6)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_announce
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff81f78e5a)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81f79138)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cpu.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/workqueue.c (ffffffff81f7c2e6)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b5f99)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/membarrier.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/page_alloc.c (ffffffff81f8751a)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/page-writeback.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/hugetlb.c (ffffffff811dabf1)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
```
```
In mm/mempolicy.c (ffffffff811e0451)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:node_random
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff811efb07)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81f9956c)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In lib/bitmap.c (ffffffff813f948e)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/acpi/numa.c (ffffffff8148b142)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/input/input.c (ffffffff81667c64)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b77dd)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In net/core/flow.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:78
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81007ea5)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/uncore.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105208a)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:smp_announce
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff81fa1585)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fa188e)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cpu.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/workqueue.c (ffffffff81fa5089)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/printk/nmi.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In kernel/membarrier.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/page_alloc.c (ffffffff81fb0449)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/page-writeback.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/hugetlb.c (ffffffff811f9daa)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff811ffeea)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8120ef52)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81fc42df)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-mq-tag.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In lib/nodemask.c (ffffffff81433f0a)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In lib/bitmap.c (ffffffff814404fe)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/acpi/numa.c (ffffffff814d9f7c)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/input/input.c (ffffffff816c948d)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/md/dm.c (ffffffff81703b4f)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817192b6)
Location: include/linux/bitops.h:78
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In net/core/flow.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:78
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:78
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81007ec5)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/printk/nmi.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/membarrier.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/bitmap.c (ffffffff8145d5fe)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/input/input.c (ffffffff816f746d)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In net/core/flow.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:68
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
In arch/x86/events/amd/core.c (ffffffff81007ba5)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In kernel/membarrier.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/bitmap.c (ffffffff8146274e)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/input/input.c (ffffffff8170cfa9)
Location: include/linux/bitops.h:68
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In net/core/flow.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/bitops.h:68
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:68
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff8100802f)
Location: include/linux/bitops.h:70
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8110094a)
Location: include/linux/bitops.h:70
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/bitmap.c (ffffffff8148e62e)
Location: include/linux/bitops.h:70
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/rhashtable.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/input/input.c (ffffffff8177e1e9)
Location: include/linux/bitops.h:70
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:70
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81008839)
Location: include/linux/bitops.h:70
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811087cb)
Location: include/linux/bitops.h:70
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/bitmap.c (ffffffff814c314c)
Location: include/linux/bitops.h:70
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/input/input.c (ffffffff817bf303)
Location: include/linux/bitops.h:70
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/bitops.h:70
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:70
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81008747)
Location: include/linux/bitops.h:51
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81113be1)
Location: include/linux/bitops.h:51
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/bitmap.c (ffffffff814d78cc)
Location: include/linux/bitops.h:51
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/input/input.c (ffffffff817e6763)
Location: include/linux/bitops.h:51
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:51
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81008a3c)
Location: include/linux/bitops.h:51
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8111d7fb)
Location: include/linux/bitops.h:51
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/swap_slots.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In fs/proc/stat.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/bitmap.c (ffffffff815037a8)
Location: include/linux/bitops.h:51
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/input/input.c (ffffffff81827392)
Location: include/linux/bitops.h:51
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/bitops.h:51
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:51
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81008d5c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81129d9b)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bitmap.c (ffffffff81521748)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/input/input.c (ffffffff818588c2)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:58
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81009eaa)
Location: include/linux/bitops.h:73
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811381e3)
Location: include/linux/bitops.h:73
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In fs/io-wq.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In lib/bitmap.c (ffffffff8158479d)
Location: include/linux/bitops.h:73
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/input/input.c (ffffffff8192898e)
Location: include/linux/bitops.h:73
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitops.h:73
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:73
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81008d2a)
Location: include/linux/bitops.h:76
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In lib/bitmap.c (ffffffff815a18ad)
Location: include/linux/bitops.h:76
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/input/input.c (ffffffff8192febe)
Location: include/linux/bitops.h:76
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:76
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff810096ca)
Location: include/linux/bitops.h:76
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In lib/bitmap.c (ffffffff815a8758)
Location: include/linux/bitops.h:76
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8186be7b)
Location: include/linux/bitops.h:76
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff819141f4)
Location: include/linux/bitops.h:76
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In drivers/powercap/dtpm_cpu.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitops.h:76
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:76
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff8100a69a)
Location: include/linux/bitops.h:77
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In lib/bitmap.c (ffffffff81611908)
Location: include/linux/bitops.h:77
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/spi/spi.c (ffffffff818fbd3b)
Location: include/linux/bitops.h:77
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff819b6302)
Location: include/linux/bitops.h:77
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In drivers/powercap/dtpm_cpu.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitops.h:77
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:77
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81009c84)
Location: include/linux/bitops.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff816ddaf6)
Location: include/linux/bitops.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81a4d424)
Location: include/linux/bitops.h:43
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff81b15ad9)
Location: include/linux/bitops.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitops.h:43
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:43
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff8100b724)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/vmscan.c (ffffffff81387681)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/bitmap.c (ffffffff817cdb0c)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/find_bit.c (ffffffff817d6e04)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81bd7644)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff81ca739d)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/bitops.h:94
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff8100ade9)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/bitmap.c (ffffffff8180bf8c)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/find_bit.c (ffffffff81815e1f)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_and_andnot_bit
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/group_cpus.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81c2e064)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff81d0e579)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:94
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81010569)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/kernel/shstk.c (ffffffff810cad15)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_prctl
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/futex/core.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/crash_core.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/bpf/cpumask.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In fs/proc/fd.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/bitmap.c (ffffffff8185246c)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/find_bit.c (ffffffff8185af5f)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_and_andnot_bit
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/group_cpus.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81ce0ab4)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff81dc41c9)
Location: include/linux/bitops.h:94
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/ethtool/ioctl.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In net/ipv4/tcp_sigpool.c (0)
Location: include/linux/bitops.h:94
Inline: True
```
```
In lib/objpool.c (0)
Location: include/linux/bitops.h:94
Inline: True
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
In arch/arm64/kernel/setup.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/arm64/kernel/smp.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/arm64/mm/context.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/arm64/mm/numa.c (ffff8000100b2344)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:node_set_online
```
```
In kernel/workqueue.c (ffff800011442ef4)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/rcu/tree.c (ffff800010191a48)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/smp.c (ffff800011449714)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/page_alloc.c (ffff80001031b168)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/hugetlb.c (ffff80001032fa14)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffff800010338a00)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffff80001034dbd8)
Location: include/linux/bitops.h:58
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In security/apparmor/lsm.c (ffff80001146b774)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In lib/bitmap.c (ffff80001062b258)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/irqchip/irq-gic.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/irqchip/irq-bcm7038-l1.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/bus/brcmstb_gisb.c (ffff8000114769d4)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
```
```
In drivers/pci/controller/pci-xgene-msi.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/pci/controller/pcie-iproc-msi.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/acpi/numa.c (ffff80001077b950)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/soc/fsl/qbman/qman.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/base/arch_topology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/input/input.c (ffff800010a975cc)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/thermal/cpu_cooling.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/md/dm.c (ffff800010afd038)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/firmware/qcom_scm.c (ffff800010b4edb0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
```
```
In drivers/perf/arm-cci.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/perf/arm-ccn.c (ffff800010b92998)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_active_counters
```
```
In drivers/perf/arm_pmu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/perf/xgene_pmu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/nodemask.c (ffff800010d8d0f0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/arm/kernel/setup.c (c1504e00)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/kernel/smp.c (c1505ca8)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_prepare_cpus
```
```
In arch/arm/kernel/machine_kexec.c (c03151cc)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_kexec_prepare
```
```
In arch/arm/mach-exynos/exynos.c (c032cbf4)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion
```
```
In arch/arm/mach-mvebu/platsmp.c (c150e588)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_init_cpus
```
```
In kernel/workqueue.c (c0371710)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (c0377da0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/core.c (c038d180)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (c039b8d4)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/deadline.c (c03a55ac)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (c03a873c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_overlap_sched_groups
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (c03ae5fc)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/sched/cpufreq_schedutil.c (c03b1560)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_start
```
```
In kernel/printk/printk.c (c03c85b0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/irq/affinity.c (c03d6e50)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (c03df5e4)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (c03fbe80)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/time/clockevents.c:tick_cleanup_dead_cpu
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (c03ffc6c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (c1523684)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (c0405524)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (c04248c0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (c0428d78)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/kprobes.c (c04396d4)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (c0441cd4)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (c04434c0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (c0444670)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/bpf/syscall.c (c0493c74)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (c04aaab8)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (c04ad4c0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (c04adce8)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (c04aeb18)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (c04b0180)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/devmap.c (c04b6f8c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (c04b7af0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/xskmap.c (c04b8d00)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/padata.c (c04d81d0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (c0501f08)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (c152e4a0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
```
```
In mm/percpu.c (c050818c)
Location: include/linux/bitops.h:58
Inline: True
```
```
In fs/aio.c (c05d096c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In lib/bitmap.c (c07d2560)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bucket_locks.c (c07ddc10)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/irqchip/irq-gic.c (c08152bc)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_get_cpumask
```
```
In drivers/bus/brcmstb_gisb.c (c154eb20)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
```
```
In drivers/dma/mv_xor.c (c0925324)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/soc/tegra/flowctrl.c (c093ad48)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/soc/tegra/flowctrl.c:flowctrl_cpu_suspend_enter
```
```
In drivers/base/arch_topology.c (c1598d24)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/mtd/nand/raw/nand_base.c (c0a9b314)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_check_erased_buf
```
```
In drivers/input/input.c (c0b7a7bc)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (c0bb57ec)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:perf_trace_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_limit
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
  - drivers/thermal/thermal_core.c:trace_event_raw_event_thermal_power_cpu_get_power
```
```
In drivers/thermal/cpu_cooling.c (c0bbc8e0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/thermal/cpu_cooling.c:__cpufreq_cooling_register
  - drivers/thermal/cpu_cooling.c:cpufreq_state2power
  - drivers/thermal/cpu_cooling.c:cpufreq_get_requested_power
```
```
In drivers/md/dm-stats.c (c0beb2d8)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bff58c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
```
```
In drivers/cpuidle/coupled.c (c0c05088)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:coupled_cpu_online
  - drivers/cpuidle/coupled.c:cpuidle_coupled_register_device
```
```
In drivers/leds/trigger/ledtrig-cpu.c (c0c344e4)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In drivers/firmware/qcom_scm.c (c0c35654)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
```
```
In drivers/perf/arm-cci.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/perf/arm-ccn.c (c0c7c550)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_active_counters
```
```
In drivers/perf/arm_pmu.c (c0c7eb04)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
```
In sound/soc/soc-pcm.c (c0cb0254)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - sound/soc/soc-pcm.c:soc_pcm_codec_params_fixup
```
```
In net/core/dev.c (c0cea738)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/net-sysfs.c (c0d2377c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (c0d48534)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (c0d78d04)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In arch/powerpc/kernel/setup-common.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/kernel/watchdog.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/kernel/crash.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/mm/numa.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/sysdev/mpic.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/sysdev/xive/common.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/platforms/powernv/memtrace.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/platforms/pseries/lpar.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/platforms/pseries/setup.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/xmon/xmon.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/powerpc/perf/imc-pmu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/rcu/tree.c (c0000000001ed05c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bitmap.c (c0000000007cd4e0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/input/input.c (c000000000b78170)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/thermal/cpu_cooling.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/powernv-cpufreq.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:58
Inline: True
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
In kernel/workqueue.c (ffffffe0000d7104)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffe0000dcd74)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/core.c (ffffffe0000ec4f8)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (ffffffe0000f7b10)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/sched/rt.c:do_balance_runtime
```
```
In kernel/sched/deadline.c (ffffffe0000fe568)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffe000100e8a)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:sd_degenerate
```
```
In kernel/sched/debug.c (ffffffe000105bd2)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/printk/printk.c (ffffffe0001119da)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/irq/affinity.c (ffffffe00011db8a)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffe000124ce8)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffe000139864)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffe00013be36)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffe00000a92a)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffe0001409f0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a1aa)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffffffe00015dc24)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/bpf/syscall.c (ffffffe00019e324)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffe0001b03aa)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffe0001b326a)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffe0001b39a0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4628)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffe0001b5ba0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffe0001bbda6)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc7e4)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffe0001bd73e)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/padata.c (ffffffe0001d2fec)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (ffffffe000012788)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffe000012aa0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
```
```
In mm/percpu.c (ffffffe0001fa756)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/page_alloc.c (ffffffe0000156c4)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffe000018142)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In fs/aio.c (ffffffe0002aba58)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In lib/bitmap.c (ffffffe00045bff4)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bucket_locks.c (ffffffe0004650c0)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe00002abd2)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_init
```
```
In drivers/base/arch_topology.c (ffffffe0000317d8)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/nvdimm/region.c (ffffffe0005c6e96)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/input/input.c (ffffffe0006a8aee)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm-stats.c (ffffffe0006fa83e)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffe00071e1f6)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffe00075a82c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/net-sysfs.c (ffffffe00078906c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7916)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf862)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
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
In arch/x86/events/amd/core.c (ffffffff81008d5c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8112237b)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bitmap.c (ffffffff81519d28)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvme/host/pci.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/input/input.c (ffffffff8180d8d2)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:58
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff8100756c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81114a2b)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bitmap.c (ffffffff8150a018)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/scsi/storvsc_drv.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvme/host/pci.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/input/input.c (ffffffff817d5042)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/hv/channel_mgmt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:58
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81008d1c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8112026b)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bitmap.c (ffffffff81515db8)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/input/input.c (ffffffff8184ca52)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:58
Inline: True
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
In arch/x86/events/amd/core.c (ffffffff81008e7c)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/pid.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8112c4ab)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/smp.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In kernel/padata.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mm_init.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bitmap.c (ffffffff8152f548)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/sbitmap.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/input/input.c (ffffffff81867d42)
Location: include/linux/bitops.h:58
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
```
In lib/nodemask.c (0)
Location: include/linux/bitops.h:58
Inline: True
```
</details>
</li>
</ul>

## Differences
