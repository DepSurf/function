# Function: <code>acpi_ec_mask_gpe</code>

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
In drivers/acpi/ec.c (ffffffff81544bd0)
Location: drivers/acpi/ec.c:427
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff81544640-ffffffff81544687: acpi_ec_mask_gpe.part.12 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff8157acad)
Location: drivers/acpi/ec.c:427
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff8157a6a0-ffffffff8157a6e7: acpi_ec_mask_gpe.part.14 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff815929a7)
Location: drivers/acpi/ec.c:427
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff81592320-ffffffff81592367: acpi_ec_mask_gpe.part.14 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff815c384c)
Location: drivers/acpi/ec.c:417
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815c3220-ffffffff815c3267: acpi_ec_mask_gpe.part.0 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff815e4a8c)
Location: drivers/acpi/ec.c:419
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815e4470-ffffffff815e44b7: acpi_ec_mask_gpe.part.0 (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_mask_gpe(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff800010770858)
Location: drivers/acpi/ec.c:419
Inline: True
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffff800010770858-ffff8000107708dc: acpi_ec_mask_gpe (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d697c)
Location: drivers/acpi/ec.c:419
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815d6360-ffffffff815d63a7: acpi_ec_mask_gpe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c053c)
Location: drivers/acpi/ec.c:419
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815bff20-ffffffff815bff67: acpi_ec_mask_gpe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d8d6c)
Location: drivers/acpi/ec.c:419
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815d8750-ffffffff815d8797: acpi_ec_mask_gpe.part.0 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff815f2c2c)
Location: drivers/acpi/ec.c:419
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815f2610-ffffffff815f2657: acpi_ec_mask_gpe.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
