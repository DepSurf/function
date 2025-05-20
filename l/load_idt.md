# Function: <code>load_idt</code>

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
In arch/x86/kernel/head64.c (ffffffff81f59448)
Location: arch/x86/include/asm/paravirt.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff81f65731)
Location: arch/x86/include/asm/paravirt.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:early_trap_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040346)
Location: arch/x86/include/asm/paravirt.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff81050618)
Location: arch/x86/include/asm/paravirt.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/tracepoint.c (ffffffff810663d6)
Location: arch/x86/include/asm/paravirt.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
  - arch/x86/kernel/tracepoint.c:switch_idt
  - arch/x86/kernel/tracepoint.c:switch_idt
```
```
In arch/x86/power/cpu.c (ffffffff816fb0f4)
Location: arch/x86/include/asm/paravirt.h:233
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/head64.c (ffffffff81f813e1)
Location: arch/x86/include/asm/paravirt.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff81f8d5a0)
Location: arch/x86/include/asm/paravirt.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:early_trap_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041085)
Location: arch/x86/include/asm/paravirt.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/reboot.c (ffffffff810507c4)
Location: arch/x86/include/asm/paravirt.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/tracepoint.c (ffffffff81066166)
Location: arch/x86/include/asm/paravirt.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
  - arch/x86/kernel/tracepoint.c:switch_idt
  - arch/x86/kernel/tracepoint.c:switch_idt
```
```
In arch/x86/power/cpu.c (ffffffff81760354)
Location: arch/x86/include/asm/paravirt.h:232
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/head64.c (ffffffff81fbd3e1)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff81fc89b4)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:early_trap_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040ad2)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/reboot.c (ffffffff81053034)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/tracepoint.c (ffffffff81069686)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
  - arch/x86/kernel/tracepoint.c:switch_idt
  - arch/x86/kernel/tracepoint.c:switch_idt
```
```
In arch/x86/power/cpu.c (ffffffff8178d354)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/head64.c (ffffffff8209d3cd)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/traps.c (ffffffff820a90a5)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:early_trap_init
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ea63)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/reboot.c (ffffffff81052b3a)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/tracepoint.c (ffffffff81068900)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/tracepoint.c:switch_idt
  - arch/x86/kernel/tracepoint.c:switch_idt
  - arch/x86/kernel/tracepoint.c:switch_idt
```
```
In arch/x86/power/cpu.c (ffffffff817ab4d1)
Location: arch/x86/include/asm/paravirt.h:223
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/idt.c (ffffffff8102e092)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041742)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_reset
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057756)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/power/cpu.c (ffffffff818229d1)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/idt.c (ffffffff8102f112)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043012)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105a636)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/power/cpu.c (ffffffff8186cbf1)
Location: arch/x86/include/asm/paravirt.h:219
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/idt.c (ffffffff810303a2)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104467a)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff810602b6)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/power/cpu.c (ffffffff8188cc01)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/idt.c (ffffffff81032182)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046c28)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063bbd)
Location: arch/x86/include/asm/paravirt.h:267
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/power/cpu.c (ffffffff818d76e3)
Location: arch/x86/include/asm/paravirt.h:267
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
In arch/x86/kernel/idt.c (ffffffff81032a42)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810473a8)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106426d)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/power/cpu.c (ffffffff81909743)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81034832)
Location: arch/x86/include/asm/paravirt.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:load_current_idt
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/power/cpu.c (ffffffff81bba2f5)
Location: arch/x86/include/asm/paravirt.h:261
Inline: True
```
**Symbols:**

```
ffffffff810347e0-ffffffff810347ed: load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81035042)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:load_current_idt
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/power/cpu.c (ffffffff81bceb65)
Location: arch/x86/include/asm/paravirt.h:259
Inline: True
```
**Symbols:**

```
ffffffff81034ff0-ffffffff81034ffd: load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81036a82)
Location: arch/x86/include/asm/paravirt.h:276
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:load_current_idt
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/power/cpu.c (ffffffff81bc2515)
Location: arch/x86/include/asm/paravirt.h:276
Inline: True
```
**Symbols:**

```
ffffffff81036a30-ffffffff81036a3d: load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8103bd65)
Location: arch/x86/include/asm/paravirt.h:276
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:load_current_idt
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/power/cpu.c (ffffffff81c92ba3)
Location: arch/x86/include/asm/paravirt.h:276
Inline: True
```
**Symbols:**

```
ffffffff8103bd30-ffffffff8103bd3d: load_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void load_idt(const struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81042df5)
Location: arch/x86/include/asm/paravirt.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:load_current_idt
Direct callers:
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/power/cpu.c (ffffffff81e4250e)
Location: arch/x86/include/asm/paravirt.h:282
Inline: True
```
**Symbols:**

```
ffffffff81042d80-ffffffff81042da6: load_idt (STB_LOCAL)
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
In arch/x86/kernel/idt.c (ffffffff8104c855)
Location: arch/x86/include/asm/paravirt.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_traps
  - arch/x86/kernel/idt.c:load_current_idt
```
```
In arch/x86/power/cpu.c (ffffffff8201ceee)
Location: arch/x86/include/asm/paravirt.h:282
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
In arch/x86/kernel/idt.c (ffffffff8104d0c5)
Location: arch/x86/include/asm/paravirt.h:284
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_traps
  - arch/x86/kernel/idt.c:load_current_idt
```
```
In arch/x86/power/cpu.c (ffffffff8209d57e)
Location: arch/x86/include/asm/paravirt.h:284
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
In arch/x86/kernel/idt.c (ffffffff81054345)
Location: arch/x86/include/asm/paravirt.h:286
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/idt.c:idt_setup_early_traps
  - arch/x86/kernel/idt.c:load_current_idt
```
```
In arch/x86/power/cpu.c (ffffffff82174d7e)
Location: arch/x86/include/asm/paravirt.h:286
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
In arch/x86/kernel/idt.c (ffffffff81032ba2)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047528)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063d5d)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/power/cpu.c (ffffffff818a8b03)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032a02)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047368)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106420d)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/power/cpu.c (ffffffff818fa163)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
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
In arch/x86/kernel/idt.c (ffffffff81033962)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/idt.c:idt_invalidate
  - arch/x86/kernel/idt.c:idt_setup_early_handler
  - arch/x86/kernel/idt.c:idt_setup_early_traps
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048768)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
  - arch/x86/kernel/cpu/common.c:debug_stack_set_zero
```
```
In arch/x86/kernel/smpboot.c (ffffffff810657cd)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/power/cpu.c (ffffffff8191b2c3)
Location: arch/x86/include/asm/paravirt.h:255
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
