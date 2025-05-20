# Function: <code>tick_broadcast_enter</code>

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
In arch/x86/kernel/process.c (ffffffff81038f04)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:amd_e400_idle
```
```
In drivers/idle/intel_idle.c (ffffffff814794d3)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff814ace7a)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/cpuidle/cpuidle.c (ffffffff816bb923)
Location: include/linux/tick.h:91
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
In arch/x86/kernel/process.c (ffffffff81037f5a)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:amd_e400_idle
```
```
In drivers/idle/intel_idle.c (ffffffff814c78b2)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff814fca74)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8171d1e3)
Location: include/linux/tick.h:91
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
In arch/x86/kernel/process.c (ffffffff81037be4)
Location: include/linux/tick.h:91
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff818d3fb5)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff8151f6f0)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8174fdc3)
Location: include/linux/tick.h:91
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
In arch/x86/kernel/process.c (ffffffff81035cd4)
Location: include/linux/tick.h:91
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff8190b135)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff81530a91)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8176e871)
Location: include/linux/tick.h:91
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
In arch/x86/kernel/process.c (ffffffff81037ff7)
Location: include/linux/tick.h:92
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff819954ab)
Location: include/linux/tick.h:92
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff81591ab8)
Location: include/linux/tick.h:92
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff817e42f4)
Location: include/linux/tick.h:92
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
In arch/x86/kernel/process.c (ffffffff81039117)
Location: include/linux/tick.h:92
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff819f19ed)
Location: include/linux/tick.h:92
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff815c8e2d)
Location: include/linux/tick.h:92
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8182d491)
Location: include/linux/tick.h:92
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
In arch/x86/kernel/process.c (ffffffff8103a377)
Location: include/linux/tick.h:92
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81a2cefd)
Location: include/linux/tick.h:92
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff815e23fd)
Location: include/linux/tick.h:92
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818594ef)
Location: include/linux/tick.h:92
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
In arch/x86/kernel/process.c (ffffffff8103c937)
Location: include/linux/tick.h:98
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81a9d067)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff81613ec8)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189cd79)
Location: include/linux/tick.h:98
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
In arch/x86/kernel/process.c (ffffffff8103d0f7)
Location: include/linux/tick.h:98
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81ad48b7)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff816353ad)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cf157)
Location: include/linux/tick.h:98
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
In arch/x86/kernel/process.c (ffffffff8103ff97)
Location: include/linux/tick.h:98
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81bcc8aa)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff816e216c)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a1963)
Location: include/linux/tick.h:98
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
In arch/x86/kernel/process.c (ffffffff8103fed7)
Location: include/linux/tick.h:98
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff819a49fd)
Location: include/linux/tick.h:98
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
In arch/x86/kernel/process.c (ffffffff810418b4)
Location: include/linux/tick.h:99
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81989620)
Location: include/linux/tick.h:99
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
In arch/x86/kernel/process.c (ffffffff81047b54)
Location: include/linux/tick.h:99
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81a33b3c)
Location: include/linux/tick.h:99
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
In arch/x86/kernel/process.c (ffffffff81050b25)
Location: include/linux/tick.h:99
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81ba029c)
Location: include/linux/tick.h:99
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
In arch/x86/kernel/process.c (ffffffff8105e015)
Location: include/linux/tick.h:99
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81d41e4a)
Location: include/linux/tick.h:99
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
In arch/x86/kernel/process.c (ffffffff8105f6d7)
Location: include/linux/tick.h:99
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff821425bb)
Location: include/linux/tick.h:99
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
In arch/x86/kernel/process.c (ffffffff81066784)
Location: include/linux/tick.h:99
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (ffffffff82224cab)
Location: include/linux/tick.h:99
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
In drivers/cpuidle/cpuidle.c (ffff800010b26eb8)
Location: include/linux/tick.h:98
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
In arch/arm/mach-omap2/cpuidle44xx.c (c033ee34)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled
```
```
In drivers/cpuidle/cpuidle.c (c0c01b28)
Location: include/linux/tick.h:98
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
In drivers/cpuidle/cpuidle.c (c000000000c1e040)
Location: include/linux/tick.h:98
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
In arch/x86/kernel/process.c (ffffffff8103d277)
Location: include/linux/tick.h:98
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81a73727)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff81604b9d)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81872c02)
Location: include/linux/tick.h:98
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
In arch/x86/kernel/process.c (ffffffff8102c927)
Location: include/linux/tick.h:98
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81a2fab7)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff815efd0d)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183c9ec)
Location: include/linux/tick.h:98
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
In arch/x86/kernel/process.c (ffffffff8103d0b7)
Location: include/linux/tick.h:98
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81adfb37)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff8162968d)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c4607)
Location: include/linux/tick.h:98
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
In arch/x86/kernel/process.c (ffffffff8103e147)
Location: include/linux/tick.h:98
Inline: True
```
```
In drivers/idle/intel_idle.c (ffffffff81aec337)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/processor_idle.c (ffffffff8164352d)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e0987)
Location: include/linux/tick.h:98
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
</details>
</li>
</ul>

## Differences
