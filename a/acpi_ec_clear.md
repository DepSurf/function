# Function: <code>acpi_ec_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ec_clear(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81484352)
Location: drivers/acpi/ec.c:832
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_unblock_transactions
```
**Symbols:**

```
ffffffff81484352-ffffffff814843ce: acpi_ec_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ec_clear(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d2dbc)
Location: drivers/acpi/ec.c:839
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_unblock_transactions
```
**Symbols:**

```
ffffffff814d2dbc-ffffffff814d2e38: acpi_ec_clear (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff814f5405)
Location: drivers/acpi/ec.c:499
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c4a28)
Location: drivers/acpi/ec.c:496
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff815e5c68)
Location: drivers/acpi/ec.c:498
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff81690f28)
Location: drivers/acpi/ec.c:504
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff816aec5a)
Location: drivers/acpi/ec.c:487
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff8169126a)
Location: drivers/acpi/ec.c:488
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff81706d1a)
Location: drivers/acpi/ec.c:490
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:511
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:512
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:512
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:512
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffff800010772ab0)
Location: drivers/acpi/ec.c:498
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff815d7b58)
Location: drivers/acpi/ec.c:498
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff815c1718)
Location: drivers/acpi/ec.c:498
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff815d9f48)
Location: drivers/acpi/ec.c:498
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff815f3e08)
Location: drivers/acpi/ec.c:498
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
