# Function: <code>acpi_table_initrd_scan</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81fcc837)
Location: drivers/acpi/tables.c:655
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
In drivers/acpi/tables.c (ffffffff8200983b)
Location: drivers/acpi/tables.c:654
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
In drivers/acpi/tables.c (ffffffff820eaed9)
Location: drivers/acpi/tables.c:643
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
In drivers/acpi/tables.c (ffffffff826f3e55)
Location: drivers/acpi/tables.c:643
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
In drivers/acpi/tables.c (ffffffff8271de38)
Location: drivers/acpi/tables.c:649
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
In drivers/acpi/tables.c (ffffffff828d5e63)
Location: drivers/acpi/tables.c:648
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
In drivers/acpi/tables.c (ffffffff828efcb7)
Location: drivers/acpi/tables.c:695
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
In drivers/acpi/tables.c (ffffffff828f8e34)
Location: drivers/acpi/tables.c:696
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_table_initrd_scan();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82d0f732)
Location: drivers/acpi/tables.c:696
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff82d0f732-ffffffff82d0f814: acpi_table_initrd_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_table_initrd_scan();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82ffd1b3)
Location: drivers/acpi/tables.c:685
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init_complete
```
**Symbols:**

```
ffffffff82ffd1b3-ffffffff82ffd295: acpi_table_initrd_scan (STB_LOCAL)
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
In drivers/acpi/tables.c (ffffffff832087b5)
Location: drivers/acpi/tables.c:685
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
In drivers/acpi/tables.c (ffffffff832f0950)
Location: drivers/acpi/tables.c:696
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
In drivers/acpi/tables.c (ffffffff834a88d9)
Location: drivers/acpi/tables.c:741
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
void acpi_table_initrd_scan();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83edf6a0)
Location: drivers/acpi/tables.c:751
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff83edf6a0-ffffffff83edf7b0: acpi_table_initrd_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_table_initrd_scan();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83705130)
Location: drivers/acpi/tables.c:762
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff83705130-ffffffff83705240: acpi_table_initrd_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_table_initrd_scan();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83938660)
Location: drivers/acpi/tables.c:590
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff83938660-ffffffff83938770: acpi_table_initrd_scan (STB_LOCAL)
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
In drivers/acpi/tables.c (ffff80001147bf04)
Location: drivers/acpi/tables.c:696
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
In drivers/acpi/tables.c (ffffffff828e1ba0)
Location: drivers/acpi/tables.c:696
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
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:754
Inline: True
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
In drivers/acpi/tables.c (ffffffff828f4a30)
Location: drivers/acpi/tables.c:696
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
In drivers/acpi/tables.c (ffffffff828f9e88)
Location: drivers/acpi/tables.c:696
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
