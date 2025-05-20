# Function: <code>update_debugctlmsr</code>

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
In arch/x86/events/intel/core.c (ffffffff8100c6fa)
Location: arch/x86/include/asm/processor.h:639
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8101075e)
Location: arch/x86/include/asm/processor.h:639
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
```
```
In arch/x86/kernel/process.c (ffffffff81039396)
Location: arch/x86/include/asm/processor.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103dc90)
Location: arch/x86/include/asm/processor.h:639
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f0d4)
Location: arch/x86/include/asm/processor.h:639
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
In arch/x86/events/intel/core.c (ffffffff8100c96a)
Location: arch/x86/include/asm/processor.h:650
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff810101d2)
Location: arch/x86/include/asm/processor.h:650
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/process.c (ffffffff8103839f)
Location: arch/x86/include/asm/processor.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103dab0)
Location: arch/x86/include/asm/processor.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f4e6)
Location: arch/x86/include/asm/processor.h:650
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
In arch/x86/events/intel/core.c (ffffffff8100ca32)
Location: arch/x86/include/asm/processor.h:725
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff81010392)
Location: arch/x86/include/asm/processor.h:725
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/process.c (ffffffff81037e48)
Location: arch/x86/include/asm/processor.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/step.c (ffffffff8103d398)
Location: arch/x86/include/asm/processor.h:725
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81062582)
Location: arch/x86/include/asm/processor.h:725
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
In arch/x86/events/intel/core.c (ffffffff8100c79b)
Location: arch/x86/include/asm/processor.h:738
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100e992)
Location: arch/x86/include/asm/processor.h:738
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8103b3d1)
Location: arch/x86/include/asm/processor.h:738
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106152c)
Location: arch/x86/include/asm/processor.h:738
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
In arch/x86/events/intel/core.c (ffffffff8100cd4e)
Location: arch/x86/include/asm/processor.h:760
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100f142)
Location: arch/x86/include/asm/processor.h:760
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8103de08)
Location: arch/x86/include/asm/processor.h:760
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106522c)
Location: arch/x86/include/asm/processor.h:760
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
In arch/x86/events/intel/core.c (ffffffff8100d47c)
Location: arch/x86/include/asm/processor.h:774
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
```
In arch/x86/events/intel/ds.c (ffffffff8100fa92)
Location: arch/x86/include/asm/processor.h:774
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8103f3a8)
Location: arch/x86/include/asm/processor.h:774
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81067df5)
Location: arch/x86/include/asm/processor.h:774
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
In arch/x86/events/intel/core.c (ffffffff8100cc0a)
Location: arch/x86/include/asm/processor.h:769
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81010062)
Location: arch/x86/include/asm/processor.h:769
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff810409a8)
Location: arch/x86/include/asm/processor.h:769
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106dcb5)
Location: arch/x86/include/asm/processor.h:769
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
In arch/x86/events/intel/core.c (ffffffff8100d44a)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff810111a2)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8104305e)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071cde)
Location: arch/x86/include/asm/processor.h:759
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
In arch/x86/events/intel/core.c (ffffffff8100d97a)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81011882)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff810437be)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81072d0e)
Location: arch/x86/include/asm/processor.h:759
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
In arch/x86/events/intel/core.c (ffffffff8100ea6d)
Location: arch/x86/include/asm/processor.h:780
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81012ce2)
Location: arch/x86/include/asm/processor.h:780
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff810471d8)
Location: arch/x86/include/asm/processor.h:780
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a252)
Location: arch/x86/include/asm/processor.h:780
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
In arch/x86/events/intel/core.c (ffffffff8100d71d)
Location: arch/x86/include/asm/processor.h:700
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81012882)
Location: arch/x86/include/asm/processor.h:700
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81046a28)
Location: arch/x86/include/asm/processor.h:700
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81079ac6)
Location: arch/x86/include/asm/processor.h:700
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
In arch/x86/events/intel/core.c (ffffffff8100f482)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81013a72)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff810482a8)
Location: arch/x86/include/asm/processor.h:682
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
In arch/x86/events/intel/core.c (ffffffff81010255)
Location: arch/x86/include/asm/processor.h:695
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81014d92)
Location: arch/x86/include/asm/processor.h:695
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8104ebb8)
Location: arch/x86/include/asm/processor.h:695
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
In arch/x86/events/intel/core.c (ffffffff81011869)
Location: arch/x86/include/asm/processor.h:695
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81016bc1)
Location: arch/x86/include/asm/processor.h:695
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81059ddf)
Location: arch/x86/include/asm/processor.h:695
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
In arch/x86/events/intel/core.c (ffffffff810152b1)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101ad51)
Location: arch/x86/include/asm/processor.h:572
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8106799f)
Location: arch/x86/include/asm/processor.h:572
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
In arch/x86/events/intel/core.c (ffffffff81014b14)
Location: arch/x86/include/asm/processor.h:570
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101a7e1)
Location: arch/x86/include/asm/processor.h:570
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8106924f)
Location: arch/x86/include/asm/processor.h:570
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
In arch/x86/events/intel/core.c (ffffffff81019b04)
Location: arch/x86/include/asm/processor.h:592
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81020341)
Location: arch/x86/include/asm/processor.h:592
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff810706bf)
Location: arch/x86/include/asm/processor.h:592
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
In arch/x86/events/intel/core.c (ffffffff8100d97a)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81011882)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8104393e)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071d0e)
Location: arch/x86/include/asm/processor.h:759
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
In arch/x86/events/intel/core.c (ffffffff8100c2a0)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff8101066b)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81032f72)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81061d35)
Location: arch/x86/include/asm/processor.h:759
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
In arch/x86/events/intel/core.c (ffffffff8100d93a)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81011842)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff8104377e)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81071cbe)
Location: arch/x86/include/asm/processor.h:759
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
In arch/x86/events/intel/core.c (ffffffff8100db0a)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_reset
```
```
In arch/x86/events/intel/ds.c (ffffffff81011a52)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pmu_disable_bts
  - arch/x86/events/intel/ds.c:intel_pmu_enable_bts
```
```
In arch/x86/kernel/step.c (ffffffff81044b7e)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:set_task_blockstep
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81073d3e)
Location: arch/x86/include/asm/processor.h:759
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:resume_execution
```
</details>
</li>
</ul>

## Differences
