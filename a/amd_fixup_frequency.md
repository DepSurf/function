# Function: <code>amd_fixup_frequency</code>

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
In drivers/acpi/processor_perflib.c (ffffffff814aece1)
Location: drivers/acpi/processor_perflib.c:290
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff814fe83f)
Location: drivers/acpi/processor_perflib.c:290
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff81521533)
Location: drivers/acpi/processor_perflib.c:288
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff81532eef)
Location: drivers/acpi/processor_perflib.c:286
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
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
In drivers/acpi/processor_perflib.c (ffffffff81594548)
Location: drivers/acpi/processor_perflib.c:286
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
In drivers/acpi/processor_perflib.c (ffffffff815cb868)
Location: drivers/acpi/processor_perflib.c:286
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff815e4e48)
Location: drivers/acpi/processor_perflib.c:286
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff81616a33)
Location: drivers/acpi/processor_perflib.c:273
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff81637f93)
Location: drivers/acpi/processor_perflib.c:259
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff816e4d30)
Location: drivers/acpi/processor_perflib.c:259
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
**Symbols:**

```
ffffffff816e4d30-ffffffff816e4db2: amd_fixup_frequency.constprop.0 (STB_LOCAL)
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
In drivers/acpi/processor_perflib.c (ffffffff817027a0)
Location: drivers/acpi/processor_perflib.c:258
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
**Symbols:**

```
ffffffff817027a0-ffffffff81702822: amd_fixup_frequency.constprop.0 (STB_LOCAL)
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
In drivers/acpi/processor_perflib.c (ffffffff816e4240)
Location: drivers/acpi/processor_perflib.c:256
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff8175cee0)
Location: drivers/acpi/processor_perflib.c:255
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff81890a98)
Location: drivers/acpi/processor_perflib.c:255
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff819d7a7f)
Location: drivers/acpi/processor_perflib.c:253
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff81a1f47f)
Location: drivers/acpi/processor_perflib.c:275
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff81a6a79f)
Location: drivers/acpi/processor_perflib.c:275
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:286
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
In drivers/acpi/processor_perflib.c (ffffffff8160725c)
Location: drivers/acpi/processor_perflib.c:259
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff815f2334)
Location: drivers/acpi/processor_perflib.c:259
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff8162c273)
Location: drivers/acpi/processor_perflib.c:259
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
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
In drivers/acpi/processor_perflib.c (ffffffff81646113)
Location: drivers/acpi/processor_perflib.c:259
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
```
</details>
</li>
</ul>

## Differences
