# Function: <code>acpi_ec_is_gpe_raised</code>

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
In drivers/acpi/ec.c (ffffffff81483501)
Location: drivers/acpi/ec.c:309
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff814d20a1)
Location: drivers/acpi/ec.c:314
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff814f454a)
Location: drivers/acpi/ec.c:345
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff81503abd)
Location: drivers/acpi/ec.c:349
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff81545f40)
Location: drivers/acpi/ec.c:348
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff8157b357)
Location: drivers/acpi/ec.c:348
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff81593b47)
Location: drivers/acpi/ec.c:348
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff815c4bf7)
Location: drivers/acpi/ec.c:338
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff815e5e37)
Location: drivers/acpi/ec.c:340
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff816911c2)
Location: drivers/acpi/ec.c:338
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:340
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
In drivers/acpi/ec.c (ffffffff815d7d27)
Location: drivers/acpi/ec.c:340
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff815c18e7)
Location: drivers/acpi/ec.c:340
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff815da117)
Location: drivers/acpi/ec.c:340
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff815f3fd7)
Location: drivers/acpi/ec.c:340
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
</details>
</li>
</ul>

## Differences
