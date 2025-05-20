# Function: <code>acpi_sci_irq_valid</code>

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
In drivers/acpi/osl.c (ffffffff8147a03a)
Location: include/linux/acpi.h:211
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
```
In drivers/acpi/sleep.c (ffffffff8147b78b)
Location: include/linux/acpi.h:211
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_prepare
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
In drivers/acpi/osl.c (ffffffff814c890e)
Location: include/linux/acpi.h:289
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
```
In drivers/acpi/sleep.c (ffffffff814c9df6)
Location: include/linux/acpi.h:289
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_prepare
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
In drivers/acpi/osl.c (ffffffff814ea852)
Location: include/linux/acpi.h:314
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
```
In drivers/acpi/sleep.c (ffffffff814ebd51)
Location: include/linux/acpi.h:314
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_prepare
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
In drivers/acpi/osl.c (ffffffff814f66b5)
Location: include/linux/acpi.h:313
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
```
In drivers/acpi/sleep.c (ffffffff814f84f5)
Location: include/linux/acpi.h:313
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_restore
  - drivers/acpi/sleep.c:acpi_freeze_wake
  - drivers/acpi/sleep.c:acpi_freeze_prepare
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
In drivers/acpi/osl.c (ffffffff81537475)
Location: include/linux/acpi.h:309
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
```
In drivers/acpi/sleep.c (ffffffff815398e5)
Location: include/linux/acpi.h:309
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_wake
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff8156cfe5)
Location: include/linux/acpi.h:311
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
```
```
In drivers/acpi/sleep.c (ffffffff8156f545)
Location: include/linux/acpi.h:311
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_restore
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff81583ca5)
Location: include/linux/acpi.h:311
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
```
```
In drivers/acpi/sleep.c (ffffffff81587129)
Location: include/linux/acpi.h:311
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff815b4885)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
```
```
In drivers/acpi/sleep.c (ffffffff815b7d89)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff815d5b05)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
```
```
In drivers/acpi/sleep.c (ffffffff815d8d15)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff81680d63)
Location: include/linux/acpi.h:318
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
```
In drivers/acpi/wakeup.c (ffffffff816829f5)
Location: include/linux/acpi.h:318
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff81682ed5)
Location: include/linux/acpi.h:318
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff8169f853)
Location: include/linux/acpi.h:322
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
```
In drivers/acpi/wakeup.c (ffffffff816a1055)
Location: include/linux/acpi.h:322
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff816a1345)
Location: include/linux/acpi.h:322
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff816824f3)
Location: include/linux/acpi.h:322
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
```
In drivers/acpi/wakeup.c (ffffffff81683e45)
Location: include/linux/acpi.h:322
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff81684135)
Location: include/linux/acpi.h:322
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff816f7663)
Location: include/linux/acpi.h:326
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_hotplug_work_fn
```
```
In drivers/acpi/wakeup.c (ffffffff816f8ff5)
Location: include/linux/acpi.h:326
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff816f9315)
Location: include/linux/acpi.h:326
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff818245f3)
Location: include/linux/acpi.h:346
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
```
In drivers/acpi/wakeup.c (ffffffff818261b5)
Location: include/linux/acpi.h:346
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_register_wakeup_handler
```
```
In drivers/acpi/sleep.c (ffffffff818265c5)
Location: include/linux/acpi.h:346
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff81955a93)
Location: include/linux/acpi.h:350
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
```
In drivers/acpi/wakeup.c (ffffffff81957b65)
Location: include/linux/acpi.h:350
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_register_wakeup_handler
```
```
In drivers/acpi/sleep.c (ffffffff81957ff5)
Location: include/linux/acpi.h:350
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff8199be93)
Location: include/linux/acpi.h:339
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
```
In drivers/acpi/wakeup.c (ffffffff8199e025)
Location: include/linux/acpi.h:339
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_register_wakeup_handler
```
```
In drivers/acpi/sleep.c (ffffffff8199e4b5)
Location: include/linux/acpi.h:339
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff819e43e3)
Location: include/linux/acpi.h:325
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
```
```
In drivers/acpi/wakeup.c (ffffffff819e6695)
Location: include/linux/acpi.h:325
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_register_wakeup_handler
```
```
In drivers/acpi/sleep.c (ffffffff819e6b55)
Location: include/linux/acpi.h:325
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffff800010763144)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815c9865)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
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
In drivers/acpi/osl.c (ffffffff815b28f5)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
```
```
In drivers/acpi/sleep.c (ffffffff815b5095)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff815c9de5)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
```
```
In drivers/acpi/sleep.c (ffffffff815ccff5)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
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
In drivers/acpi/osl.c (ffffffff815e3c45)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_events_complete
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
```
```
In drivers/acpi/sleep.c (ffffffff815e6e95)
Location: include/linux/acpi.h:303
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_prepare
```
</details>
</li>
</ul>

## Differences
