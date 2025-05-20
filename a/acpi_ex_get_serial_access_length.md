# Function: <code>acpi_ex_get_serial_access_length</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 acpi_ex_get_serial_access_length(u32 accessor_type, u32 access_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfield.c (ffffffff814951b1)
Location: drivers/acpi/acpica/exfield.c:73
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
```
**Symbols:**

```
ffffffff814951b1-ffffffff814951e4: acpi_ex_get_serial_access_length (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 acpi_ex_get_serial_access_length(u32 accessor_type, u32 access_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfield.c (ffffffff814e41b6)
Location: drivers/acpi/acpica/exfield.c:73
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff814e41b6-ffffffff814e41eb: acpi_ex_get_serial_access_length (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 acpi_ex_get_serial_access_length(u32 accessor_type, u32 access_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfield.c (ffffffff81506a0a)
Location: drivers/acpi/acpica/exfield.c:73
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff81506a0a-ffffffff81506a3f: acpi_ex_get_serial_access_length (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 acpi_ex_get_serial_access_length(u32 accessor_type, u32 access_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfield.c (ffffffff8151700a)
Location: drivers/acpi/acpica/exfield.c:73
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff8151700a-ffffffff8151703f: acpi_ex_get_serial_access_length (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 acpi_ex_get_serial_access_length(u32 accessor_type, u32 access_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfield.c (ffffffff8156370e)
Location: drivers/acpi/acpica/exfield.c:73
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff8156370e-ffffffff81563749: acpi_ex_get_serial_access_length (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 acpi_ex_get_serial_access_length(u32 accessor_type, u32 access_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfield.c (ffffffff8159a441)
Location: drivers/acpi/acpica/exfield.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
```
**Symbols:**

```
ffffffff8159a441-ffffffff8159a47c: acpi_ex_get_serial_access_length (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
