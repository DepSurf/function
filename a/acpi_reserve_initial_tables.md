# Function: <code>acpi_reserve_initial_tables</code>

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
void acpi_reserve_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff82ffda40)
Location: drivers/acpi/tables.c:810
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
```
**Symbols:**

```
ffffffff82ffda40-ffffffff82ffdaa4: acpi_reserve_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_reserve_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff8320872e)
Location: drivers/acpi/tables.c:810
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
```
**Symbols:**

```
ffffffff8320872e-ffffffff83208792: acpi_reserve_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_reserve_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff832f08ae)
Location: drivers/acpi/tables.c:821
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
```
**Symbols:**

```
ffffffff832f08ae-ffffffff832f092d: acpi_reserve_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_reserve_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff834a8829)
Location: drivers/acpi/tables.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
```
**Symbols:**

```
ffffffff834a8829-ffffffff834a88b6: acpi_reserve_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_reserve_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83edff80)
Location: drivers/acpi/tables.c:875
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
```
**Symbols:**

```
ffffffff83edff80-ffffffff83ee0012: acpi_reserve_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_reserve_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83705a20)
Location: drivers/acpi/tables.c:886
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
```
**Symbols:**

```
ffffffff83705a20-ffffffff83705ab2: acpi_reserve_initial_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_reserve_initial_tables();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff83938f50)
Location: drivers/acpi/tables.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_boot_table_init
```
**Symbols:**

```
ffffffff83938f50-ffffffff83938fe2: acpi_reserve_initial_tables (STB_GLOBAL)
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
