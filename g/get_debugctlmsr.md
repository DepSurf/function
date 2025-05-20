# Function: <code>get_debugctlmsr</code>

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
In arch/x86/events/intel/core.c (ffffffff8100c6e5)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8101072c)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
```
```
In arch/x86/kernel/process.c (ffffffff8103937e)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103dc2c)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f0c0)
Location: arch/x86/include/asm/processor.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100c95a)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff810101c3)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/process.c (ffffffff8103838b)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103da69)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f4d7)
Location: arch/x86/include/asm/processor.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100ca22)
Location: arch/x86/include/asm/processor.h:712
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010383)
Location: arch/x86/include/asm/processor.h:712
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/process.c (ffffffff81037e31)
Location: arch/x86/include/asm/processor.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103d359)
Location: arch/x86/include/asm/processor.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81062573)
Location: arch/x86/include/asm/processor.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100c78b)
Location: arch/x86/include/asm/processor.h:725
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e983)
Location: arch/x86/include/asm/processor.h:725
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8103b3a9)
Location: arch/x86/include/asm/processor.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106151d)
Location: arch/x86/include/asm/processor.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100cd3c)
Location: arch/x86/include/asm/processor.h:747
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f133)
Location: arch/x86/include/asm/processor.h:747
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8103ddc9)
Location: arch/x86/include/asm/processor.h:747
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106521d)
Location: arch/x86/include/asm/processor.h:747
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100d470)
Location: arch/x86/include/asm/processor.h:761
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fa83)
Location: arch/x86/include/asm/processor.h:761
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8103f369)
Location: arch/x86/include/asm/processor.h:761
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81067de6)
Location: arch/x86/include/asm/processor.h:761
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100cbfb)
Location: arch/x86/include/asm/processor.h:756
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81010053)
Location: arch/x86/include/asm/processor.h:756
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81040969)
Location: arch/x86/include/asm/processor.h:756
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106dca6)
Location: arch/x86/include/asm/processor.h:756
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100d43b)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101118e)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81043019)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071ccf)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100d96b)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101186e)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81043779)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81072cff)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100ea5e)
Location: arch/x86/include/asm/processor.h:767
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81012cce)
Location: arch/x86/include/asm/processor.h:767
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81047199)
Location: arch/x86/include/asm/processor.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a243)
Location: arch/x86/include/asm/processor.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100d70e)
Location: arch/x86/include/asm/processor.h:687
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101286e)
Location: arch/x86/include/asm/processor.h:687
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff810469e9)
Location: arch/x86/include/asm/processor.h:687
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81079ab6)
Location: arch/x86/include/asm/processor.h:687
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_fault_handler
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100f478)
Location: arch/x86/include/asm/processor.h:669
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81013a5e)
Location: arch/x86/include/asm/processor.h:669
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81048269)
Location: arch/x86/include/asm/processor.h:669
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
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
In arch/x86/events/intel/core.c (ffffffff8101024b)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81014d7e)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8104eb79)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
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
In arch/x86/events/intel/core.c (ffffffff8101185f)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81016bae)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81059d88)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
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
In arch/x86/events/intel/core.c (ffffffff810152a3)
Location: arch/x86/include/asm/processor.h:559
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101ad3e)
Location: arch/x86/include/asm/processor.h:559
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81067948)
Location: arch/x86/include/asm/processor.h:559
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
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
In arch/x86/events/intel/core.c (ffffffff81014b06)
Location: arch/x86/include/asm/processor.h:557
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101a7ce)
Location: arch/x86/include/asm/processor.h:557
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff810691f8)
Location: arch/x86/include/asm/processor.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
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
In arch/x86/events/intel/core.c (ffffffff81019af6)
Location: arch/x86/include/asm/processor.h:579
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8102032e)
Location: arch/x86/include/asm/processor.h:579
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81070668)
Location: arch/x86/include/asm/processor.h:579
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d96b)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101186e)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff810438f9)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071cff)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100c27b)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101063e)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81032f15)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81061d0f)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100d92b)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101182e)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81043739)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071caf)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
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
In arch/x86/events/intel/core.c (ffffffff8100dafb)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81011a3e)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81044b39)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81073d2f)
Location: arch/x86/include/asm/processor.h:746
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
</details>
</li>
</ul>

## Differences
