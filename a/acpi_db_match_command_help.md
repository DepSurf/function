# Function: <code>acpi_db_match_command_help</code>

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
In drivers/acpi/acpica/dbinput.c (ffffffff8158af27)
Location: drivers/acpi/acpica/dbinput.c:353
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
In drivers/acpi/acpica/dbinput.c (ffffffff815c2223)
Location: drivers/acpi/acpica/dbinput.c:333
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
In drivers/acpi/acpica/dbinput.c (ffffffff815db6a9)
Location: drivers/acpi/acpica/dbinput.c:333
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
In drivers/acpi/acpica/dbinput.c (ffffffff8160d1a6)
Location: drivers/acpi/acpica/dbinput.c:333
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
In drivers/acpi/acpica/dbinput.c (ffffffff8162e647)
Location: drivers/acpi/acpica/dbinput.c:333
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u8 acpi_db_match_command_help(const char *command, const struct acpi_db_command_help *help);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff816daf47)
Location: drivers/acpi/acpica/dbinput.c:337
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
**Symbols:**

```
ffffffff816daf47-ffffffff816dafd4: acpi_db_match_command_help (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 acpi_db_match_command_help(const char *command, const struct acpi_db_command_help *help);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff816f8f0c)
Location: drivers/acpi/acpica/dbinput.c:340
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
```
**Symbols:**

```
ffffffff816f8f0c-ffffffff816f8f99: acpi_db_match_command_help (STB_LOCAL)
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
In drivers/acpi/acpica/dbinput.c (ffffffff816dad99)
Location: drivers/acpi/acpica/dbinput.c:340
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
In drivers/acpi/acpica/dbinput.c (ffffffff81752b94)
Location: drivers/acpi/acpica/dbinput.c:340
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
In drivers/acpi/acpica/dbinput.c (ffffffff81885999)
Location: drivers/acpi/acpica/dbinput.c:340
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
In drivers/acpi/acpica/dbinput.c (ffffffff819cb11f)
Location: drivers/acpi/acpica/dbinput.c:340
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
In drivers/acpi/acpica/dbinput.c (ffffffff81a1258f)
Location: drivers/acpi/acpica/dbinput.c:340
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
In drivers/acpi/acpica/dbinput.c (ffffffff81a5d71f)
Location: drivers/acpi/acpica/dbinput.c:343
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
In drivers/acpi/acpica/dbinput.c (ffffffff81622927)
Location: drivers/acpi/acpica/dbinput.c:333
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
In drivers/acpi/acpica/dbinput.c (ffffffff8163c7d7)
Location: drivers/acpi/acpica/dbinput.c:333
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info
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
</ul>
