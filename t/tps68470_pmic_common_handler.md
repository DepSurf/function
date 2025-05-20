# Function: <code>tps68470_pmic_common_handler</code>

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
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815a0430)
Location: drivers/acpi/pmic/tps68470_pmic.c:279
Inline: True
Direct callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
**Symbols:**

```
ffffffff815a0430-ffffffff815a051a: tps68470_pmic_common_handler.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815d80c0)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
Inline: True
Direct callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
**Symbols:**

```
ffffffff815d80c0-ffffffff815d818c: tps68470_pmic_common_handler.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815f19d0)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
Inline: True
Direct callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
**Symbols:**

```
ffffffff815f19d0-ffffffff815f1a9c: tps68470_pmic_common_handler.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816238b0)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
Inline: True
Direct callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
**Symbols:**

```
ffffffff816238b0-ffffffff81623980: tps68470_pmic_common_handler.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816453a0)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
Inline: True
Direct callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
**Symbols:**

```
ffffffff816453a0-ffffffff81645470: tps68470_pmic_common_handler.constprop.0 (STB_LOCAL)
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
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f3f72)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff817110f2)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f29c8)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8176cc08)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff818a1c27)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff819eb367)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
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
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a33a97)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
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
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a7ef07)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffff8000107b1190)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
Inline: True
Direct callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
**Symbols:**

```
ffff8000107b1190-ffff8000107b129c: tps68470_pmic_common_handler.constprop.0 (STB_LOCAL)
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
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816391e0)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
Inline: True
Direct callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
**Symbols:**

```
ffffffff816391e0-ffffffff816392b0: tps68470_pmic_common_handler.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81653530)
Location: drivers/acpi/pmic/tps68470_pmic.c:271
Inline: True
Direct callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_vrval_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_clk_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_cfreq_handler
```
**Symbols:**

```
ffffffff81653530-ffffffff81653600: tps68470_pmic_common_handler.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
