# Function: <code>paravirt_get_debugreg</code>

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
In arch/x86/kernel/process_64.c (ffffffff8102d337)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102f23a)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81037610)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
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
In arch/x86/kernel/process_64.c (ffffffff8102c319)
Location: arch/x86/include/asm/paravirt.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102e2cf)
Location: arch/x86/include/asm/paravirt.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103683a)
Location: arch/x86/include/asm/paravirt.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
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
In arch/x86/kernel/process_64.c (ffffffff8102c308)
Location: arch/x86/include/asm/paravirt.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102e21f)
Location: arch/x86/include/asm/paravirt.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103655a)
Location: arch/x86/include/asm/paravirt.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
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
In arch/x86/kernel/process_64.c (ffffffff8102a4f8)
Location: arch/x86/include/asm/paravirt.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102c32f)
Location: arch/x86/include/asm/paravirt.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103456a)
Location: arch/x86/include/asm/paravirt.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
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
In arch/x86/kernel/process_64.c (ffffffff8102b259)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102d22f)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff810368ca)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
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
In arch/x86/kernel/process_64.c (ffffffff8102cfca)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102e1df)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81037913)
Location: arch/x86/include/asm/paravirt.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
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
In arch/x86/kernel/process_64.c (ffffffff8102e21e)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102f49f)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81038b33)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
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
In arch/x86/kernel/process_64.c (ffffffff8102ffae)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8103129f)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b0bd)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
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
In arch/x86/kernel/process_64.c (ffffffff8103090e)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81031b5f)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b88d)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int paravirt_get_debugreg(int reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032d96)
Location: arch/x86/include/asm/paravirt.h:103
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81bbd820)
Location: arch/x86/include/asm/paravirt.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbde68)
Location: arch/x86/include/asm/paravirt.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbeb23)
Location: arch/x86/include/asm/paravirt.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
**Symbols:**

```
ffffffff81032d96-ffffffff81032da6: paravirt_get_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int paravirt_get_debugreg(int reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81bd2f9f)
Location: arch/x86/include/asm/paravirt.h:103
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81c35ec9)
Location: arch/x86/include/asm/paravirt.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81c36761)
Location: arch/x86/include/asm/paravirt.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c37323)
Location: arch/x86/include/asm/paravirt.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
**Symbols:**

```
ffffffff81bd2f9f-ffffffff81bd2faf: paravirt_get_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int paravirt_get_debugreg(int reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81bc538f)
Location: arch/x86/include/asm/paravirt.h:116
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81c28349)
Location: arch/x86/include/asm/paravirt.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81c28bf1)
Location: arch/x86/include/asm/paravirt.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c29a83)
Location: arch/x86/include/asm/paravirt.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
**Symbols:**

```
ffffffff81bc538f-ffffffff81bc539f: paravirt_get_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int paravirt_get_debugreg(int reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81c97faf)
Location: arch/x86/include/asm/paravirt.h:116
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81d464b9)
Location: arch/x86/include/asm/paravirt.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81d46d8e)
Location: arch/x86/include/asm/paravirt.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47ff3)
Location: arch/x86/include/asm/paravirt.h:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
**Symbols:**

```
ffffffff81c97faf-ffffffff81c97fbf: paravirt_get_debugreg (STB_LOCAL)
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
In arch/x86/kernel/process_64.c (ffffffff81e47601)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81f14789)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81f152d0)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f16aed)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
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
In arch/x86/kernel/process_64.c (ffffffff8104a255)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff820bbb09)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff820bc761)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820be0cd)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
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
In arch/x86/kernel/process_64.c (ffffffff8104aa95)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8213d239)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff8213def9)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213fb6d)
Location: arch/x86/include/asm/paravirt.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
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
In arch/x86/kernel/process_64.c (ffffffff81051d05)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8221f259)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff8221fef6)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82221b8d)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
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
In arch/x86/kernel/process_64.c (ffffffff81030a6e)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81031cbf)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b9ed)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
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
In arch/x86/kernel/process_64.c (ffffffff810308ce)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81031b1f)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b84d)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
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
In arch/x86/kernel/process_64.c (ffffffff8103175e)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff810329e6)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103c84d)
Location: arch/x86/include/asm/paravirt.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
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
</ul>
