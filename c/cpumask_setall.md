# Function: <code>cpumask_setall</code>

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
In arch/x86/kernel/apic/vector.c (ffffffff81f72613)
Location: include/linux/cpumask.h:329
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff81068726)
Location: include/linux/cpumask.h:329
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain
```
```
In kernel/sched/core.c (ffffffff810af974)
Location: include/linux/cpumask.h:329
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff81f7ef49)
Location: include/linux/cpumask.h:329
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cpuset.c (ffffffff81f81fb4)
Location: include/linux/cpumask.h:329
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8114d713)
Location: include/linux/cpumask.h:329
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816ae9b1)
Location: include/linux/cpumask.h:329
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In arch/x86/kernel/apic/vector.c (ffffffff81f9ae30)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff81068426)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain
```
```
In kernel/sched/core.c (ffffffff810b217a)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff81fa7fa8)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cpuset.c (ffffffff81fab545)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff81155f2b)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81710260)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In arch/x86/kernel/apic/vector.c (ffffffff81fd6300)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff8106c079)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain
```
```
In kernel/sched/core.c (ffffffff810b855f)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - kernel/sched/core.c:build_sched_domains
```
```
In kernel/irq/irqdesc.c (ffffffff81fe3dce)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cpuset.c (ffffffff81fe77ed)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_init
  - kernel/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff81160678)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81742244)
Location: include/linux/cpumask.h:333
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In arch/x86/kernel/apic/vector.c (ffffffff820b700b)
Location: include/linux/cpumask.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
```
```
In arch/x86/kernel/vsmp_64.c (ffffffff8106b489)
Location: include/linux/cpumask.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/vsmp_64.c:fill_vector_allocation_domain
```
```
In kernel/irq/irqdesc.c (ffffffff820c48d1)
Location: include/linux/cpumask.h:361
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff820c7e34)
Location: include/linux/cpumask.h:361
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff81163a68)
Location: include/linux/cpumask.h:361
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817608e4)
Location: include/linux/cpumask.h:361
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In kernel/irq/irqdesc.c (ffffffff826ccb6a)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff826d0505)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811709e8)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d68b4)
Location: include/linux/cpumask.h:365
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In kernel/irq/irqdesc.c (ffffffff826f6d51)
Location: include/linux/cpumask.h:367
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff826fac47)
Location: include/linux/cpumask.h:367
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8117fb04)
Location: include/linux/cpumask.h:367
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8181f5a6)
Location: include/linux/cpumask.h:367
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In kernel/irq/irqdesc.c (ffffffff828adc7d)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff828b1b7a)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8118d474)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184b446)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In kernel/irq/irqdesc.c (ffffffff828c6633)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff828ca8ce)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8119ad8b)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8188e506)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In kernel/irq/irqdesc.c (ffffffff828cec60)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff828d2db0)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811a6c58)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c0696)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In kernel/irq/irqdesc.c (ffffffff82cf0041)
Location: include/linux/cpumask.h:402
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/cgroup/cpuset.c (ffffffff82cf3772)
Location: include/linux/cpumask.h:402
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811bf85f)
Location: include/linux/cpumask.h:402
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819925e6)
Location: include/linux/cpumask.h:402
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In kernel/irq/irqdesc.c (ffffffff82fdca2c)
Location: include/linux/cpumask.h:408
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/cgroup/cpuset.c (ffffffff82fe024c)
Location: include/linux/cpumask.h:408
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811bd488)
Location: include/linux/cpumask.h:408
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819957f6)
Location: include/linux/cpumask.h:408
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052c91)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
```
In kernel/irq/irqdesc.c (ffffffff831e780e)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff831eae2c)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811bcf88)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197a666)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b191)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In kernel/irq/irqdesc.c (ffffffff832cb900)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff832cf79e)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811e7a40)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a23686)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067c07)
Location: include/linux/cpumask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In kernel/irq/irqdesc.c (ffffffff8347f0aa)
Location: include/linux/cpumask.h:414
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8348350e)
Location: include/linux/cpumask.h:414
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8121cc1f)
Location: include/linux/cpumask.h:414
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8c98b)
Location: include/linux/cpumask.h:414
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077557)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In kernel/irq/irqdesc.c (ffffffff83eab1ab)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/cgroup/cpuset.c (ffffffff83eb0fd5)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8126753f)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2c3eb)
Location: include/linux/cpumask.h:479
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810797b7)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In kernel/irq/irqdesc.c (ffffffff836d016b)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/cgroup/cpuset.c (ffffffff836d5f73)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8127eae1)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In kernel/bpf/cpumask.c (ffffffff8135d895)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_setall
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9567b)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81081037)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:fake_panic_set
  - arch/x86/kernel/cpu/mce/core.c:mce_end
```
```
In kernel/irq/irqdesc.c (ffffffff8390158b)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:init_irq_default_affinity
```
```
In kernel/rcu/tree.c (ffffffff839020a3)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8390833d)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff812995a8)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In kernel/bpf/cpumask.c (ffffffff81386635)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_setall
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4d16b)
Location: include/linux/cpumask.h:539
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In arch/arm64/mm/context.c (ffff8000100affc4)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In kernel/irq/irqdesc.c (ffff8000114465dc)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffff80001144b3a8)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffff800010223ad8)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1e444)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In drivers/cpufreq/cpufreq-dt.c (ffff800010b264cc)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
```
```
In drivers/perf/arm_pmu_platform.c (ffff800010b95bac)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
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
In arch/arm/mm/context.c (0)
Location: include/linux/cpumask.h:395
Inline: True
```
```
In kernel/irq/irqdesc.c (c1520c4c)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (c1525848)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (c0461310)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (c0bfaaf0)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
```
In drivers/cpufreq/cpufreq-dt.c (c0c00330)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
```
```
In drivers/perf/arm_pmu_platform.c (c0c7f108)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
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
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011c780)
Location: include/linux/cpumask.h:395
Inline: True
```
```
In kernel/irq/irqdesc.c (c00000000136b3fc)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (c000000001370d28)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (c0000000002a8708)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (c000000000c13f64)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In arch/riscv/mm/cacheflush.c (ffffffe0000ba02a)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - arch/riscv/mm/cacheflush.c:flush_icache_mm
```
```
In kernel/irq/irqdesc.c (ffffffe00000813a)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/cpumask.h:395
Inline: True
```
```
In kernel/trace/trace.c (ffffffe00017f12e)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
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
In kernel/irq/irqdesc.c (ffffffff828b7958)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff828bbc61)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8119f278)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81864db6)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In kernel/irq/irqdesc.c (ffffffff828afbd8)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/rcu/tree.c (ffffffff828b05f8)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff828b42f4)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811922c8)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182da66)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In kernel/irq/irqdesc.c (ffffffff828ca894)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff828ce9e4)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff8119d048)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b5b46)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
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
In kernel/irq/irqdesc.c (ffffffff828cfc8d)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff828d3dde)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_init
  - kernel/cgroup/cpuset.c:cpuset_init
```
```
In kernel/trace/trace.c (ffffffff811aace8)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_pipe
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d1df6)
Location: include/linux/cpumask.h:395
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_init
```
</details>
</li>
</ul>

## Differences
