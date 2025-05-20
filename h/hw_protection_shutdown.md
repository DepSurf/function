# Function: <code>hw_protection_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hw_protection_shutdown(const char *reason, int ms_until_forced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81ca572d)
Location: kernel/reboot.c:581
Inline: False
Direct callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/thermal/thermal_core.c:thermal_zone_device_critical
```
**Symbols:**

```
ffffffff81ca572d-ffffffff81ca5792: hw_protection_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hw_protection_shutdown(const char *reason, int ms_until_forced);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81e54fd0)
Location: kernel/reboot.c:953
Inline: False
Direct callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/thermal/thermal_core.c:thermal_zone_device_critical
```
**Symbols:**

```
ffffffff81e54fd0-ffffffff81e5503e: hw_protection_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void hw_protection_shutdown(const char *reason, int ms_until_forced);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81127a40)
Location: kernel/reboot.c:970
Inline: True
Direct callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/thermal/thermal_core.c:thermal_zone_device_critical
```
**Symbols:**

```
ffffffff81127a40-ffffffff81127ad1: hw_protection_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void hw_protection_shutdown(const char *reason, int ms_until_forced);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81134ee0)
Location: kernel/reboot.c:970
Inline: True
Direct callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/thermal/thermal_core.c:thermal_zone_device_critical
```
**Symbols:**

```
ffffffff81134ee0-ffffffff81134f71: hw_protection_shutdown (STB_GLOBAL)
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
In drivers/regulator/core.c (ffffffff81ad4bf0)
Location: include/linux/reboot.h:187
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_notifier_call_chain
```
```
In drivers/regulator/irq_helpers.c (ffffffff81ae249e)
Location: include/linux/reboot.h:187
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
```
```
In drivers/thermal/thermal_core.c (ffffffff81dfd09d)
Location: include/linux/reboot.h:187
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_critical
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
