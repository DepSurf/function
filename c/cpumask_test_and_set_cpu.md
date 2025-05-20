# Function: <code>cpumask_test_and_set_cpu</code>

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
In arch/x86/xen/smp.c (ffffffff8102b758)
Location: include/linux/cpumask.h:306
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041092)
Location: include/linux/cpumask.h:306
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/time/tick-broadcast.c (ffffffff810fd68e)
Location: include/linux/cpumask.h:306
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In mm/vmstat.c (ffffffff811ad4e9)
Location: include/linux/cpumask.h:306
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b20e4)
Location: include/linux/cpumask.h:306
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
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
In arch/x86/xen/smp.c (ffffffff8102aa68)
Location: include/linux/cpumask.h:310
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040fa9)
Location: include/linux/cpumask.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/time/tick-broadcast.c (ffffffff811049f8)
Location: include/linux/cpumask.h:310
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81714259)
Location: include/linux/cpumask.h:310
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
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
In arch/x86/xen/smp.c (ffffffff8102abfd)
Location: include/linux/cpumask.h:310
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810409f1)
Location: include/linux/cpumask.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8110c140)
Location: include/linux/cpumask.h:310
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81745f86)
Location: include/linux/cpumask.h:310
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_add_dev
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
In arch/x86/xen/smp_pv.c (ffffffff810294bd)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e97b)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8110e4d3)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81761772)
Location: include/linux/cpumask.h:338
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/xen/smp_pv.c (ffffffff810296dd)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041641)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/time/tick-broadcast.c (ffffffff81119753)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d7722)
Location: include/linux/cpumask.h:342
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/xen/smp_pv.c (ffffffff8102a15d)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042f20)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/time/tick-broadcast.c (ffffffff811262dc)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81820132)
Location: include/linux/cpumask.h:344
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/xen/smp_pv.c (ffffffff8102a7ad)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810444f9)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/time/tick-broadcast.c (ffffffff811319bc)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184bfe2)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/xen/smp_pv.c (ffffffff8102c5c4)
Location: include/linux/cpumask.h:356
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046ac9)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/time/tick-broadcast.c (ffffffff8113c53e)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8188f112)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/xen/smp_pv.c (ffffffff8102ce94)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047249)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/cpu.c (ffffffff810a4570)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8114814e)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c10f2)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/xen/smp_pv.c (ffffffff8102ee45)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a070)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:wait_for_master_cpu
```
```
In kernel/cpu.c (ffffffff810ab840)
Location: include/linux/cpumask.h:379
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81157f8e)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81992e72)
Location: include/linux/cpumask.h:379
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/xen/smp_pv.c (ffffffff8102fc55)
Location: include/linux/cpumask.h:385
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81049510)
Location: include/linux/cpumask.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:wait_for_master_cpu
```
```
In kernel/cpu.c (ffffffff810a70c0)
Location: include/linux/cpumask.h:385
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8115407e)
Location: include/linux/cpumask.h:385
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81996092)
Location: include/linux/cpumask.h:385
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/xen/smp_pv.c (ffffffff81030765)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104bfe1)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/cpu.c (ffffffff810a8160)
Location: include/linux/cpumask.h:356
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811554ef)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197ae62)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/xen/smp_pv.c (ffffffff81035635)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810533e2)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/cpu.c (ffffffff810b9c10)
Location: include/linux/cpumask.h:356
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff81179887)
Location: include/linux/cpumask.h:356
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a24236)
Location: include/linux/cpumask.h:356
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
In arch/x86/xen/smp_pv.c (ffffffff8103b465)
Location: include/linux/cpumask.h:391
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105ee82)
Location: include/linux/cpumask.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/cpu.c (ffffffff810d0710)
Location: include/linux/cpumask.h:391
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811aee26)
Location: include/linux/cpumask.h:391
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8d936)
Location: include/linux/cpumask.h:391
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
In arch/x86/xen/smp_pv.c (ffffffff81043c35)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d5f2)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/cpu.c (ffffffff810eeff0)
Location: include/linux/cpumask.h:456
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811ef5e6)
Location: include/linux/cpumask.h:456
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2d29a)
Location: include/linux/cpumask.h:456
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
In arch/x86/xen/smp_pv.c (ffffffff81043d35)
Location: include/linux/cpumask.h:516
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In kernel/cpu.c (ffffffff810fafa0)
Location: include/linux/cpumask.h:516
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114301c)
Location: include/linux/cpumask.h:516
Inline: True
Inline callers:
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/time/tick-broadcast.c (ffffffff81203d7c)
Location: include/linux/cpumask.h:516
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/bpf/cpumask.c (ffffffff8135d823)
Location: include/linux/cpumask.h:516
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_set_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d9650a)
Location: include/linux/cpumask.h:516
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
In arch/x86/xen/smp_pv.c (ffffffff8104a235)
Location: include/linux/cpumask.h:516
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In kernel/cpu.c (ffffffff81104440)
Location: include/linux/cpumask.h:516
Inline: True
```
```
In kernel/sched/core.c (ffffffff8114e4ec)
Location: include/linux/cpumask.h:516
Inline: True
Inline callers:
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
  - kernel/sched/core.c:mm_cid_get
```
```
In kernel/time/tick-broadcast.c (ffffffff8121a33c)
Location: include/linux/cpumask.h:516
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In kernel/bpf/cpumask.c (ffffffff813865c3)
Location: include/linux/cpumask.h:516
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_test_and_set_cpu
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4e16a)
Location: include/linux/cpumask.h:516
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
In kernel/cpu.c (ffff8000100fa220)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffff8000101b39f4)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1f548)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In kernel/cpu.c (c03583b4)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In kernel/sched/core.c (c038d29c)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:__schedule
```
```
In kernel/time/tick-broadcast.c (c03fda20)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In mm/mmu_context.c (c05048d0)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (c0575240)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (c0bf8abc)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
```
In drivers/cpuidle/coupled.c (c0c04f3c)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - drivers/cpuidle/coupled.c:cpuidle_coupled_poke_others
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
In kernel/cpu.c (c00000000013e120)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In kernel/time/tick-broadcast.c (c0000000002192f0)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (c000000000c10eb4)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe00000479e)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
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
In arch/x86/xen/smp_pv.c (ffffffff8102cff4)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810473c9)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/cpu.c (ffffffff8109de90)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8114076e)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81865812)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/kernel/cpu/common.c (ffffffff8103654d)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/cpu.c (ffffffff8108c8b0)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff811334ee)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182e4c2)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/xen/smp_pv.c (ffffffff8102ce54)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047209)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/cpu.c (ffffffff8109de40)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8113e61e)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b65a2)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
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
In arch/x86/xen/smp_pv.c (ffffffff8102dc44)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048609)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/cpu.c (ffffffff810a5d30)
Location: include/linux/cpumask.h:372
Inline: True
```
```
In kernel/time/tick-broadcast.c (ffffffff8114b12c)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_control
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d2852)
Location: include/linux/cpumask.h:372
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:add_cpu_dev_symlink
```
</details>
</li>
</ul>

## Differences
