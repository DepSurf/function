# Function: <code>acpi_ec_read_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81483076)
Location: drivers/acpi/ec.c:246
Inline: True
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_space_handler
```
**Symbols:**

```
ffffffff81483076-ffffffff814830d5: acpi_ec_read_status.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d1b86)
Location: drivers/acpi/ec.c:251
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff814d1b86-ffffffff814d1be2: acpi_ec_read_status.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f3e1a)
Location: drivers/acpi/ec.c:282
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff814f3e1a-ffffffff814f3e76: acpi_ec_read_status.isra.7 (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff81503573)
Location: drivers/acpi/ec.c:286
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815459d3)
Location: drivers/acpi/ec.c:285
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff8157bfa9)
Location: drivers/acpi/ec.c:285
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff81593669)
Location: drivers/acpi/ec.c:285
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815c4633)
Location: drivers/acpi/ec.c:275
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815e5873)
Location: drivers/acpi/ec.c:277
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff816915d8)
Location: drivers/acpi/ec.c:275
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff816af318)
Location: drivers/acpi/ec.c:275
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff81691928)
Location: drivers/acpi/ec.c:276
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff817073b1)
Location: drivers/acpi/ec.c:277
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff81835365)
Location: drivers/acpi/ec.c:273
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff81968d45)
Location: drivers/acpi/ec.c:274
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff819af326)
Location: drivers/acpi/ec.c:274
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff819f97d6)
Location: drivers/acpi/ec.c:274
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffff800010772484)
Location: drivers/acpi/ec.c:277
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815d7763)
Location: drivers/acpi/ec.c:277
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815c1323)
Location: drivers/acpi/ec.c:277
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815d9b53)
Location: drivers/acpi/ec.c:277
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815f3a13)
Location: drivers/acpi/ec.c:277
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:advance_transaction
```
</details>
</li>
</ul>

## Differences
