# Function: <code>acpi_locate_initial_tables</code>

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
int acpi_locate_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82ffd9e7)
Location: drivers/acpi/tables.c:791
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff82ffd9e7-ffffffff82ffda40: acpi_locate_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_locate_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff832086dc)
Location: drivers/acpi/tables.c:791
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff832086dc-ffffffff8320872e: acpi_locate_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_locate_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff832f0844)
Location: drivers/acpi/tables.c:802
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff832f0844-ffffffff832f08ae: acpi_locate_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_locate_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff834a87b5)
Location: drivers/acpi/tables.c:847
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff834a87b5-ffffffff834a8829: acpi_locate_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_locate_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83edfef0)
Location: drivers/acpi/tables.c:856
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff83edfef0-ffffffff83edff6d: acpi_locate_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_locate_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83705990)
Location: drivers/acpi/tables.c:867
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff83705990-ffffffff83705a0d: acpi_locate_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_locate_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83938ec0)
Location: drivers/acpi/tables.c:695
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
  - drivers/acpi/tables.c:acpi_table_init
```
**Symbols:**

```
ffffffff83938ec0-ffffffff83938f3d: acpi_locate_initial_tables (STB_GLOBAL)
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
