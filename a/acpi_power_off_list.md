# Function: <code>acpi_power_off_list</code>

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
In drivers/acpi/power.c (ffffffff81489022)
Location: drivers/acpi/power.c:312
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
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
In drivers/acpi/power.c (ffffffff814d7e29)
Location: drivers/acpi/power.c:312
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
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
In drivers/acpi/power.c (ffffffff814fa511)
Location: drivers/acpi/power.c:312
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
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
In drivers/acpi/power.c (ffffffff815097bc)
Location: drivers/acpi/power.c:313
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
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
In drivers/acpi/power.c (ffffffff8154bdf7)
Location: drivers/acpi/power.c:313
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
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
In drivers/acpi/power.c (ffffffff8158242f)
Location: drivers/acpi/power.c:313
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
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
In drivers/acpi/power.c (ffffffff8159a4ef)
Location: drivers/acpi/power.c:335
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815cbc4a)
Location: drivers/acpi/power.c:456
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815ececa)
Location: drivers/acpi/power.c:456
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81698ac7)
Location: drivers/acpi/power.c:454
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff816b5bfa)
Location: drivers/acpi/power.c:454
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81697bc5)
Location: drivers/acpi/power.c:445
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8170d972)
Location: drivers/acpi/power.c:469
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff8183b770)
Location: drivers/acpi/power.c:469
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff8183b770-ffffffff8183b801: acpi_power_off_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff81970f30)
Location: drivers/acpi/power.c:469
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff81970f30-ffffffff81970fc1: acpi_power_off_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff819b75c0)
Location: drivers/acpi/power.c:470
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff819b75c0-ffffffff819b7651: acpi_power_off_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff81a01b70)
Location: drivers/acpi/power.c:470
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff81a01b70-ffffffff81a01c01: acpi_power_off_list.isra.0 (STB_LOCAL)
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
In drivers/acpi/power.c (ffff8000107785c8)
Location: drivers/acpi/power.c:456
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
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
In drivers/acpi/power.c (ffffffff815dbff9)
Location: drivers/acpi/power.c:456
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815c7639)
Location: drivers/acpi/power.c:456
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815e11aa)
Location: drivers/acpi/power.c:456
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815fb06a)
Location: drivers/acpi/power.c:456
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
```
</details>
</li>
</ul>

## Differences
