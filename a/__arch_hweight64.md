# Function: <code>__arch_hweight64</code>

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
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff8100bc5b)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff810519a6)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_announce
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff81f78e5a)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81f79138)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/workqueue.c (ffffffff81f7c2e6)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810b5f99)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/power/swap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/events/core.c (ffffffff8118357d)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In kernel/membarrier.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In mm/page_alloc.c (ffffffff81f8751a)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/page-writeback.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In mm/hugetlb.c (ffffffff811dabf1)
Location: arch/x86/include/asm/arch_hweight.h:54
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
Location: arch/x86/include/asm/arch_hweight.h:54
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
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff811efb07)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In fs/proc/stat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81f9956c)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-mq-tag.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In lib/bitmap.c (ffffffff813f948e)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/acpi/numa.c (ffffffff8148b142)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/input/input.c (ffffffff81667c64)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b77dd)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In net/core/ethtool.c (ffffffff81720710)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/flow.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:54
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
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff81f86bf3)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105208a)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:smp_announce
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/mm/numa.c (ffffffff81fa1585)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fa188e)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/workqueue.c (ffffffff81fa5089)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/power/swap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/printk/nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/events/core.c (ffffffff811955de)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/membarrier.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/page_alloc.c (ffffffff81fb0449)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/page-writeback.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/hugetlb.c (ffffffff811f9daa)
Location: arch/x86/include/asm/arch_hweight.h:50
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
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8120ef52)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In fs/proc/stat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff81fc42df)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In block/blk-mq-tag.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/nodemask.c (ffffffff81433f0a)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In lib/bitmap.c (ffffffff814404fe)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/acpi/numa.c (ffffffff814d9f7c)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/input/input.c (ffffffff816c948d)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/md/dm.c (ffffffff81703b4f)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817192b6)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/core/ethtool.c (ffffffff81789d92)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/flow.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
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
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff81fc205f)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/power/swap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/printk/nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/events/core.c (ffffffff811a503e)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/membarrier.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/page-writeback.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In fs/proc/stat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/bitmap.c (ffffffff8145d5fe)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/input/input.c (ffffffff816f746d)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/core/ethtool.c (ffffffff817b7672)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/flow.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
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
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff820a2602)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/power/swap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/events/core.c (ffffffff811ac67e)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In kernel/membarrier.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/page-writeback.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/swap_slots.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In fs/proc/stat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/bitmap.c (ffffffff8146274e)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/input/input.c (ffffffff8170cfa9)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/core/ethtool.c (ffffffff817d60a2)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/flow.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:50
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
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff826a88af)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/crash.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/power/swap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8110094a)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/events/core.c (ffffffff811c0041)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/page-writeback.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/swap_slots.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In fs/proc/stat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/bitmap.c (ffffffff8148e62e)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/rhashtable.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/input/input.c (ffffffff8177e1e9)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In net/core/ethtool.c (ffffffff818505e2)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
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
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff826d1a53)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/power/swap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811087cb)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In kernel/events/core.c (ffffffff811e0429)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/page-writeback.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/swap_slots.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In fs/proc/stat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/bitmap.c (ffffffff814c314c)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/percpu_ida.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/input/input.c (ffffffff817bf303)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In net/core/ethtool.c (ffffffff8189b9b2)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:51
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
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff82887d4f)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/power/swap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81113be1)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In kernel/events/core.c (ffffffff811f0879)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In mm/page-writeback.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In mm/swap_slots.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In fs/proc/stat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In lib/bitmap.c (ffffffff814d78cc)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/input/input.c (ffffffff817e6763)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In net/core/ethtool.c (ffffffff818bddc2)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:45
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
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff8289ee02)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/acpi/cstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/ftrace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/membarrier.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/power/swap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk_safe.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8111d7fb)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/debug_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff81208040)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page-writeback.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/swap_slots.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/io_uring.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/crypto/crypto.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/proc/stat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff815037a8)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/percpu_counter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/input/input.c (ffffffff81827392)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/ethtool.c (ffffffff8190a303)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff828a1eb3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bbbec)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81129d9b)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff812153b0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff81521748)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81753cfa)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff817626c9)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In drivers/input/input.c (ffffffff818588c2)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/ethtool.c (ffffffff8193c8e3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff82cc7f6e)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e2e9)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce0f1d)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811381e3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff812418de)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/io-wq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff8158479d)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818127aa)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff818223cf)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
```
```
In drivers/input/input.c (ffffffff8192898e)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a83ed3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff82fb3a93)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101e909)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fcd688)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff8124bfc1)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff815a18ad)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818219fa)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff818310df)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
```
```
In drivers/input/input.c (ffffffff8192febe)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a8da03)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
In arch/x86/events/core.c (ffffffff81bc4090)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_show_pmu_cap
  - arch/x86/events/core.c:events_hybrid_sysfs_show
```
```
In arch/x86/events/amd/core.c (ffffffff810096ca)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff81bc438b)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101fd39)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d8195)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff812500e1)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff815a8758)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81804d1a)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff818146f1)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
```
In drivers/spi/spi.c (ffffffff8186be7b)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff819141f4)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/powercap/dtpm_cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81a768c3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
In arch/x86/events/core.c (ffffffff81c9535e)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_show_pmu_cap
  - arch/x86/events/core.c:events_hybrid_sysfs_show
```
```
In arch/x86/events/amd/core.c (ffffffff8100a69a)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff81c95878)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810231d9)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bb0ab)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/clocksource.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff8128ae41)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff81611908)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188f47a)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff8189ee04)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
```
In drivers/spi/spi.c (ffffffff818fbd3b)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff819b6302)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/powercap/dtpm_cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81b30a93)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
In arch/x86/events/core.c (ffffffff81e44617)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_show_pmu_cap
  - arch/x86/events/core.c:events_hybrid_sysfs_show
```
```
In arch/x86/events/amd/core.c (ffffffff81009c84)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff81e44d11)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81026fb8)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346cb06)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff812df8a6)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff816ddaf6)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d8a1a)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff819e8872)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
```
In drivers/spi/spi.c (ffffffff81a4d424)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff81b15ad9)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81cbb982)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
In arch/x86/events/core.c (ffffffff8100a50a)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_show_pmu_cap
  - arch/x86/events/core.c:events_hybrid_sysfs_show
```
```
In arch/x86/events/amd/core.c (ffffffff8100b724)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff81012743)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c828)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93557)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff81347bff)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmscan.c (ffffffff81387681)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/proc/fd.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff817cdb0c)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/find_bit.c (ffffffff817d6e04)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b5398a)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff81b63e3f)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
```
In drivers/spi/spi.c (ffffffff81bd7644)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff81ca739d)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81e79f32)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/cpumask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
In arch/x86/events/core.c (ffffffff81009d5a)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_show_pmu_cap
  - arch/x86/events/core.c:events_hybrid_sysfs_show
```
```
In arch/x86/events/amd/core.c (ffffffff8100ade9)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff81011cb3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c878)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff81378b41)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/proc/fd.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff8180bf8c)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/find_bit.c (ffffffff81815e1f)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_and_andnot_bit
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/group_cpus.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6e8a)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff81bb743f)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
```
In drivers/spi/spi.c (ffffffff81c2e064)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff81d0e579)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81ed6232)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
In arch/x86/events/core.c (ffffffff8100f47a)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_pmu_show_pmu_cap
  - arch/x86/events/core.c:events_hybrid_sysfs_show
```
```
In arch/x86/events/amd/core.c (ffffffff81010569)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff8101b1c5)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810329d8)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:icx_count_chabox
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/threshold.c (ffffffff81086a1f)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/threshold.c:mce_track_storm
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/shstk.c (ffffffff810cad15)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_prctl
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/reboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/build_utility.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/power/energy_model.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/crash_core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/map_iter.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/cpumask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff813a1e41)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mmap_lock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/slub.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/proc/fd.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/squashfs/decompressor_multi_percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff8185246c)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight_and
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/find_bit.c (ffffffff8185af5f)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/find_bit.c:__find_nth_and_andnot_bit
  - lib/find_bit.c:__find_nth_andnot_bit
  - lib/find_bit.c:__find_nth_and_bit
  - lib/find_bit.c:__find_nth_bit
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/group_cpus.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/char/random.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfb13a)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff81c0ba8f)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
```
```
In drivers/gpu/drm/drm_property.c (ffffffff81cae425)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_property_create_bitmask
```
```
In drivers/spi/spi.c (ffffffff81ce0ab4)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
```
```
In drivers/input/input.c (ffffffff81dc41c9)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_estimate_events_per_packet
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/hv/hv_common.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ethtool/ioctl.c (ffffffff81f99db2)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_get_sset_info
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ipv4/tcp_sigpool.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/objpool.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In arch/arm64/kernel/insn.c (ffff8000100963f8)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - arch/arm64/kernel/insn.c:aarch64_encode_immediate
```
```
In arch/arm64/kernel/smp.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In arch/arm64/mm/context.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In arch/arm64/mm/numa.c (ffff8000100b2344)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:node_set_online
```
```
In kernel/workqueue.c (ffff800011442ef4)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/pid.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/sched/rt.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/sched/deadline.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/sched/topology.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/sched/debug.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/printk/printk.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/irq/affinity.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/rcu/tree.c (ffff800010191a48)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/time/tick-sched.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/futex.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/smp.c (ffff800011449714)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/kexec_file.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/stop_machine.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/kprobes.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/bpf/syscall.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/bpf/hashtab.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/bpf/arraymap.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/bpf/local_storage.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/bpf/devmap.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/bpf/cpumap.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/bpf/xskmap.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In kernel/events/core.c (ffff80001029f424)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In mm/vmstat.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In mm/mm_init.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In mm/percpu.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In mm/page_alloc.c (ffff80001031b168)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In mm/hugetlb.c (ffff80001032fa14)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffff800010338a00)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffff80001034dbd8)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In fs/aio.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In security/apparmor/lsm.c (ffff80001146b774)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In lib/bitmap.c (ffff80001062b258)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In lib/sbitmap.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In drivers/irqchip/irq-gic.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/irqchip/irq-bcm7038-l1.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/bus/brcmstb_gisb.c (ffff8000114769d4)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
```
```
In drivers/pci/controller/pci-xgene-msi.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/pci/controller/pcie-iproc-msi.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/acpi/numa.c (ffff80001077b950)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/soc/fsl/qbman/qman.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/xen/time.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/base/arch_topology.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffff80001095471c)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/nvdimm/label.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In drivers/nvdimm/security.c (ffff800010962544)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In drivers/input/input.c (ffff800010a975cc)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/thermal/cpu_cooling.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/md/dm.c (ffff800010afd038)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/md/dm-stats.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In drivers/firmware/qcom_scm.c (ffff800010b4edb0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_assign_mem
```
```
In drivers/perf/arm-cci.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In drivers/perf/arm-ccn.c (ffff800010b92998)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_active_counters
```
```
In drivers/perf/arm_pmu.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In drivers/perf/hisilicon/hisi_uncore_pmu.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In drivers/perf/xgene_pmu.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In net/core/dev.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In net/core/ethtool.c (ffff800010bdc590)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: False
```
```
In lib/nodemask.c (ffff800010d8d0f0)
Location: include/asm-generic/bitops/arch_hweight.h:22
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
In kernel/events/core.c (c04cf294)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In net/core/ethtool.c (c0cf6608)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/input/input.c:input_register_device
  - net/core/ethtool.c:ethtool_get_sset_info
```
**Symbols:**

```
c0000000000b3bb4-c0000000000b3bb4: __arch_hweight64 (STB_GLOBAL)
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
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_clamp_max_active
```
```
In kernel/pid.c (ffffffe0000dcd74)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In kernel/sched/core.c (ffffffe0000ec4f8)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:set_cpus_allowed_common
```
```
In kernel/sched/rt.c (ffffffe0000f7b10)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/sched/rt.c:do_balance_runtime
```
```
In kernel/sched/deadline.c (ffffffe0000fe568)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_add_task_root_domain
  - kernel/sched/deadline.c:dl_task_offline_migration
  - kernel/sched/deadline.c:dl_task_offline_migration
```
```
In kernel/sched/topology.c (ffffffe000100e8a)
Location: include/asm-generic/bitops/arch_hweight.h:22
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
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/sched/debug.c:register_sched_domain_sysctl
```
```
In kernel/printk/printk.c (ffffffe0001119da)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In kernel/irq/affinity.c (ffffffe00011db8a)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_calc_affinity_vectors
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/rcu/tree.c (ffffffe000124ce8)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (ffffffe000139864)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_register_device
```
```
In kernel/time/tick-sched.c (ffffffe00013be36)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_setup_sched_timer
```
```
In kernel/futex.c (ffffffe00000a92a)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/smp.c (ffffffe0001409f0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a1aa)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
  - kernel/cgroup/cpuset.c:update_parent_subparts_cpumask
```
```
In kernel/stop_machine.c (ffffffe00015dc24)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:__stop_cpus
```
```
In kernel/bpf/syscall.c (ffffffe00019e324)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/hashtab.c (ffffffe0001b03aa)
Location: include/asm-generic/bitops/arch_hweight.h:22
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
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/percpu_freelist.c (ffffffe0001b39a0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
```
```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4628)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
```
In kernel/bpf/local_storage.c (ffffffe0001b5ba0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffe0001bbda6)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc7e4)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In kernel/bpf/xskmap.c (ffffffe0001bd73e)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In kernel/events/core.c (ffffffe0001cedf2)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (ffffffe0001d2fec)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_parallel
```
```
In mm/vmstat.c (ffffffe000012788)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mm_init.c (ffffffe000012aa0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - mm/mm_init.c:mm_compute_batch_init
```
```
In mm/percpu.c (ffffffe0001fa756)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In mm/page_alloc.c (ffffffe0000156c4)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffe000018142)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In fs/aio.c (ffffffe0002aba58)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
```
```
In lib/bitmap.c (ffffffe00045bff4)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In lib/bucket_locks.c (ffffffe0004650c0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - lib/bucket_locks.c:__alloc_bucket_spinlocks
```
```
In lib/sbitmap.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe00002abd2)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_init
```
```
In drivers/base/arch_topology.c (ffffffe0000317d8)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_parse_cpu_capacity
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c3ea2)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (ffffffe0005c6e96)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/label.c (0)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffe0005cfbba)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In drivers/input/input.c (ffffffe0006a8aee)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm-stats.c (ffffffe0006fa83e)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (ffffffe00071e1f6)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu
```
```
In net/core/dev.c (ffffffe00075a82c)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - net/core/dev.c:__netif_set_xps_queue
```
```
In net/core/ethtool.c (ffffffe000763cc8)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/net-sysfs.c (ffffffe00078906c)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - net/core/net-sysfs.c:store_rps_map
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7916)
Location: include/asm-generic/bitops/arch_hweight.h:22
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf862)
Location: include/asm-generic/bitops/arch_hweight.h:22
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
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff8288feb3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8112237b)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff8120da00)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff81519d28)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817083ea)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff81716db9)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In drivers/nvme/host/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvme/host/pci.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/input/input.c (ffffffff8180d8d2)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/ethtool.c (ffffffff818dc8b3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff8288ddef)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff81114a2b)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff812007d0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff8150a018)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dbe6a)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff816ea839)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In drivers/scsi/storvsc_drv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvme/host/pci.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/input/input.c (ffffffff817d5042)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/hv/channel_mgmt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/ethtool.c (ffffffff818966f3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff828a2eb3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8112026b)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff8120b7a0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff81515db8)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817471ba)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff81755b89)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In drivers/input/input.c (ffffffff8184ca52)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/ethtool.c (ffffffff8192d8e3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
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
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
  - arch/x86/events/amd/core.c:amd_get_event_constraints_f15h
```
```
In arch/x86/events/intel/core.c (ffffffff828a2ec7)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/trace.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/xen/spinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/proc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/tsc_sync.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bcc19)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/apic/apic_flat_64.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/kernel/kvmclock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/mm/amdtopology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/tlb_uv.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/workqueue.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/pid.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff8112c4ab)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/time/clockevents.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/time/tick-sched.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/futex.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/stop_machine.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/kprobes.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/debug/kdb/kdb_bt.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/arraymap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/percpu_freelist.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/bpf_lru_list.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/local_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/devmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/cpumap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In kernel/events/core.c (ffffffff8121a5b0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
```
In kernel/padata.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In fs/aio.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bitmap.c (ffffffff8152f548)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_weight
  - lib/bitmap.c:__bitmap_weight
```
```
In lib/memweight.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/bucket_locks.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/x86/apple.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/acpi/numa.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/xen/time.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/iommu/hyperv-iommu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817625fa)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_freeze
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/region.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff81770ff9)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_security_unlock
```
```
In drivers/input/input.c (ffffffff81867d42)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
```
In drivers/md/dm.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/pcc-cpufreq.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In drivers/leds/trigger/ledtrig-cpu.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/ethtool.c (ffffffff8194efb3)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_get_sset_info
```
```
In net/core/net-sysfs.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
```
In lib/nodemask.c (0)
Location: arch/x86/include/asm/arch_hweight.h:43
Inline: True
```
</details>
</li>
</ul>

## Differences
