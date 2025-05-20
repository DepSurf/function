# Function: <code>__mwait</code>

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
In arch/x86/kernel/acpi/cstate.c (ffffffff81050126)
Location: arch/x86/include/asm/mwait.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105284a)
Location: arch/x86/include/asm/mwait.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff81479483)
Location: arch/x86/include/asm/mwait.h:39
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81050282)
Location: arch/x86/include/asm/mwait.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105299e)
Location: arch/x86/include/asm/mwait.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff814c792c)
Location: arch/x86/include/asm/mwait.h:39
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
In arch/x86/kernel/acpi/cstate.c (ffffffff818d3d12)
Location: arch/x86/include/asm/mwait.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff810552a7)
Location: arch/x86/include/asm/mwait.h:39
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff814e984d)
Location: arch/x86/include/asm/mwait.h:39
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
In arch/x86/kernel/acpi/cstate.c (ffffffff8190ae72)
Location: arch/x86/include/asm/mwait.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054bad)
Location: arch/x86/include/asm/mwait.h:40
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff814f546d)
Location: arch/x86/include/asm/mwait.h:40
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
In arch/x86/kernel/acpi/cstate.c (ffffffff819951e2)
Location: arch/x86/include/asm/mwait.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81058979)
Location: arch/x86/include/asm/mwait.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff81535ced)
Location: arch/x86/include/asm/mwait.h:41
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
In arch/x86/kernel/acpi/cstate.c (ffffffff819f1742)
Location: arch/x86/include/asm/mwait.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b5ea)
Location: arch/x86/include/asm/mwait.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff8156b88c)
Location: arch/x86/include/asm/mwait.h:41
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2cbe2)
Location: arch/x86/include/asm/mwait.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81061274)
Location: arch/x86/include/asm/mwait.h:41
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff8158340c)
Location: arch/x86/include/asm/mwait.h:41
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd42)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106492c)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b4d)
Location: arch/x86/include/asm/mwait.h:42
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad4592)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064fac)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff815d4d8d)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81068ab4)
Location: arch/x86/include/asm/mwait.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b6d5)
Location: arch/x86/include/asm/mwait.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff8167e8d4)
Location: arch/x86/include/asm/mwait.h:44
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
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a754)
Location: arch/x86/include/asm/mwait.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d375)
Location: arch/x86/include/asm/mwait.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff8169d5d4)
Location: arch/x86/include/asm/mwait.h:44
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
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b21b)
Location: arch/x86/include/asm/mwait.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106dde5)
Location: arch/x86/include/asm/mwait.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff8168035b)
Location: arch/x86/include/asm/mwait.h:44
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d3b)
Location: arch/x86/include/asm/mwait.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff810795f5)
Location: arch/x86/include/asm/mwait.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff816f50cb)
Location: arch/x86/include/asm/mwait.h:44
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81084784)
Location: arch/x86/include/asm/mwait.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff81088485)
Location: arch/x86/include/asm/mwait.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff818219f4)
Location: arch/x86/include/asm/mwait.h:44
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81097a14)
Location: arch/x86/include/asm/mwait.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bf45)
Location: arch/x86/include/asm/mwait.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff819526e4)
Location: arch/x86/include/asm/mwait.h:45
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
In arch/x86/kernel/acpi/cstate.c (ffffffff821430f7)
Location: arch/x86/include/asm/mwait.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109be11)
Location: arch/x86/include/asm/mwait.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff8214362c)
Location: arch/x86/include/asm/mwait.h:45
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
In arch/x86/kernel/acpi/cstate.c (ffffffff822257e2)
Location: arch/x86/include/asm/mwait.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a3411)
Location: arch/x86/include/asm/mwait.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff82225d3c)
Location: arch/x86/include/asm/mwait.h:45
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a73402)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064a9c)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff815c8add)
Location: arch/x86/include/asm/mwait.h:42
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f7b2)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054d71)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b4d)
Location: arch/x86/include/asm/mwait.h:42
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf812)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064f4c)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff815c906d)
Location: arch/x86/include/asm/mwait.h:42
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81aebfe2)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106652c)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In drivers/idle/intel_idle.c (ffffffff815e2ecd)
Location: arch/x86/include/asm/mwait.h:42
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
</details>
</li>
</ul>

## Differences
