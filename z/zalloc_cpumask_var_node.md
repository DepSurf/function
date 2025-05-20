# Function: <code>zalloc_cpumask_var_node</code>

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
In arch/x86/kernel/apic/vector.c (ffffffff81055516)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
```
```
In kernel/workqueue.c (ffffffff81f7c367)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/sched/rt.c (ffffffff81f7e4d2)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff81f7e525)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/irq/irqdesc.c (ffffffff810da132)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/smp.c (ffffffff811037c9)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/smp.c:hotplug_cfd
```
```
In block/blk-mq.c (ffffffff813c5050)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81fa56e5)
Location: include/linux/cpumask.h:686
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81fb3ee7)
Location: include/linux/cpumask.h:686
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
In arch/x86/kernel/apic/vector.c (ffffffff810557b6)
Location: include/linux/cpumask.h:688
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
```
```
In kernel/workqueue.c (ffffffff81fa5111)
Location: include/linux/cpumask.h:688
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/sched/rt.c (ffffffff81fa7397)
Location: include/linux/cpumask.h:688
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffff81fa73ea)
Location: include/linux/cpumask.h:688
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/irq/irqdesc.c (ffffffff810df62a)
Location: include/linux/cpumask.h:688
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/smp.c (ffffffff8110b495)
Location: include/linux/cpumask.h:688
Inline: True
Inline callers:
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In block/blk-mq.c (ffffffff814079e0)
Location: include/linux/cpumask.h:688
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81fd1b6a)
Location: include/linux/cpumask.h:688
Inline: True
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81fe0993)
Location: include/linux/cpumask.h:688
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8144b5f0)
Location: lib/cpumask.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8144b5f0-ffffffff8144b601: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff818ebcb0)
Location: lib/cpumask.c:109
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - arch/x86/kernel/apic/vector.c:alloc_apic_chip_data
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff818ebcb0-ffffffff818ebcc1: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81971c90)
Location: lib/cpumask.c:126
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81971c90-ffffffff81971ca1: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff819ce040)
Location: lib/cpumask.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - kernel/workqueue.c:wq_numa_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff819ce040-ffffffff819ce051: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a07500)
Location: lib/cpumask.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - kernel/workqueue.c:wq_numa_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff81a07500-ffffffff81a07511: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a76e60)
Location: lib/cpumask.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - kernel/workqueue.c:wq_numa_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff81a76e60-ffffffff81a76e71: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81aae360)
Location: lib/cpumask.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff81aae360-ffffffff81aae371: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815e8080)
Location: lib/cpumask.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_alloc_hctx
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
```
**Symbols:**

```
ffffffff815e8080-ffffffff815e8091: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8160d1e0)
Location: lib/cpumask.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - kernel/workqueue.c:wq_numa_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_alloc_hctx
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
```
**Symbols:**

```
ffffffff8160d1e0-ffffffff8160d1f1: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815f0680)
Location: lib/cpumask.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - kernel/workqueue.c:wq_numa_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_alloc_hctx
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff815f0680-ffffffff815f0691: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8165d760)
Location: lib/cpumask.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - kernel/workqueue.c:wq_numa_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_alloc_hctx
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff8165d760-ffffffff8165d771: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81776cb0)
Location: lib/cpumask.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - kernel/workqueue.c:wq_numa_init
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:init_sched_rt_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_alloc_hctx
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff81776cb0-ffffffff81776ccb: zalloc_cpumask_var_node (STB_GLOBAL)
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
In arch/x86/kernel/kvm.c (ffffffff83e963a6)
Location: include/linux/cpumask.h:824
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
```
In kernel/workqueue.c (ffffffff83ea6544)
Location: include/linux/cpumask.h:824
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff83ea83a7)
Location: include/linux/cpumask.h:824
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff83ea8875)
Location: include/linux/cpumask.h:824
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/build_policy.c (ffffffff83ea8b99)
Location: include/linux/cpumask.h:824
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:init_sched_rt_class
```
```
In kernel/irq/irqdesc.c (ffffffff81194b94)
Location: include/linux/cpumask.h:824
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/smp.c (ffffffff811f9a7c)
Location: include/linux/cpumask.h:824
Inline: True
Inline callers:
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In block/blk-mq.c (ffffffff8174501a)
Location: include/linux/cpumask.h:824
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff83eebbd3)
Location: include/linux/cpumask.h:824
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff83f02485)
Location: include/linux/cpumask.h:824
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
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
In arch/x86/kernel/kvm.c (ffffffff836b9f26)
Location: include/linux/cpumask.h:876
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
```
In kernel/workqueue.c (ffffffff836cad04)
Location: include/linux/cpumask.h:876
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/core.c (ffffffff836ccc77)
Location: include/linux/cpumask.h:876
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff836cd237)
Location: include/linux/cpumask.h:876
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/build_policy.c (ffffffff836cd659)
Location: include/linux/cpumask.h:876
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:init_sched_rt_class
```
```
In kernel/irq/irqdesc.c (ffffffff811a6314)
Location: include/linux/cpumask.h:876
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/smp.c (ffffffff8120e90c)
Location: include/linux/cpumask.h:876
Inline: True
Inline callers:
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In block/blk-mq.c (ffffffff81780f8a)
Location: include/linux/cpumask.h:876
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff83711813)
Location: include/linux/cpumask.h:876
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff83728375)
Location: include/linux/cpumask.h:876
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
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
In arch/x86/kernel/kvm.c (ffffffff838ea856)
Location: include/linux/cpumask.h:894
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
```
In kernel/workqueue.c (ffffffff838fc570)
Location: include/linux/cpumask.h:894
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/sched/core.c (ffffffff838fe058)
Location: include/linux/cpumask.h:894
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/sched/fair.c (ffffffff838fe607)
Location: include/linux/cpumask.h:894
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:init_sched_fair_class
```
```
In kernel/sched/build_policy.c (ffffffff838feaa9)
Location: include/linux/cpumask.h:894
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:init_sched_rt_class
```
```
In kernel/irq/irqdesc.c (ffffffff811b5e33)
Location: include/linux/cpumask.h:894
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/smp.c (ffffffff812260ac)
Location: include/linux/cpumask.h:894
Inline: True
Inline callers:
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In block/blk-mq.c (ffffffff817c37ec)
Location: include/linux/cpumask.h:894
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff839451a3)
Location: include/linux/cpumask.h:894
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff8395c305)
Location: include/linux/cpumask.h:894
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
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
In kernel/workqueue.c (ffff800011442fa0)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/rt.c (ffff8000114450cc)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffff800011445140)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/irq/irqdesc.c (ffff8000101774c0)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/smp.c (ffff8000101bdaa4)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In block/blk-mq.c (ffff8000105f20d0)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
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
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:773
Inline: True
```
```
In kernel/sched/rt.c (c151f234)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (c151f290)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/irq/irqdesc.c (c03c93c0)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/smp.c (c0405bb4)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In block/blk-mq.c (c079e224)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
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
In arch/powerpc/kernel/smp.c (c000000001350750)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
```
```
In kernel/workqueue.c (c000000001366f3c)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/rt.c (c000000001369a0c)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (c000000001369abc)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/irq/irqdesc.c (c0000000001d107c)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/smp.c (c000000000223ddc)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In block/blk-mq.c (c0000000007891fc)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
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
In kernel/workqueue.c (0)
Location: include/linux/cpumask.h:773
Inline: True
```
```
In kernel/sched/rt.c (ffffffe000006eee)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_sched_rt_class
```
```
In kernel/sched/deadline.c (ffffffe000006f70)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/sched/deadline.c:init_sched_dl_class
```
```
In kernel/irq/irqdesc.c (ffffffe0001124f0)
Location: include/linux/cpumask.h:773
Inline: True
```
```
In kernel/smp.c (ffffffe000140f88)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
```
```
In block/blk-mq.c (ffffffe000430a16)
Location: include/linux/cpumask.h:773
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a4d1b0)
Location: lib/cpumask.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff81a4d1b0-ffffffff81a4d1c1: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81a0a2e0)
Location: lib/cpumask.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff81a0a2e0-ffffffff81a0a2f1: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ab95a0)
Location: lib/cpumask.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff81ab95a0-ffffffff81ab95b1: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool zalloc_cpumask_var_node(cpumask_var_t *mask, gfp_t flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81ac59f0)
Location: lib/cpumask.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - kernel/workqueue.c:workqueue_init
  - kernel/sched/rt.c:init_sched_rt_class
  - kernel/sched/deadline.c:init_sched_dl_class
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/smp.c:smpcfd_prepare_cpu
  - kernel/smp.c:smpcfd_prepare_cpu
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
```
**Symbols:**

```
ffffffff81ac59f0-ffffffff81ac5a01: zalloc_cpumask_var_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
