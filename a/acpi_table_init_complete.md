# Function: <code>acpi_table_init_complete</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_table_init_complete();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82ffdaa4)
Location: drivers/acpi/tables.c:829
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff82ffdaa4-ffffffff82ffdb3e: acpi_table_init_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_table_init_complete();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83208792)
Location: drivers/acpi/tables.c:829
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff83208792-ffffffff83208906: acpi_table_init_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_table_init_complete();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff832f092d)
Location: drivers/acpi/tables.c:840
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff832f092d-ffffffff832f0aa1: acpi_table_init_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_table_init_complete();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff834a88b6)
Location: drivers/acpi/tables.c:885
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff834a88b6-ffffffff834a8a30: acpi_table_init_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_table_init_complete();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83ee0075)
Location: drivers/acpi/tables.c:894
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
**Symbols:**

```
ffffffff83ee0030-ffffffff83ee0049: acpi_table_init_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_table_init_complete();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83705b15)
Location: drivers/acpi/tables.c:905
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
**Symbols:**

```
ffffffff83705ad0-ffffffff83705ae9: acpi_table_init_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_table_init_complete();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83939045)
Location: drivers/acpi/tables.c:733
Inline: True
Inline callers:
  - drivers/acpi/tables.c:acpi_table_init
Direct callers:
  - arch/x86/kernel/acpi/boot.c:early_acpi_boot_init
```
**Symbols:**

```
ffffffff83939000-ffffffff83939019: acpi_table_init_complete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
