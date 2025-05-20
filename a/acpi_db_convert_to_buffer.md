# Function: <code>acpi_db_convert_to_buffer</code>

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
In drivers/acpi/acpica/dbconvert.c (ffffffff81588db1)
Location: drivers/acpi/acpica/dbconvert.c:137
Inline: True
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
In drivers/acpi/acpica/dbconvert.c (0)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: True
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
In drivers/acpi/acpica/dbconvert.c (0)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: True
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
In drivers/acpi/acpica/dbconvert.c (0)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: True
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
In drivers/acpi/acpica/dbconvert.c (0)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_buffer(char *string, union acpi_object *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d8ac0)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
**Symbols:**

```
ffffffff816d8ac0-ffffffff816d8c17: acpi_db_convert_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_buffer(char *string, union acpi_object *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff816f6a4f)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
**Symbols:**

```
ffffffff816f6a4f-ffffffff816f6ba6: acpi_db_convert_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_buffer(char *string, union acpi_object *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d88bf)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
**Symbols:**

```
ffffffff816d88bf-ffffffff816d8a1d: acpi_db_convert_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_buffer(char *string, union acpi_object *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff81750473)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
**Symbols:**

```
ffffffff81750473-ffffffff817505d1: acpi_db_convert_to_buffer (STB_LOCAL)
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
In drivers/acpi/acpica/dbconvert.c (ffffffff8188310c)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_buffer(char *string, union acpi_object *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff819c7f70)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
**Symbols:**

```
ffffffff819c7f70-ffffffff819c8163: acpi_db_convert_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_buffer(char *string, union acpi_object *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a0f390)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
**Symbols:**

```
ffffffff81a0f390-ffffffff81a0f583: acpi_db_convert_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_buffer(char *string, union acpi_object *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a5a4d0)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_object
```
**Symbols:**

```
ffffffff81a5a4d0-ffffffff81a5a6c3: acpi_db_convert_to_buffer (STB_LOCAL)
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
In drivers/acpi/acpica/dbconvert.c (0)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: True
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
In drivers/acpi/acpica/dbconvert.c (0)
Location: drivers/acpi/acpica/dbconvert.c:101
Inline: True
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
