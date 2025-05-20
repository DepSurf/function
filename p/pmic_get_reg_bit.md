# Function: <code>pmic_get_reg_bit</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815a0444)
Location: drivers/acpi/pmic/tps68470_pmic.c:205
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815d80d3)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815f19e3)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816238c3)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816453b3)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff816f2ab7)
Location: drivers/acpi/pmic/intel_pmic.c:34
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_thermal_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_power_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f3c1d)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff8170fcee)
Location: drivers/acpi/pmic/intel_pmic.c:34
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_thermal_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_power_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81710d9d)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff816f15bb)
Location: drivers/acpi/pmic/intel_pmic.c:34
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_thermal_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_power_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f266d)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff8176b6bb)
Location: drivers/acpi/pmic/intel_pmic.c:34
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_thermal_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_power_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8176c8ad)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff818a0368)
Location: drivers/acpi/pmic/intel_pmic.c:34
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_thermal_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_power_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff818a186d)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff819e9848)
Location: drivers/acpi/pmic/intel_pmic.c:34
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_thermal_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_power_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff819eaf7d)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff81a31f68)
Location: drivers/acpi/pmic/intel_pmic.c:34
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_thermal_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_power_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a336ad)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/intel_pmic.c (ffffffff81a7d3d8)
Location: drivers/acpi/pmic/intel_pmic.c:34
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_thermal_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_power_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a7eb1d)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
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
In drivers/acpi/pmic/tps68470_pmic.c (ffff8000107b11d8)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816391f3)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81653543)
Location: drivers/acpi/pmic/tps68470_pmic.c:197
Inline: True
```
</details>
</li>
</ul>

## Differences
