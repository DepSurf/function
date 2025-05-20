# Function: <code>acpi_dm_compare_aml_resources</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbcmds.c (ffffffff8158825b)
Location: drivers/acpi/acpica/dbcmds.c:599
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
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
In drivers/acpi/acpica/dbcmds.c (ffffffff815bf3d4)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
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
In drivers/acpi/acpica/dbcmds.c (ffffffff815d883d)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
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
In drivers/acpi/acpica/dbcmds.c (ffffffff8160a338)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
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
In drivers/acpi/acpica/dbcmds.c (ffffffff8162b7d9)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_dm_compare_aml_resources(u8 *aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 *aml2_buffer, acpi_rsdesc_size aml2_buffer_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbcmds.c (ffffffff816d7c73)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: False
```
**Symbols:**

```
ffffffff816d7c73-ffffffff816d7d9d: acpi_dm_compare_aml_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_dm_compare_aml_resources(u8 *aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 *aml2_buffer, acpi_rsdesc_size aml2_buffer_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbcmds.c (ffffffff816f5c08)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: False
```
**Symbols:**

```
ffffffff816f5c08-ffffffff816f5d32: acpi_dm_compare_aml_resources (STB_LOCAL)
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
In drivers/acpi/acpica/dbcmds.c (ffffffff816d7b9a)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: True
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
In drivers/acpi/acpica/dbcmds.c (ffffffff8174f733)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: True
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
In drivers/acpi/acpica/dbcmds.c (ffffffff81882282)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_dm_compare_aml_resources(u8 *aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 *aml2_buffer, acpi_rsdesc_size aml2_buffer_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbcmds.c (ffffffff819c6d00)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
**Symbols:**

```
ffffffff819c6d00-ffffffff819c6e97: acpi_dm_compare_aml_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_dm_compare_aml_resources(u8 *aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 *aml2_buffer, acpi_rsdesc_size aml2_buffer_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbcmds.c (ffffffff81a0e100)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
**Symbols:**

```
ffffffff81a0e100-ffffffff81a0e297: acpi_dm_compare_aml_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_dm_compare_aml_resources(u8 *aml1_buffer, acpi_rsdesc_size aml1_buffer_length, u8 *aml2_buffer, acpi_rsdesc_size aml2_buffer_length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbcmds.c (ffffffff81a59100)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
```
**Symbols:**

```
ffffffff81a59100-ffffffff81a59297: acpi_dm_compare_aml_resources (STB_LOCAL)
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbcmds.c (ffffffff8161fab9)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
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
In drivers/acpi/acpica/dbcmds.c (ffffffff81639969)
Location: drivers/acpi/acpica/dbcmds.c:563
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
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
