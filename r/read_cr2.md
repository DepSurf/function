# Function: <code>read_cr2</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102d2c9)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/nmi.c (ffffffff810329c6)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81063f01)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106b7ad)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_page_fault
  - arch/x86/mm/fault.c:trace_do_page_fault
```
```
In arch/x86/power/cpu.c (ffffffff816faff9)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8102c2ab)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/nmi.c (ffffffff81031b46)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81063b21)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106b6c1)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff81fa0796)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff8176020d)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8102c29a)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102ebc5)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff81031796)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81066fcc)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106f2e1)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff81fdbd07)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff8178d20d)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8102a48a)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102ced5)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff8102f9a6)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff81066295)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106ea31)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:trace_do_page_fault
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff820bccd9)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff817ab37d)
Location: arch/x86/include/asm/paravirt.h:54
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8102b1f2)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102dc95)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff810319b6)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106a486)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81073ab1)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff826c38cf)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff81822870)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8102cf5f)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102ec25)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff81032b26)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff8106d0e6)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810763f0)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff826edb54)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff8186cab0)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8102e1ad)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102fe55)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff81033ed6)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810732b6)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8107c6a0)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff828a46e6)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff8188cac0)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8102ff36)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/nmi.c (ffffffff81035c54)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828bcbb2)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff818d7430)
Location: arch/x86/include/asm/paravirt.h:117
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
In arch/x86/kernel/process_64.c (ffffffff81030896)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/nmi.c (ffffffff8103646b)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828c304d)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff81909ac0)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff81032ebd)
Location: arch/x86/include/asm/paravirt.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81bbcf0a)
Location: arch/x86/include/asm/paravirt.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbde37)
Location: arch/x86/include/asm/paravirt.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/mm/fault.c (ffffffff81bbf5e0)
Location: arch/x86/include/asm/paravirt.h:123
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff82ce6472)
Location: arch/x86/include/asm/paravirt.h:123
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff81bba1f0)
Location: arch/x86/include/asm/paravirt.h:123
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
In arch/x86/kernel/process_64.c (ffffffff81bd30da)
Location: arch/x86/include/asm/paravirt.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81c3560a)
Location: arch/x86/include/asm/paravirt.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff81c3672b)
Location: arch/x86/include/asm/paravirt.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/mm/fault.c (ffffffff81c38470)
Location: arch/x86/include/asm/paravirt.h:123
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff82fd3de3)
Location: arch/x86/include/asm/paravirt.h:123
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff81bcea65)
Location: arch/x86/include/asm/paravirt.h:123
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
In arch/x86/kernel/process_64.c (ffffffff81bc54ca)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81c27a9a)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff81c28bbb)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/mm/fault.c (ffffffff81c2a860)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff831de924)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff81bc2415)
Location: arch/x86/include/asm/paravirt.h:136
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
In arch/x86/kernel/process_64.c (ffffffff81c980ea)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81d45afd)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff81d46d58)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/mm/fault.c (ffffffff81d48e50)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff832c1c9a)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff81c92a81)
Location: arch/x86/include/asm/paravirt.h:136
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
In arch/x86/kernel/process_64.c (ffffffff81e4758a)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81f13dbd)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff81f152a2)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/mm/fault.c (ffffffff81f181d0)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff834743b0)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff81e423cb)
Location: arch/x86/include/asm/paravirt.h:142
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
In arch/x86/kernel/process_64.c (ffffffff8104a1dd)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff820bb02d)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff820bc732)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/mm/fault.c (ffffffff820bf9c0)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff83e9c152)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff8201cd9b)
Location: arch/x86/include/asm/paravirt.h:142
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
In arch/x86/kernel/process_64.c (ffffffff8104aa1d)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8213c74d)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff8213dea1)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/mm/fault.c (ffffffff821416c0)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff836bfbf2)
Location: arch/x86/include/asm/paravirt.h:142
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff8209d42b)
Location: arch/x86/include/asm/paravirt.h:142
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
In arch/x86/kernel/process_64.c (ffffffff81051c8d)
Location: arch/x86/include/asm/paravirt.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8221e74d)
Location: arch/x86/include/asm/paravirt.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff8221fea0)
Location: arch/x86/include/asm/paravirt.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/mm/fault.c (ffffffff82223640)
Location: arch/x86/include/asm/paravirt.h:146
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff838f0712)
Location: arch/x86/include/asm/paravirt.h:146
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff82174c2b)
Location: arch/x86/include/asm/paravirt.h:146
Inline: True
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
In arch/x86/kernel/process_64.c (ffffffff810309f6)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/nmi.c (ffffffff810365cb)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828ae023)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff818a8e80)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff81020486)
Location: arch/x86/include/asm/special_insns.h:153
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/nmi.c (ffffffff81025f1b)
Location: arch/x86/include/asm/special_insns.h:153
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828a621c)
Location: arch/x86/include/asm/special_insns.h:153
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff8186361e)
Location: arch/x86/include/asm/special_insns.h:153
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff81030856)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/nmi.c (ffffffff8103642b)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828c0f22)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff818fa4e0)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff810316e6)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/nmi.c (ffffffff8103742b)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
```
```
In arch/x86/mm/extable.c (ffffffff828c406d)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:early_fixup_exception
```
```
In arch/x86/power/cpu.c (ffffffff8191b640)
Location: arch/x86/include/asm/paravirt.h:117
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
</ul>

## Differences
