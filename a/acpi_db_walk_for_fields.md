# Function: <code>acpi_db_walk_for_fields</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_walk_for_fields(acpi_handle obj_handle, u32 nesting_level, void *context, void **return_value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbnames.c (ffffffff816dbfea)
Location: drivers/acpi/acpica/dbnames.c:519
Inline: True
```
**Symbols:**

```
ffffffff816dbfea-ffffffff816dc0e4: acpi_db_walk_for_fields.part.0 (STB_LOCAL)
ffffffff816dc0e4-ffffffff816dc125: acpi_db_walk_for_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_walk_for_fields(acpi_handle obj_handle, u32 nesting_level, void *context, void **return_value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbnames.c (ffffffff816fa08e)
Location: drivers/acpi/acpica/dbnames.c:519
Inline: True
```
**Symbols:**

```
ffffffff816fa08e-ffffffff816fa188: acpi_db_walk_for_fields.part.0 (STB_LOCAL)
ffffffff816fa188-ffffffff816fa1c9: acpi_db_walk_for_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_db_walk_for_fields(acpi_handle obj_handle, u32 nesting_level, void *context, void **return_value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbnames.c (ffffffff816dbed6)
Location: drivers/acpi/acpica/dbnames.c:519
Inline: True
```
**Symbols:**

```
ffffffff816dbed6-ffffffff816dc001: acpi_db_walk_for_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_db_walk_for_fields(acpi_handle obj_handle, u32 nesting_level, void *context, void **return_value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbnames.c (ffffffff81753e91)
Location: drivers/acpi/acpica/dbnames.c:519
Inline: True
```
**Symbols:**

```
ffffffff81753e91-ffffffff81753fbc: acpi_db_walk_for_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_db_walk_for_fields(acpi_handle obj_handle, u32 nesting_level, void *context, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbnames.c (ffffffff81886cbe)
Location: drivers/acpi/acpica/dbnames.c:519
Inline: False
```
**Symbols:**

```
ffffffff81886cbe-ffffffff81886e08: acpi_db_walk_for_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_db_walk_for_fields(acpi_handle obj_handle, u32 nesting_level, void *context, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbnames.c (ffffffff819ccb60)
Location: drivers/acpi/acpica/dbnames.c:519
Inline: False
```
**Symbols:**

```
ffffffff819ccb60-ffffffff819ccca9: acpi_db_walk_for_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_db_walk_for_fields(acpi_handle obj_handle, u32 nesting_level, void *context, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbnames.c (ffffffff81a13ff0)
Location: drivers/acpi/acpica/dbnames.c:519
Inline: False
```
**Symbols:**

```
ffffffff81a13ff0-ffffffff81a14139: acpi_db_walk_for_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_db_walk_for_fields(acpi_handle obj_handle, u32 nesting_level, void *context, void **return_value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbnames.c (ffffffff81a5f180)
Location: drivers/acpi/acpica/dbnames.c:519
Inline: False
```
**Symbols:**

```
ffffffff81a5f180-ffffffff81a5f2c9: acpi_db_walk_for_fields (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
