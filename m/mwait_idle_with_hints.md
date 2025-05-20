# Function: <code>mwait_idle_with_hints</code>

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
In arch/x86/kernel/acpi/cstate.c (ffffffff810500cf)
Location: arch/x86/include/asm/mwait.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff8147942c)
Location: arch/x86/include/asm/mwait.h:98
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle_freeze
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
In arch/x86/kernel/acpi/cstate.c (ffffffff8105023f)
Location: arch/x86/include/asm/mwait.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff814c78e9)
Location: arch/x86/include/asm/mwait.h:98
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff818d3cde)
Location: arch/x86/include/asm/mwait.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff814e9819)
Location: arch/x86/include/asm/mwait.h:98
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff8190ae3e)
Location: arch/x86/include/asm/mwait.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff814f5439)
Location: arch/x86/include/asm/mwait.h:99
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff819951ae)
Location: arch/x86/include/asm/mwait.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff81535cb9)
Location: arch/x86/include/asm/mwait.h:100
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff819f170e)
Location: arch/x86/include/asm/mwait.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff8156b858)
Location: arch/x86/include/asm/mwait.h:100
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2cbae)
Location: arch/x86/include/asm/mwait.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff815833d8)
Location: arch/x86/include/asm/mwait.h:100
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd0e)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b19)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad455e)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff815d4d59)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068a80)
Location: arch/x86/include/asm/mwait.h:109
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff8167e8a0)
Location: arch/x86/include/asm/mwait.h:109
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
**Symbols:**

```
ffffffff81068a80-ffffffff81068b0a: mwait_idle_with_hints (STB_LOCAL)
ffffffff8167e8a0-ffffffff8167e92c: mwait_idle_with_hints.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a720)
Location: arch/x86/include/asm/mwait.h:107
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff8169d5a0)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
**Symbols:**

```
ffffffff8106a720-ffffffff8106a7aa: mwait_idle_with_hints (STB_LOCAL)
ffffffff8169d5a0-ffffffff8169d62c: mwait_idle_with_hints.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b1e0)
Location: arch/x86/include/asm/mwait.h:107
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff81680320)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
**Symbols:**

```
ffffffff8106b1e0-ffffffff8106b272: mwait_idle_with_hints (STB_LOCAL)
ffffffff81680320-ffffffff816803b4: mwait_idle_with_hints.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d00)
Location: arch/x86/include/asm/mwait.h:107
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff816f5090)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
**Symbols:**

```
ffffffff81075d00-ffffffff81075d8c: mwait_idle_with_hints (STB_LOCAL)
ffffffff816f5090-ffffffff816f5121: mwait_idle_with_hints.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff81084750)
Location: arch/x86/include/asm/mwait.h:107
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff818219c0)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
**Symbols:**

```
ffffffff81084750-ffffffff810847e6: mwait_idle_with_hints (STB_LOCAL)
ffffffff818219c0-ffffffff81821a56: mwait_idle_with_hints.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mwait_idle_with_hints(long unsigned int eax, long unsigned int ecx);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff810979e0)
Location: arch/x86/include/asm/mwait.h:108
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff819526b0)
Location: arch/x86/include/asm/mwait.h:108
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
**Symbols:**

```
ffffffff810979e0-ffffffff81097a75: mwait_idle_with_hints (STB_LOCAL)
ffffffff819526b0-ffffffff81952745: mwait_idle_with_hints.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/acpi/cstate.c (ffffffff821430c3)
Location: arch/x86/include/asm/mwait.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff821435f8)
Location: arch/x86/include/asm/mwait.h:108
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff822257a8)
Location: arch/x86/include/asm/mwait.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff82225d08)
Location: arch/x86/include/asm/mwait.h:117
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a733ce)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff815c8aa9)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f77e)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b19)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf7de)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff815c9039)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81aebfae)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In drivers/idle/intel_idle.c (ffffffff815e2e99)
Location: arch/x86/include/asm/mwait.h:107
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
