# Function: <code>cr4_set_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005892)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/xen/enlighten.c (ffffffff8101cdb6)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103925d)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810398e5)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b755)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040e1c)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045472)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic
```
```
In arch/x86/mm/init.c (ffffffff8107d49b)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In kernel/sched/core.c (ffffffff8181fc92)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:idle_task_exit
```
```
In mm/mmu_context.c (ffffffff811afcbd)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffffffff812137ed)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
```
**Symbols:**

```
ffffffff8107d49b-ffffffff8107d4c0: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005b22)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/xen/enlighten.c (ffffffff8101bfd6)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8103845d)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810388d6)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b0f8)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040d3b)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104552d)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8107ef78)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff810724a1)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff8107ef78-ffffffff8107ef9d: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005a62)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/xen/enlighten.c (ffffffff8101c7e6)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81037ee2)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810382f6)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103a9d8)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040768)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104713d)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81083628)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81076035)
Location: arch/x86/include/asm/tlbflush.h:88
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff81083628-ffffffff8108364d: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810057b0)
Location: arch/x86/include/asm/tlbflush.h:93
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff81035e36)
Location: arch/x86/include/asm/tlbflush.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810364d6)
Location: arch/x86/include/asm/tlbflush.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810388f8)
Location: arch/x86/include/asm/tlbflush.h:93
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e6f3)
Location: arch/x86/include/asm/tlbflush.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810469cd)
Location: arch/x86/include/asm/tlbflush.h:93
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8106b937)
Location: arch/x86/include/asm/tlbflush.h:93
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff8107475b)
Location: arch/x86/include/asm/tlbflush.h:93
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff8106b937-ffffffff8106b95d: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005bd1)
Location: arch/x86/include/asm/tlbflush.h:258
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103815d)
Location: arch/x86/include/asm/tlbflush.h:258
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103888a)
Location: arch/x86/include/asm/tlbflush.h:258
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103aa03)
Location: arch/x86/include/asm/tlbflush.h:258
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810412f3)
Location: arch/x86/include/asm/tlbflush.h:258
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a41e)
Location: arch/x86/include/asm/tlbflush.h:258
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff810701c6)
Location: arch/x86/include/asm/tlbflush.h:258
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff8107a54f)
Location: arch/x86/include/asm/tlbflush.h:258
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff810701c6-ffffffff81070208: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006361)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff810392ce)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81039db5)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103bf03)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042c27)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104cacd)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff810730c7)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff8107d2ba)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff810730c7-ffffffff81073109: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810062b1)
Location: arch/x86/include/asm/tlbflush.h:291
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103a52e)
Location: arch/x86/include/asm/tlbflush.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103b2d5)
Location: arch/x86/include/asm/tlbflush.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103d3c3)
Location: arch/x86/include/asm/tlbflush.h:291
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81044292)
Location: arch/x86/include/asm/tlbflush.h:291
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104a1ad)
Location: arch/x86/include/asm/tlbflush.h:291
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81079161)
Location: arch/x86/include/asm/tlbflush.h:291
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81083d68)
Location: arch/x86/include/asm/tlbflush.h:291
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff81079161-ffffffff810791a3: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810064c1)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103cae7)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103d905)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fc73)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104681a)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d32d)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8107cd61)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff810879c5)
Location: arch/x86/include/asm/tlbflush.h:293
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff8107cd61-ffffffff8107cda3: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d2a7)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e0c5)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040393)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046f7a)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dccd)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8107de01)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8107de01-ffffffff8107de43: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810402e7)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810411b5)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810436e9)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104adb2)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810533ad)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81084501)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:cr4_set_bits_and_update_boot
```
**Symbols:**

```
ffffffff81084501-ffffffff8108452b: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040237)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81041085)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810436f5)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a2b0)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810524cd)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81bd877a)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:cr4_set_bits_and_update_boot
```
**Symbols:**

```
ffffffff81bd877a-ffffffff81bd87a4: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81041c07)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81042a75)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81044f45)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104ada0)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053d82)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81bca61e)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:cr4_set_bits_and_update_boot
```
**Symbols:**

```
ffffffff8104ada0-ffffffff8104add5: cr4_set_bits (STB_LOCAL)
ffffffff81bca61e-ffffffff81bca64b: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81047ed7)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81048de5)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b50e)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81051e30)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105c5e1)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81c9fa9d)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:cr4_set_bits_and_update_boot
```
**Symbols:**

```
ffffffff81051e30-ffffffff81051e65: cr4_set_bits (STB_LOCAL)
ffffffff81c9fa9d-ffffffff81c9faca: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81050bb0)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Direct callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810521a0)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81055660)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105d1c0)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067a40)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81e4f2ff)
Location: arch/x86/include/asm/tlbflush.h:36
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:cr4_set_bits_and_update_boot
```
**Symbols:**

```
ffffffff81050bb0-ffffffff81050beb: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff810521a0-ffffffff810521db: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff81055660-ffffffff8105569b: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff8105d1c0-ffffffff8105d1f6: cr4_set_bits (STB_LOCAL)
ffffffff81067a40-ffffffff81067a7b: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff81e4f2ff-ffffffff81e4f333: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105e0c0)
Location: arch/x86/include/asm/tlbflush.h:37
Inline: True
Direct callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8105f990)
Location: arch/x86/include/asm/tlbflush.h:37
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810631d0)
Location: arch/x86/include/asm/tlbflush.h:37
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106b5f0)
Location: arch/x86/include/asm/tlbflush.h:37
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076fa0)
Location: arch/x86/include/asm/tlbflush.h:37
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff810c0c50)
Location: arch/x86/include/asm/tlbflush.h:37
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:probe_page_size_mask
```
**Symbols:**

```
ffffffff8105e0c0-ffffffff8105e0ff: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff8105f990-ffffffff8105f9cf: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff810631d0-ffffffff8106320f: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff8106b5f0-ffffffff8106b633: cr4_set_bits (STB_LOCAL)
ffffffff81076fa0-ffffffff81076fdf: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff810c0c50-ffffffff810c0c93: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105f770)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
Direct callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810610e0)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064b20)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106cfa0)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810791b0)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff810c4330)
Location: arch/x86/include/asm/tlbflush.h:40
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:probe_page_size_mask
```
**Symbols:**

```
ffffffff8105f770-ffffffff8105f7af: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff810610e0-ffffffff8106111f: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff81064b20-ffffffff81064b5f: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff8106cfa0-ffffffff8106cfe3: cr4_set_bits (STB_LOCAL)
ffffffff810791b0-ffffffff810791ef: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff810c4330-ffffffff810c4373: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81066820)
Location: arch/x86/include/asm/tlbflush.h:41
Inline: True
Direct callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810681f0)
Location: arch/x86/include/asm/tlbflush.h:41
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106bfb0)
Location: arch/x86/include/asm/tlbflush.h:41
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81074610)
Location: arch/x86/include/asm/tlbflush.h:41
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080760)
Location: arch/x86/include/asm/tlbflush.h:41
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff810cc780)
Location: arch/x86/include/asm/tlbflush.h:41
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:probe_page_size_mask
```
**Symbols:**

```
ffffffff81066820-ffffffff8106685f: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff810681f0-ffffffff8106822f: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff8106bfb0-ffffffff8106bfef: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff81074610-ffffffff81074673: cr4_set_bits (STB_LOCAL)
ffffffff81080760-ffffffff8108079f: cr4_set_bits.constprop.0 (STB_LOCAL)
ffffffff810cc780-ffffffff810cc7c3: cr4_set_bits (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d427)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e245)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040513)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810470fa)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104de2d)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8107ce01)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8107ce01-ffffffff8107ce43: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8102cad7)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8102da65)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102fd13)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810361c0)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103d2dd)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8106c571)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8106c571-ffffffff8106c59b: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d267)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e085)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040353)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046f3a)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dc7d)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8107cdb1)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8107cdb1-ffffffff8107cdf3: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_set_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103e33e)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103f205)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041723)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104833a)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f0bd)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8107eeb1)
Location: arch/x86/include/asm/tlbflush.h:313
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8107eeb1-ffffffff8107eef3: cr4_set_bits (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
