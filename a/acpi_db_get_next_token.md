# Function: <code>acpi_db_get_next_token</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff8158afd8)
Location: drivers/acpi/acpica/dbinput.c:470
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
**Symbols:**

```
ffffffff8158afd8-ffffffff8158b0e8: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff815c22a5)
Location: drivers/acpi/acpica/dbinput.c:454
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
**Symbols:**

```
ffffffff815c22a5-ffffffff815c23b6: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff815db72b)
Location: drivers/acpi/acpica/dbinput.c:454
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
**Symbols:**

```
ffffffff815db72b-ffffffff815db83c: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff8160d22d)
Location: drivers/acpi/acpica/dbinput.c:454
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
**Symbols:**

```
ffffffff8160d22d-ffffffff8160d33f: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff8162e6ce)
Location: drivers/acpi/acpica/dbinput.c:454
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
**Symbols:**

```
ffffffff8162e6ce-ffffffff8162e7e0: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff816dae27)
Location: drivers/acpi/acpica/dbinput.c:458
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
**Symbols:**

```
ffffffff816dae27-ffffffff816daf47: acpi_db_get_next_token.part.0 (STB_LOCAL)
ffffffff816db01a-ffffffff816db03b: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff816f8dec)
Location: drivers/acpi/acpica/dbinput.c:461
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
**Symbols:**

```
ffffffff816f8dec-ffffffff816f8f0c: acpi_db_get_next_token.part.0 (STB_LOCAL)
ffffffff816f8fdf-ffffffff816f9000: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff816dac5b)
Location: drivers/acpi/acpica/dbinput.c:461
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
**Symbols:**

```
ffffffff816dac5b-ffffffff816dad71: acpi_db_get_next_token.part.0 (STB_LOCAL)
ffffffff816dae1e-ffffffff816dae3f: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff81752a56)
Location: drivers/acpi/acpica/dbinput.c:461
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
**Symbols:**

```
ffffffff81752a56-ffffffff81752b6c: acpi_db_get_next_token.part.0 (STB_LOCAL)
ffffffff81752c19-ffffffff81752c3a: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff81885833)
Location: drivers/acpi/acpica/dbinput.c:461
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
```
**Symbols:**

```
ffffffff81885833-ffffffff81885971: acpi_db_get_next_token.part.0 (STB_LOCAL)
ffffffff81885a2e-ffffffff81885a6d: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff819cb4ea)
Location: drivers/acpi/acpica/dbinput.c:461
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
```
**Symbols:**

```
ffffffff819cb1f0-ffffffff819cb416: acpi_db_get_next_token.part.0 (STB_LOCAL)
ffffffff819cb430-ffffffff819cb461: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff81a1294a)
Location: drivers/acpi/acpica/dbinput.c:461
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
```
**Symbols:**

```
ffffffff81a12660-ffffffff81a12875: acpi_db_get_next_token.part.0 (STB_LOCAL)
ffffffff81a12890-ffffffff81a128c1: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff81a5dada)
Location: drivers/acpi/acpica/dbinput.c:464
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
```
**Symbols:**

```
ffffffff81a5d7f0-ffffffff81a5da05: acpi_db_get_next_token.part.0 (STB_LOCAL)
ffffffff81a5da20-ffffffff81a5da51: acpi_db_get_next_token (STB_GLOBAL)
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
<summary>In <code>gcp</code>: ✅</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff816229ae)
Location: drivers/acpi/acpica/dbinput.c:454
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
**Symbols:**

```
ffffffff816229ae-ffffffff81622ac0: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *acpi_db_get_next_token(char *string, char **next, acpi_object_type *return_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff8163c85e)
Location: drivers/acpi/acpica/dbinput.c:454
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
**Symbols:**

```
ffffffff8163c85e-ffffffff8163c970: acpi_db_get_next_token (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
