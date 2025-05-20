# Function: <code>sync_core</code>

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
In arch/x86/kernel/alternative.c (ffffffff81035cf6)
Location: arch/x86/include/asm/processor.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:apply_alternatives
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104200f)
Location: arch/x86/include/asm/processor.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045296)
Location: arch/x86/include/asm/processor.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d251)
Location: arch/x86/include/asm/processor.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105a911)
Location: arch/x86/include/asm/processor.h:574
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
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
In arch/x86/kernel/alternative.c (ffffffff81034ee6)
Location: arch/x86/include/asm/processor.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:apply_alternatives
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041fe3)
Location: arch/x86/include/asm/processor.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:early_init_intel
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045623)
Location: arch/x86/include/asm/processor.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d27b)
Location: arch/x86/include/asm/processor.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105a981)
Location: arch/x86/include/asm/processor.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
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
In arch/x86/kernel/alternative.c (ffffffff81034bf9)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047232)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105d794)
Location: arch/x86/include/asm/processor.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
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
In arch/x86/kernel/alternative.c (ffffffff81032c29)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046ae0)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105ce94)
Location: arch/x86/include/asm/processor.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
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
In arch/x86/kernel/alternative.c (ffffffff81035039)
Location: arch/x86/include/asm/processor.h:671
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a550)
Location: arch/x86/include/asm/processor.h:671
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
```
In arch/x86/kernel/ftrace.c (ffffffff81060fb4)
Location: arch/x86/include/asm/processor.h:671
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
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
In arch/x86/kernel/alternative.c (ffffffff810361b5)
Location: arch/x86/include/asm/processor.h:687
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104cc0a)
Location: arch/x86/include/asm/processor.h:687
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
```
In arch/x86/kernel/ftrace.c (ffffffff810640d0)
Location: arch/x86/include/asm/processor.h:687
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
```
In kernel/sched/core.c (ffffffff810bb667)
Location: arch/x86/include/asm/processor.h:687
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In arch/x86/kernel/alternative.c (ffffffff810373a5)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104a8ab)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/ftrace.c (ffffffff81069d80)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
```
In kernel/sched/core.c (ffffffff810c4c0d)
Location: arch/x86/include/asm/processor.h:682
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In arch/x86/kernel/alternative.c (ffffffff81039655)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104da36)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106d630)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
```
In kernel/sched/core.c (ffffffff810ca807)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In arch/x86/kernel/alternative.c (ffffffff81039e25)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e3da)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106ec30)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
```
In kernel/sched/core.c (ffffffff810d3e6c)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In arch/x86/kernel/alternative.c (ffffffff8103ca95)
Location: arch/x86/include/asm/processor.h:695
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbe58c)
Location: arch/x86/include/asm/processor.h:695
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff810df1e0)
Location: arch/x86/include/asm/processor.h:695
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sync_core();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103cf45)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105242a)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
```
In kernel/sched/core.c (ffffffff810d6b07)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff81108ad2)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
```
**Symbols:**

```
ffffffff8104fee0-ffffffff8104ff03: sync_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sync_core();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103e7e5)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053cda)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
```
In kernel/sched/core.c (ffffffff810d87de)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff8110a9b9)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
```
**Symbols:**

```
ffffffff81051a50-ffffffff81051a73: sync_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sync_core();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81044555)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105c50a)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
```
In kernel/sched/core.c (ffffffff810ec06e)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff81129149)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
```
**Symbols:**

```
ffffffff81059fe0-ffffffff8105a003: sync_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sync_core();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8104c905)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81068c04)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
```
In kernel/sched/core.c (ffffffff8110651c)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff8113c097)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
```
**Symbols:**

```
ffffffff810667e0-ffffffff8106680f: sync_core (STB_LOCAL)
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
In arch/x86/kernel/alternative.c (ffffffff81058c65)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810765fc)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff8112c1dc)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff81166cb7)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
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
In arch/x86/kernel/alternative.c (ffffffff8105a535)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078867)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff811392dc)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff81177127)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
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
In arch/x86/kernel/alternative.c (ffffffff810616a5)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:optimize_nops_inplace
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107fd17)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In kernel/sched/core.c (ffffffff811440dc)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff81185097)
Location: arch/x86/include/asm/sync_core.h:58
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
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
In arch/x86/kernel/alternative.c (ffffffff81039f85)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e53a)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106dbd0)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
```
In kernel/sched/core.c (ffffffff810ce15c)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In arch/x86/kernel/alternative.c (ffffffff81029ce5)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103da0a)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/ftrace.c (ffffffff8105dff0)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
```
In kernel/sched/core.c (ffffffff810bca2b)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In arch/x86/kernel/alternative.c (ffffffff81039de5)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e38a)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/ftrace.c (ffffffff8106e080)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
```
In kernel/sched/core.c (ffffffff810cd58c)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
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
In arch/x86/kernel/alternative.c (ffffffff8103ade5)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f7ca)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/ftrace.c (ffffffff81070300)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:do_sync_core
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
```
In kernel/sched/core.c (ffffffff810d48d9)
Location: arch/x86/include/asm/processor.h:672
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
