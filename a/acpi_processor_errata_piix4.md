# Function: <code>acpi_processor_errata_piix4</code>

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
In drivers/acpi/acpi_processor.c (ffffffff81482225)
Location: drivers/acpi/acpi_processor.c:42
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
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
In drivers/acpi/acpi_processor.c (ffffffff814d0d2e)
Location: drivers/acpi/acpi_processor.c:42
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
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
In drivers/acpi/acpi_processor.c (ffffffff814f2de4)
Location: drivers/acpi/acpi_processor.c:42
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
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
In drivers/acpi/acpi_processor.c (ffffffff8150087a)
Location: drivers/acpi/acpi_processor.c:42
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff81542b1a)
Location: drivers/acpi/acpi_processor.c:42
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff81578a66)
Location: drivers/acpi/acpi_processor.c:42
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815906d6)
Location: drivers/acpi/acpi_processor.c:42
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815c1527)
Location: drivers/acpi/acpi_processor.c:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815e27c7)
Location: drivers/acpi/acpi_processor.c:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff8168db10)
Location: drivers/acpi/acpi_processor.c:39
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8168db10-ffffffff8168de65: acpi_processor_errata_piix4.isra.0 (STB_LOCAL)
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
In drivers/acpi/acpi_processor.c (ffffffff816ab8f0)
Location: drivers/acpi/acpi_processor.c:39
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff816ab8f0-ffffffff816abc45: acpi_processor_errata_piix4.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff8168e150)
Location: drivers/acpi/acpi_processor.c:32
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8168e150-ffffffff8168e395: acpi_processor_errata_piix4.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff817039c0)
Location: drivers/acpi/acpi_processor.c:32
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff817039c0-ffffffff81703bf9: acpi_processor_errata_piix4.isra.0 (STB_LOCAL)
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
In drivers/acpi/acpi_processor.c (ffffffff81831a00)
Location: drivers/acpi/acpi_processor.c:32
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81831a00-ffffffff81831c58: acpi_processor_errata_piix4.isra.0 (STB_LOCAL)
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
In drivers/acpi/acpi_processor.c (ffffffff81965140)
Location: drivers/acpi/acpi_processor.c:32
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81965140-ffffffff81965397: acpi_processor_errata_piix4.isra.0 (STB_LOCAL)
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
In drivers/acpi/acpi_processor.c (ffffffff819ab690)
Location: drivers/acpi/acpi_processor.c:33
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff819ab690-ffffffff819ab8d1: acpi_processor_errata_piix4.isra.0 (STB_LOCAL)
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
In drivers/acpi/acpi_processor.c (ffffffff819f5ac0)
Location: drivers/acpi/acpi_processor.c:38
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff819f5ac0-ffffffff819f5d01: acpi_processor_errata_piix4.isra.0 (STB_LOCAL)
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
In drivers/acpi/acpi_processor.c (ffff80001076f210)
Location: drivers/acpi/acpi_processor.c:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815d4a81)
Location: drivers/acpi/acpi_processor.c:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815be641)
Location: drivers/acpi/acpi_processor.c:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815d6aa7)
Location: drivers/acpi/acpi_processor.c:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
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
In drivers/acpi/acpi_processor.c (ffffffff815f0967)
Location: drivers/acpi/acpi_processor.c:39
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
</details>
</li>
</ul>

## Differences
