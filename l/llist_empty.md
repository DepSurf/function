# Function: <code>llist_empty</code>

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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81046e35)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810aa6a5)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_tick
```
```
In kernel/smp.c (ffffffff811036b5)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff81170e6c)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_tick
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81047045)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810afd8d)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff8110ab93)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff8117e733)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81048bc5)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810b5ecd)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff811123b3)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff8118a343)
Location: include/linux/llist.h:158
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff81048555)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810b216d)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff811139e9)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff8118ce33)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff8104bf85)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810b9533)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff8111ef6f)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff8119a903)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/cpu/mcheck/mce-genpool.c (ffffffff8104ec85)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce-genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810c14f6)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff8112c2b3)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811b0343)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In drivers/iommu/amd_iommu.c (ffffffff81666ef5)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104c355)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810ca826)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff81137b83)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811be963)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In drivers/iommu/amd_iommu.c (ffffffff81685595)
Location: include/linux/llist.h:199
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104f255)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810d24d1)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff81142cc0)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811ce503)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bcad5)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fbd5)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810dc941)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff8114e826)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811dab23)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In drivers/iommu/amd_iommu.c (ffffffff816dfb45)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810540d5)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/smp.c (ffffffff8115fcb4)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_from_idle
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811f75c3)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In drivers/iommu/amd/iommu.c (ffffffff8179787f)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81053035)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/smp.c (ffffffff8115bc54)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_from_idle
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811f6123)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a5fef)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81054925)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/smp.c (ffffffff8115ce74)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_from_idle
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811f7013)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In fs/io_uring.c (ffffffff8139ad83)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff81787bef)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8105d275)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/smp.c (ffffffff81182174)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_from_idle
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff812285e3)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In fs/io_uring.c (ffffffff813e5383)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180f507)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff810697a5)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/smp.c (ffffffff811b8934)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff812696b0)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In io_uring/io_uring.c (ffffffff81e912bc)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
```
In drivers/iommu/amd/iommu.c (ffffffff81950107)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81079475)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/smp.c (ffffffff811f9d04)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff812be590)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In kernel/bpf/memalloc.c (ffffffff8131c13e)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In io_uring/io_uring.c (ffffffff817923b5)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_uring_poll
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_wake_function
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:io_run_local_work
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab5162)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8107b725)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/smp.c (ffffffff8120f0e4)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff812e51d0)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In kernel/bpf/memalloc.c (ffffffff8134bc13)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In io_uring/io_uring.c (ffffffff817d3046)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_poll
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_run_task_work_sig
  - io_uring/io_uring.c:io_wake_function
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:__io_run_local_work
```
```
In drivers/iommu/amd/iommu.c (ffffffff81affd32)
Location: include/linux/llist.h:189
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81082be5)
Location: include/linux/llist.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/smp.c (ffffffff81226884)
Location: include/linux/llist.h:216
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff81303280)
Location: include/linux/llist.h:216
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run_list
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In kernel/bpf/memalloc.c (ffffffff8137201f)
Location: include/linux/llist.h:216
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:check_leaked_objs
  - kernel/bpf/memalloc.c:check_leaked_objs
  - kernel/bpf/memalloc.c:check_leaked_objs
  - kernel/bpf/memalloc.c:check_leaked_objs
  - kernel/bpf/memalloc.c:check_leaked_objs
  - kernel/bpf/memalloc.c:check_leaked_objs
  - kernel/bpf/memalloc.c:check_leaked_objs
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
  - kernel/bpf/memalloc.c:bpf_mem_refill
```
```
In io_uring/io_uring.c (ffffffff81816335)
Location: include/linux/llist.h:216
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_poll
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_run_task_work_sig
  - io_uring/io_uring.c:io_wake_function
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:__io_run_local_work
```
```
In lib/lwq.c (ffffffff8185b9eb)
Location: include/linux/llist.h:216
Inline: True
Inline callers:
  - lib/lwq.c:lwq_dequeue_all
  - lib/lwq.c:__lwq_dequeue
  - lib/lwq.c:__lwq_dequeue
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b53a42)
Location: include/linux/llist.h:216
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:iommu_init_device
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
In kernel/sched/core.c (ffff80001013c4cc)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffff8000101bda14)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffff80001025b340)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
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
In kernel/sched/core.c (c038c1e0)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (c04059e8)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (c048e4f8)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
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
In kernel/sched/core.c (c00000000018aae0)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (c000000000222c20)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (c0000000002feff8)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
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
In kernel/sched/core.c (ffffffe0000eb84a)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffe0001404aa)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffe00019a398)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fcd5)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810d6b51)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff81146e46)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811d3143)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a5595)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8103f235)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810c5441)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff8113a146)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811c5f03)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In drivers/iommu/amd_iommu.c (ffffffff81682f85)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff8104fb85)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810d3791)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff81144cf6)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811d0f13)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d3805)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
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
In arch/x86/kernel/cpu/mce/genpool.c (ffffffff81050fc5)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/genpool.c:mce_gen_pool_empty
```
```
In kernel/sched/core.c (ffffffff810de711)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/smp.c (ffffffff81151876)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/smp.c:flush_smp_call_function_queue
```
```
In kernel/irq_work.c (ffffffff811df203)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In drivers/iommu/amd_iommu.c (ffffffff816edf05)
Location: include/linux/llist.h:187
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
```
</details>
</li>
</ul>

## Differences
