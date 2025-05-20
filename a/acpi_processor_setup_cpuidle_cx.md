# Function: <code>acpi_processor_setup_cpuidle_cx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_processor_setup_cpuidle_cx(struct acpi_processor *pr, struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814ac5c9)
Location: drivers/acpi/processor_idle.c:859
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff814ac5c9-ffffffff814ac64f: acpi_processor_setup_cpuidle_cx (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff814fcb16)
Location: drivers/acpi/processor_idle.c:812
Inline: True
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
In drivers/acpi/processor_idle.c (ffffffff8151f792)
Location: drivers/acpi/processor_idle.c:813
Inline: True
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
In drivers/acpi/processor_idle.c (ffffffff81530cbc)
Location: drivers/acpi/processor_idle.c:813
Inline: True
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
In drivers/acpi/processor_idle.c (ffffffff81591cc0)
Location: drivers/acpi/processor_idle.c:815
Inline: True
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
In drivers/acpi/processor_idle.c (ffffffff815c9050)
Location: drivers/acpi/processor_idle.c:819
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_setup_cpuidle_dev
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
In drivers/acpi/processor_idle.c (ffffffff815e2620)
Location: drivers/acpi/processor_idle.c:820
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_setup_cpuidle_dev
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
In drivers/acpi/processor_idle.c (ffffffff816141ae)
Location: drivers/acpi/processor_idle.c:815
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_setup_cpuidle_dev
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
In drivers/acpi/processor_idle.c (ffffffff8163569e)
Location: drivers/acpi/processor_idle.c:815
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_setup_cpuidle_dev
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
In drivers/acpi/processor_idle.c (ffffffff816e2346)
Location: drivers/acpi/processor_idle.c:679
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816ffb10)
Location: drivers/acpi/processor_idle.c:688
Inline: True
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff816ffb10-ffffffff816ffc29: acpi_processor_setup_cpuidle_cx.isra.0 (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff816e1b5a)
Location: drivers/acpi/processor_idle.c:722
Inline: True
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
In drivers/acpi/processor_idle.c (ffffffff8175a138)
Location: drivers/acpi/processor_idle.c:722
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8188d428)
Location: drivers/acpi/processor_idle.c:725
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff819d4d68)
Location: drivers/acpi/processor_idle.c:741
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a1c6a6)
Location: drivers/acpi/processor_idle.c:741
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a67986)
Location: drivers/acpi/processor_idle.c:741
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
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:932
Inline: True
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
In drivers/acpi/processor_idle.c (ffffffff81604e8e)
Location: drivers/acpi/processor_idle.c:815
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_setup_cpuidle_dev
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
In drivers/acpi/processor_idle.c (ffffffff815eff3e)
Location: drivers/acpi/processor_idle.c:815
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_setup_cpuidle_dev
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
In drivers/acpi/processor_idle.c (ffffffff8162997e)
Location: drivers/acpi/processor_idle.c:815
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_setup_cpuidle_dev
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
In drivers/acpi/processor_idle.c (ffffffff8164381e)
Location: drivers/acpi/processor_idle.c:815
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_setup_cpuidle_dev
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
