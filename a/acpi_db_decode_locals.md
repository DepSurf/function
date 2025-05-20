# Function: <code>acpi_db_decode_locals</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff8158cb57)
Location: drivers/acpi/acpica/dbobject.c:416
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff8158cb57-ffffffff8158cc17: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff815c3e6b)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff815c3e6b-ffffffff815c3f3a: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff815dd36f)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff815dd36f-ffffffff815dd43e: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff8160ee7d)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff8160ee7d-ffffffff8160ef45: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff81630329)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff81630329-ffffffff816303f1: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff816dcd85)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff816dcd85-ffffffff816dce4d: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff816fae29)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff816fae29-ffffffff816faef1: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff816dcc4b)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff816dcc4b-ffffffff816dcd13: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff81754c30)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff81754c30-ffffffff81754d2f: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff81887c3a)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff81887c3a-ffffffff81887d43: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff819cde30)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff819cde30-ffffffff819cdf72: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff81a15310)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff81a15310-ffffffff81a15452: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff81a604f0)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff81a604f0-ffffffff81a60632: acpi_db_decode_locals (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff81624609)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff81624609-ffffffff816246d1: acpi_db_decode_locals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_locals(struct acpi_walk_state *walk_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff8163e4b9)
Location: drivers/acpi/acpica/dbobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_locals
  - drivers/acpi/acpica/dbobject.c:acpi_db_dump_method_info
```
**Symbols:**

```
ffffffff8163e4b9-ffffffff8163e581: acpi_db_decode_locals (STB_GLOBAL)
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
