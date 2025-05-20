# Function: <code>check_multiple_madt</code>

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
In drivers/acpi/tables.c (ffffffff81fa0bd3)
Location: drivers/acpi/tables.c:415
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff81fcc916)
Location: drivers/acpi/tables.c:424
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff8200991a)
Location: drivers/acpi/tables.c:424
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff820eafa9)
Location: drivers/acpi/tables.c:408
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff826f3f25)
Location: drivers/acpi/tables.c:408
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff8271df08)
Location: drivers/acpi/tables.c:413
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff828d5f33)
Location: drivers/acpi/tables.c:412
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff828efd8f)
Location: drivers/acpi/tables.c:450
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff828f8f00)
Location: drivers/acpi/tables.c:451
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff82d10016)
Location: drivers/acpi/tables.c:451
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff82ffdac5)
Location: drivers/acpi/tables.c:440
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
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
In drivers/acpi/tables.c (ffffffff83208881)
Location: drivers/acpi/tables.c:440
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
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
In drivers/acpi/tables.c (ffffffff832f0a1c)
Location: drivers/acpi/tables.c:450
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
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
In drivers/acpi/tables.c (ffffffff834a89a1)
Location: drivers/acpi/tables.c:495
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void check_multiple_madt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83edf5e0)
Location: drivers/acpi/tables.c:505
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff83edf5e0-ffffffff83edf685: check_multiple_madt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void check_multiple_madt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83705070)
Location: drivers/acpi/tables.c:515
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff83705070-ffffffff83705115: check_multiple_madt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void check_multiple_madt();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff839385a0)
Location: drivers/acpi/tables.c:343
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff839385a0-ffffffff83938645: check_multiple_madt (STB_LOCAL)
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
In drivers/acpi/tables.c (ffff80001147c020)
Location: drivers/acpi/tables.c:451
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff828e1c6c)
Location: drivers/acpi/tables.c:451
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff828d9cc9)
Location: drivers/acpi/tables.c:451
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff828f4afc)
Location: drivers/acpi/tables.c:451
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
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
In drivers/acpi/tables.c (ffffffff828f9f54)
Location: drivers/acpi/tables.c:451
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
