# Function: <code>hw_breakpoint_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bd39)
Location: arch/x86/include/asm/debugreg.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105be39)
Location: arch/x86/include/asm/debugreg.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105edb9)
Location: arch/x86/include/asm/debugreg.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e459)
Location: arch/x86/include/asm/debugreg.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81062189)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81065289)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106aef9)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
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
In arch/x86/kernel/alternative.c (ffffffff81039a1c)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e9c9)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
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
In arch/x86/kernel/alternative.c (ffffffff8103a1ea)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ff79)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
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
In arch/x86/kernel/alternative.c (ffffffff8103ce5b)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077399)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
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
In arch/x86/kernel/alternative.c (ffffffff8103d33c)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810779c9)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
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
In arch/x86/kernel/alternative.c (ffffffff8103eb4c)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81078459)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
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
In arch/x86/kernel/alternative.c (ffffffff810448bc)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085cb9)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
void hw_breakpoint_disable();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8104c4e0)
Location: arch/x86/include/asm/debugreg.h:76
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810956f0)
Location: arch/x86/include/asm/debugreg.h:76
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
**Symbols:**

```
ffffffff8104c4e0-ffffffff8104c54b: hw_breakpoint_disable (STB_LOCAL)
ffffffff810956f0-ffffffff8109575b: hw_breakpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
void hw_breakpoint_disable();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81058630)
Location: arch/x86/include/asm/debugreg.h:98
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab2e0)
Location: arch/x86/include/asm/debugreg.h:98
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
**Symbols:**

```
ffffffff81058630-ffffffff8105869b: hw_breakpoint_disable (STB_LOCAL)
ffffffff810ab2e0-ffffffff810ab34b: hw_breakpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
void hw_breakpoint_disable();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810596c0)
Location: arch/x86/include/asm/debugreg.h:98
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810aeea0)
Location: arch/x86/include/asm/debugreg.h:98
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
**Symbols:**

```
ffffffff810596c0-ffffffff8105972b: hw_breakpoint_disable (STB_LOCAL)
ffffffff810aeea0-ffffffff810aef0b: hw_breakpoint_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
void hw_breakpoint_disable();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81060830)
Location: arch/x86/include/asm/debugreg.h:99
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5a20)
Location: arch/x86/include/asm/debugreg.h:99
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
**Symbols:**

```
ffffffff81060830-ffffffff8106089b: hw_breakpoint_disable (STB_LOCAL)
ffffffff810b5a20-ffffffff810b5a8b: hw_breakpoint_disable (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c000000000021560)
Location: arch/powerpc/include/asm/hw_breakpoint.h:66
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:do_break
```
```
In arch/powerpc/kernel/hw_breakpoint.c (c000000000038130)
Location: arch/powerpc/include/asm/hw_breakpoint.h:66
Inline: True
Inline callers:
  - arch/powerpc/kernel/hw_breakpoint.c:hw_breakpoint_handler
  - arch/powerpc/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
```
```
In arch/powerpc/kernel/machine_kexec_64.c (c0000000000711f0)
Location: arch/powerpc/include/asm/hw_breakpoint.h:66
Inline: True
Inline callers:
  - arch/powerpc/kernel/machine_kexec_64.c:kexec_prepare_cpus_wait
  - arch/powerpc/kernel/machine_kexec_64.c:kexec_smp_down
```
```
In arch/powerpc/xmon/xmon.c (c00000000010c0f4)
Location: arch/powerpc/include/asm/hw_breakpoint.h:66
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:clear_all_bpt
  - arch/powerpc/xmon/xmon.c:xmon_core
```
</details>
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
In arch/x86/kernel/alternative.c (ffffffff8103a34a)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ef19)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
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
In arch/x86/kernel/alternative.c (ffffffff81029aa2)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f330)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
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
In arch/x86/kernel/alternative.c (ffffffff8103a1aa)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f3c9)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
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
In arch/x86/kernel/alternative.c (ffffffff8103b1a8)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071649)
Location: arch/x86/include/asm/debugreg.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
