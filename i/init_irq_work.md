# Function: <code>init_irq_work</code>

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
In arch/x86/kernel/nmi.c (ffffffff8103248a)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81f6b08b)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
```
```
In kernel/sched/rt.c (ffffffff810c10e4)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/trace/ring_buffer.c (ffffffff81149dca)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
```
```
In kernel/events/core.c (ffffffff8117e930)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81185e94)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff81fa372e)
Location: include/linux/irq_work.h:27
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
In arch/x86/kernel/nmi.c (ffffffff810315bf)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81f93396)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
```
```
In kernel/sched/rt.c (ffffffff810c4b74)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/printk/nmi.c (ffffffff81fa7ec7)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_init
```
```
In kernel/trace/ring_buffer.c (ffffffff81152b76)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/events/core.c (ffffffff81190405)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff81fcfc7c)
Location: include/linux/irq_work.h:27
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8171721f)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/nmi.c (ffffffff8103120f)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81fce9d8)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
```
```
In kernel/sched/rt.c (ffffffff810cabc4)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d48e0)
Location: include/linux/irq_work.h:27
Inline: True
```
```
In kernel/printk/nmi.c (ffffffff81fe3c2d)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/printk/nmi.c:printk_nmi_init
```
```
In kernel/relay.c (ffffffff8114e813)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff8115cbcc)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/events/core.c (ffffffff8119f2c5)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff8200d333)
Location: include/linux/irq_work.h:27
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81749005)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/nmi.c (ffffffff8102f4e4)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff820af381)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
```
```
In kernel/sched/rt.c (ffffffff810c4ed3)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/sched/rt.c:init_rt_rq
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810d3c41)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (ffffffff820c4736)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/relay.c (ffffffff81150ed3)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff8115fc1c)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/events/core.c (ffffffff811a5d37)
Location: include/linux/irq_work.h:27
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff820eed08)
Location: include/linux/irq_work.h:27
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817676a3)
Location: include/linux/irq_work.h:27
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/nmi.c (ffffffff810314e4)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff826b5c1a)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff810d2802)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810db913)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (ffffffff826cc9a8)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (ffffffff810fcdb6)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffffffff8115d6c3)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff8116ccec)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/events/core.c (ffffffff811b9927)
Location: include/linux/irq_work.h:28
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff826f851e)
Location: include/linux/irq_work.h:28
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816a87e8)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff817dd5b9)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/nmi.c (ffffffff8103242b)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff826df97f)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff810da8ea)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e39e6)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (ffffffff826f6bcc)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (ffffffff81104f83)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffffffff8116c633)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff8117bcac)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/bpf/stackmap.c (ffffffff826ffc90)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff811d8c84)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff827228cd)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816e4b48)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8182623e)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/nmi.c (ffffffff810336eb)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82895932)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff810e443a)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810edff6)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (ffffffff828adaf8)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (ffffffff811106f5)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffffffff8117a063)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff81188dac)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/bpf/stackmap.c (ffffffff828b6cfa)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff811e9181)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff828daa06)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81707eb8)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818520ae)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/nmi.c (ffffffff810358be)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:__register_nmi_handler
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828ad4b5)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff810eb04a)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f4dae)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (ffffffff828c64a9)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (ffffffff81119e19)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffffffff81186ea6)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff81194eed)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/bpf_trace.c (ffffffff828ceaea)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/stackmap.c (ffffffff828d0312)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff8120249a)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff828f5307)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81743156)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817433a6)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818955f5)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b07f9)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff810f69ea)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81100a1e)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (ffffffff828cead6)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (ffffffff81126227)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffffffff81192dc6)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff811a09ad)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/bpf_trace.c (ffffffff828d6fc6)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/stackmap.c (ffffffff828d874f)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff8120f2ca)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff828fe35e)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff817670c3)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81767346)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818c7605)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff82cd58eb)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff81100499)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b05b)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
```
In kernel/printk/printk_safe.c (ffffffff82ceff3b)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (ffffffff81134fe1)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffffffff811a7c06)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6f92)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffff811bed96)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
```
In kernel/trace/bpf_trace.c (ffffffff82cf6c06)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/ringbuf.c (ffffffff8121e505)
Location: include/linux/irq_work.h:28
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff82cf7bb8)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff8123a4b5)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff82d152c5)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81827553)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818278e6)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81999845)
Location: include/linux/irq_work.h:28
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff82fc188e)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff810fefda)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81107f8b)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
```
In kernel/printk/printk_safe.c (ffffffff82fdc920)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/relay.c (ffffffff811a5ff6)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4b5b)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffff811bc976)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
```
In kernel/trace/bpf_trace.c (ffffffff82fe370d)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81221264)
Location: include/linux/irq_work.h:34
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffff82fe4820)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff812438ce)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff83002f5c)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81837fd3)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8183837d)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8199c925)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff831cbf74)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff8110132a)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a0cb)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
```
In kernel/printk/printk_safe.c (ffffffff831e7685)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/relay.c (ffffffff811a69a6)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3ef0)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffff811bc466)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
```
In kernel/trace/bpf_trace.c (ffffffff831ede69)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81224c1a)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff831eef32)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff81248877)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff8320dfee)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8181b2c3)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181b65a)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81981606)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff832ad7d8)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff8111d54a)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81128669)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
```
In kernel/relay.c (ffffffff811d0196)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff811ddf00)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffff811e6c25)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
```
In kernel/trace/bpf_trace.c (ffffffff832d2b28)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/ringbuf.c (ffffffff8125cb5a)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff832d455d)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff8128366d)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff832f6874)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818a5733)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a5b75)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81a2a8fb)
Location: include/linux/irq_work.h:34
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8345e682)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/build_utility.c (ffffffff8114248d)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_kthread_create
```
```
In kernel/rcu/tree.c (ffffffff8117d1c3)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
```
```
In kernel/relay.c (ffffffff81204713)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff81215047)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffff8121eacb)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
```
In kernel/trace/pid_list.c (ffffffff8122b9a9)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_alloc
```
```
In kernel/trace/bpf_trace.c (ffffffff83486f7d)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/task_iter.c (ffffffff83488940)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_iter_init
```
```
In kernel/bpf/ringbuf.c (ffffffff812a69ef)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/core.c (ffffffff812d6675)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff834aed7e)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:acpi_ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff819ef539)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819efaa5)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81b94c28)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff83e7f8be)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/build_utility.c (ffffffff8116e8dd)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_kthread_create
```
```
In kernel/rcu/tree.c (ffffffff811b6ac9)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
```
```
In kernel/relay.c (ffffffff8124cab3)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e71a)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffff8126923c)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
```
In kernel/trace/pid_list.c (ffffffff81277399)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_alloc
```
```
In kernel/trace/bpf_trace.c (ffffffff83eb68c9)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/task_iter.c (ffffffff83eb8ca2)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_iter_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81304eb9)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/bpf/memalloc.c (ffffffff8131bf25)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:prefill_mem_cache
```
```
In kernel/events/core.c (ffffffff8133f440)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff83ee81a9)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:acpi_ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81b6cae9)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d0d5)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d34fe8)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff836a260e)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/build_utility.c (ffffffff8117ef7d)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_kthread_create
```
```
In kernel/rcu/tree.c (ffffffff811c74f9)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
```
```
In kernel/relay.c (ffffffff81263e33)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff812758fa)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffff812803d1)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
```
In kernel/trace/pid_list.c (ffffffff8128edb9)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_alloc
```
```
In kernel/trace/bpf_trace.c (ffffffff836dbeb9)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/task_iter.c (ffffffff836de1d2)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_iter_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81333849)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/bpf/memalloc.c (ffffffff8134b9d5)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:prefill_mem_cache
```
```
In kernel/events/core.c (ffffffff81370610)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff8370db79)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:acpi_ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc0229)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0805)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81d9e35e)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff838d270e)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/build_utility.c (ffffffff8118cd6d)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_kthread_create
```
```
In kernel/rcu/tree.c (ffffffff811d7a19)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
```
```
In kernel/relay.c (ffffffff8127dc23)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff81290175)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffff8129a5c3)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/trace.c:init_tracer_tracefs
```
```
In kernel/trace/pid_list.c (ffffffff812aa2ba)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_alloc
```
```
In kernel/trace/bpf_trace.c (ffffffff8390e4e9)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/task_iter.c (ffffffff83910812)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_iter_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81357f39)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/bpf/memalloc.c (ffffffff813719c5)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:init_refill_work
```
```
In kernel/events/core.c (ffffffff81399910)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff83941259)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:acpi_ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c149a9)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c14f85)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e560ee)
Location: include/linux/irq_work.h:37
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In kernel/sched/topology.c (ffff80001015ac4c)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffff8000101651d4)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (ffff800011446418)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (ffff80001018cc7c)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffff80001020aab0)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffff80001021a190)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/bpf_trace.c (ffff80001144f964)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/stackmap.c (ffff800011451170)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffff80001029733c)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffff80001148116c)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffff800010967e68)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffff8000109683c4)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (ffff800010b259a0)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In kernel/sched/topology.c (c03a78dc)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (c03b1814)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (c1520ad8)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (c03dad5c)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (c0449690)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (c0457660)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/bpf_trace.c (c152a120)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/stackmap.c (c152bc10)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (c04c74c4)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/dma-buf/dma-fence-array.c (c0a3e240)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (c0a3e63c)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (c0bff2e8)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In kernel/sched/topology.c (c0000000001af1bc)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (c0000000001bc3d4)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (c00000000136b1b0)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (c0000000001e740c)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (c000000000287e44)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (c00000000029d4c4)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/bpf_trace.c (c000000001376b7c)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/stackmap.c (c000000001378adc)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (c000000000346c40)
Location: include/linux/irq_work.h:31
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (c000000000a1f6f8)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (c000000000a1fbcc)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (c000000000c1ac1c)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In kernel/sched/topology.c (ffffffe00010029a)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/printk/printk_safe.c (ffffffe000007f82)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (ffffffe000120c38)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffffffe00016c4dc)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffe000177e50)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/bpf/stackmap.c (ffffffe000010d5e)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffe0001c9e28)
Location: include/linux/irq_work.h:31
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffe0005d3fb8)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d42aa)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8289e818)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff810efdea)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f9d2e)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (ffffffff828b77ce)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (ffffffff8111e807)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffffffff8118b3e6)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff81198fcd)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/bpf_trace.c (ffffffff828bfe77)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/stackmap.c (ffffffff828c1600)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff812078ea)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8171b7b3)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171ba36)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff8186bd25)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff828969e9)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff810dfe5a)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e9f0e)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (ffffffff828afa4e)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/irq/irq_sim.c (ffffffff81108af1)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_init
```
```
In kernel/rcu/tree.c (ffffffff8111007c)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffffffff8117e4e6)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff8118c80d)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/bpf_trace.c (ffffffff828b8517)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/stackmap.c (ffffffff828b9ca0)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff811faa1a)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816f4c13)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f4e96)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818349d5)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b17db)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff810ecf1a)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f6f4e)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (ffffffff828ca70a)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (ffffffff8111c6f7)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffffffff811891b6)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff81196d9d)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/bpf_trace.c (ffffffff828d2bfa)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/stackmap.c (ffffffff828d4383)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff812056ba)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff828f9681)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8175a583)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175a806)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818bcab5)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b1809)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init
```
```
In kernel/sched/topology.c (ffffffff810f7f5a)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/topology.c:init_rootdomain
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81101fce)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
```
In kernel/printk/printk_safe.c (ffffffff828cfb03)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/printk/printk_safe.c:printk_safe_init
  - kernel/printk/printk_safe.c:printk_safe_init
```
```
In kernel/rcu/tree.c (ffffffff8112a6b2)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__rcu_read_unlock
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
```
In kernel/relay.c (ffffffff81196b06)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/ring_buffer.c (ffffffff811a49ad)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/bpf_trace.c (ffffffff828d801b)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
```
```
In kernel/bpf/stackmap.c (ffffffff828d97a4)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_init
```
```
In kernel/events/core.c (ffffffff8121452a)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In drivers/acpi/apei/ghes.c (ffffffff828ff3b2)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81775b43)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_create
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81775dc6)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_init
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff818d8da5)
Location: include/linux/irq_work.h:31
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
</details>
</li>
</ul>

## Differences
