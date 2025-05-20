# Function: <code>set_debugreg</code>

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
In arch/x86/kernel/traps.c (ffffffff8102f265)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81037016)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104131b)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bd39)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff81060d74)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
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
In arch/x86/kernel/traps.c (ffffffff8102e2df)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81036851)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104123e)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105be39)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff81060c96)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff8102e22f)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81036571)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040c8b)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105edb9)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff81063d36)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff8102c33f)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81034581)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ec36)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e459)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff81062ca6)
Location: arch/x86/include/asm/paravirt.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff8102d23f)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff810368e1)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810418bd)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81062189)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff81066e36)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff8102e1f5)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81037921)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043195)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81065289)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff81069a3f)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff8102f4b5)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81038b41)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810447fd)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106aef9)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff8106f7c8)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff810312b5)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/alternative.c (ffffffff81039a1c)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b0d1)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046dd4)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e9c9)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff810738b6)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff81031b75)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a1ea)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b8a1)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047554)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ff79)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff81074876)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff81bbd840)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbdf69)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8103ce5b)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103e140)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b30c)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbeb68)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077399)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107bde8)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff81c35ed9)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81c3680f)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8103d33c)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103e200)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a9de)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c37368)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810779c9)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107bcd8)
Location: arch/x86/include/asm/paravirt.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff81c28359)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81c28c9f)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8103eb4c)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103fb50)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c2a8)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c29ac8)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81078459)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff8107ce88)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff81d464c9)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81d46e39)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff810448bc)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81045a20)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81053512)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d48038)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085cb9)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff8108b3be)
Location: arch/x86/include/asm/paravirt.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff81f14798)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff81f152e4)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff8104c4e0)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8104e1d0)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105ef94)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f16b53)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810956f0)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
```
```
In arch/x86/kernel/kgdb.c (ffffffff8109b65e)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff820bbb18)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff820bc775)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff81058630)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105b090)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d6f4)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820be133)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab2e0)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b227e)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff8213d248)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff8213df0d)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff810596c0)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105c5d0)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106f05a)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213fbd3)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810aeea0)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
```
```
In arch/x86/kernel/kgdb.c (ffffffff810b538e)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff8221f268)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_debug
```
```
In arch/x86/kernel/nmi.c (ffffffff8221ff0a)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/alternative.c (ffffffff81060830)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
  - arch/x86/kernel/alternative.c:hw_breakpoint_disable
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81063690)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810763cd)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82221bf3)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5a20)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
  - arch/x86/kernel/machine_kexec_64.c:hw_breakpoint_disable
```
```
In arch/x86/kernel/kgdb.c (ffffffff810bc7ce)
Location: arch/x86/include/asm/paravirt.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff81031cd5)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a34a)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103ba01)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810476d4)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ef19)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073876)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff81031b35)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/alternative.c (ffffffff8103a1aa)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b861)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047514)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f3c9)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff81073826)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
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
In arch/x86/kernel/traps.c (ffffffff810329fc)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
```
```
In arch/x86/kernel/alternative.c (ffffffff8103b1a8)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103c861)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_exceptions_notify
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_restore
  - arch/x86/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048914)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071649)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
```
In arch/x86/kernel/kgdb.c (ffffffff81075886)
Location: arch/x86/include/asm/paravirt.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
</details>
</li>
</ul>

## Differences
