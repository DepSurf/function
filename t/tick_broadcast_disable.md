# Function: <code>tick_broadcast_disable</code>

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
In drivers/idle/intel_idle.c (ffffffff8147922e)
Location: include/linux/tick.h:83
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:__setup_broadcast_timer
```
```
In drivers/acpi/processor_idle.c (ffffffff814ac6e5)
Location: include/linux/tick.h:83
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff816bbeea)
Location: include/linux/tick.h:83
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (ffffffff814c763e)
Location: include/linux/tick.h:83
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:__setup_broadcast_timer
```
```
In drivers/acpi/processor_idle.c (ffffffff814fbb07)
Location: include/linux/tick.h:83
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff8171d7ba)
Location: include/linux/tick.h:83
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (0)
Location: include/linux/tick.h:83
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8151e7db)
Location: include/linux/tick.h:83
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff817503aa)
Location: include/linux/tick.h:83
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (0)
Location: include/linux/tick.h:83
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8152f9c1)
Location: include/linux/tick.h:83
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff8176ee6a)
Location: include/linux/tick.h:83
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (0)
Location: include/linux/tick.h:84
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81590651)
Location: include/linux/tick.h:84
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff817e486a)
Location: include/linux/tick.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (0)
Location: include/linux/tick.h:84
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815c7a21)
Location: include/linux/tick.h:84
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff8182d96a)
Location: include/linux/tick.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (0)
Location: include/linux/tick.h:84
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815e0fe1)
Location: include/linux/tick.h:84
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff81859aea)
Location: include/linux/tick.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (0)
Location: include/linux/tick.h:90
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81612b61)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff8189d42a)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (0)
Location: include/linux/tick.h:90
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81634061)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff818cf7da)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/acpi/processor_idle.c (ffffffff816e1251)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff819a1dda)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/acpi/processor_idle.c (ffffffff816fefb1)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff819a4daa)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/acpi/processor_idle.c (ffffffff816e0c11)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff819899ba)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/acpi/processor_idle.c (ffffffff81758f21)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff81a3418a)
Location: include/linux/tick.h:91
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/acpi/processor_idle.c (ffffffff8188c697)
Location: include/linux/tick.h:91
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff81ba0960)
Location: include/linux/tick.h:91
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
In drivers/acpi/processor_idle.c (ffffffff819d3f27)
Location: include/linux/tick.h:91
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff81d425e0)
Location: include/linux/tick.h:91
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
In drivers/acpi/processor_idle.c (ffffffff81a1b657)
Location: include/linux/tick.h:91
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff81dac7c0)
Location: include/linux/tick.h:91
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
In drivers/acpi/processor_idle.c (ffffffff81a66947)
Location: include/linux/tick.h:91
Inline: True
```
```
In drivers/cpuidle/driver.c (ffffffff81e64860)
Location: include/linux/tick.h:91
Inline: True
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
In drivers/cpuidle/driver.c (ffff800010b277a0)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/driver.c (c0c025b0)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/cpuidle/driver.c (c000000000c1eb80)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (0)
Location: include/linux/tick.h:90
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81603bb1)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff8187327a)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (0)
Location: include/linux/tick.h:90
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815eec61)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff8183d06a)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (0)
Location: include/linux/tick.h:90
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81628341)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff818c4c8a)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
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
In drivers/idle/intel_idle.c (0)
Location: include/linux/tick.h:90
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816421f1)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:__lapic_timer_propagate_broadcast
```
```
In drivers/cpuidle/driver.c (ffffffff818e102a)
Location: include/linux/tick.h:90
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:cpuidle_setup_broadcast_timer
```
</details>
</li>
</ul>

## Differences
