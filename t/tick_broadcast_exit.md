# Function: <code>tick_broadcast_exit</code>

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
In arch/x86/kernel/process.c (ffffffff81038f1a)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:amd_e400_idle
```
```
In drivers/idle/intel_idle.c (ffffffff814794c0)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff814acf1f)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/cpuidle/cpuidle.c (ffffffff816bbb27)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81037f70)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:amd_e400_idle
```
```
In drivers/idle/intel_idle.c (ffffffff814c787d)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff814fca9a)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8171d3f0)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81037bfa)
Location: include/linux/tick.h:95
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff818d3f87)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff8151f716)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8174ffd0)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81035cea)
Location: include/linux/tick.h:95
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff8190b107)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff81530b1f)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176eaae)
Location: include/linux/tick.h:95
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8103800d)
Location: include/linux/tick.h:96
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff819954c5)
Location: include/linux/tick.h:96
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff81591b18)
Location: include/linux/tick.h:96
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817e4390)
Location: include/linux/tick.h:96
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8103912d)
Location: include/linux/tick.h:96
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff819f1a05)
Location: include/linux/tick.h:96
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff815c8ebc)
Location: include/linux/tick.h:96
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d41b)
Location: include/linux/tick.h:96
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8103a38d)
Location: include/linux/tick.h:96
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81a2cf15)
Location: include/linux/tick.h:96
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff815e248c)
Location: include/linux/tick.h:96
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818593ff)
Location: include/linux/tick.h:96
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8103c94d)
Location: include/linux/tick.h:102
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81a9d081)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff81613f55)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189cd47)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8103d10d)
Location: include/linux/tick.h:102
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81ad48d1)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff81635435)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cf067)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8103ffad)
Location: include/linux/tick.h:102
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81bcc885)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff816e21be)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a1a23)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8103feef)
Location: include/linux/tick.h:102
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a49d6)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff810418cc)
Location: include/linux/tick.h:103
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819895f9)
Location: include/linux/tick.h:103
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81047b6c)
Location: include/linux/tick.h:103
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81a33b0f)
Location: include/linux/tick.h:103
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81050b3f)
Location: include/linux/tick.h:103
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81ba00dd)
Location: include/linux/tick.h:103
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8105e02f)
Location: include/linux/tick.h:103
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d41d02)
Location: include/linux/tick.h:103
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8105f6e6)
Location: include/linux/tick.h:103
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff821425f5)
Location: include/linux/tick.h:103
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81066793)
Location: include/linux/tick.h:103
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff82224ce5)
Location: include/linux/tick.h:103
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffff800010b270c4)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mach-omap2/cpuidle44xx.c (c033eebc)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled
```
```
In drivers/cpuidle/cpuidle.c (c0c01c50)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (c000000000c1df0c)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8103d28d)
Location: include/linux/tick.h:102
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81a73741)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff81604c25)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81872b27)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8102c937)
Location: include/linux/tick.h:102
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81a2fad1)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff815efd93)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183c902)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8103d0cd)
Location: include/linux/tick.h:102
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81adfb51)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff81629715)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c4517)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff8103e15d)
Location: include/linux/tick.h:102
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81aec351)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff816435b5)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e0897)
Location: include/linux/tick.h:102
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
</details>
</li>
</ul>

## Differences
