# Function: <code>acpi_db_decode_internal_object</code>

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
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff8158c7ef)
Location: drivers/acpi/acpica/dbobject.c:119
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
```
**Symbols:**

```
ffffffff8158c7ef-ffffffff8158c8f2: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff815c3b03)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
```
**Symbols:**

```
ffffffff815c3b03-ffffffff815c3c06: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff815dcfe6)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
```
**Symbols:**

```
ffffffff815dcfe6-ffffffff815dd0e9: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff8160eacb)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
```
**Symbols:**

```
ffffffff8160eacb-ffffffff8160ebd1: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff8162ff77)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
```
**Symbols:**

```
ffffffff8162ff77-ffffffff8163007d: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff816dc9bf)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff816dc9bf-ffffffff816dca92: acpi_db_decode_internal_object.part.0 (STB_LOCAL)
ffffffff816dca92-ffffffff816dcad9: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff816faa63)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff816faa63-ffffffff816fab36: acpi_db_decode_internal_object.part.0 (STB_LOCAL)
ffffffff816fab36-ffffffff816fab7d: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff816dc89a)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff816dc89a-ffffffff816dc99f: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff81754855)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff81754855-ffffffff8175495a: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff81887876)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff81887876-ffffffff81887979: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff819cd950)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff819cd950-ffffffff819cda92: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff81a14e30)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff81a14e30-ffffffff81a14f6a: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff81a60010)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
  - drivers/acpi/acpica/dbobject.c:acpi_db_decode_node
```
**Symbols:**

```
ffffffff81a60010-ffffffff81a6014a: acpi_db_decode_internal_object (STB_GLOBAL)
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
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff81624257)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
```
**Symbols:**

```
ffffffff81624257-ffffffff8162435d: acpi_db_decode_internal_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_db_decode_internal_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbobject.c (ffffffff8163e107)
Location: drivers/acpi/acpica/dbobject.c:92
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbobject.c:acpi_db_display_internal_object
```
**Symbols:**

```
ffffffff8163e107-ffffffff8163e20d: acpi_db_decode_internal_object (STB_GLOBAL)
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
