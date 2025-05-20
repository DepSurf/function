# Function: <code>acpi_db_convert_to_object</code>

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
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff81588d4c)
Location: drivers/acpi/acpica/dbconvert.c:254
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff81588d4c-ffffffff81588ef5: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff815bfec3)
Location: drivers/acpi/acpica/dbconvert.c:218
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff815bfec3-ffffffff815c006e: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff815d9334)
Location: drivers/acpi/acpica/dbconvert.c:218
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff815d9334-ffffffff815d94df: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff8160ae48)
Location: drivers/acpi/acpica/dbconvert.c:218
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff8160ae48-ffffffff8160aff0: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff8162c2e9)
Location: drivers/acpi/acpica/dbconvert.c:218
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff8162c2e9-ffffffff8162c491: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d8c17)
Location: drivers/acpi/acpica/dbconvert.c:222
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff816d8c17-ffffffff816d8c75: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff816f6ba6)
Location: drivers/acpi/acpica/dbconvert.c:222
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff816f6ba6-ffffffff816f6c04: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff816d8a1d)
Location: drivers/acpi/acpica/dbconvert.c:222
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff816d8a1d-ffffffff816d8a7b: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff817505d1)
Location: drivers/acpi/acpica/dbconvert.c:222
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff817505d1-ffffffff8175062f: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff818830b1)
Location: drivers/acpi/acpica/dbconvert.c:222
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff818830b1-ffffffff81883251: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff819c81e0)
Location: drivers/acpi/acpica/dbconvert.c:222
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff819c81e0-ffffffff819c8274: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a0f600)
Location: drivers/acpi/acpica/dbconvert.c:222
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff81a0f600-ffffffff81a0f694: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a5a740)
Location: drivers/acpi/acpica/dbconvert.c:222
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff81a5a740-ffffffff81a5a7d4: acpi_db_convert_to_object (STB_GLOBAL)
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
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff816205c9)
Location: drivers/acpi/acpica/dbconvert.c:218
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff816205c9-ffffffff81620771: acpi_db_convert_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_db_convert_to_object(acpi_object_type type, char *string, union acpi_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbconvert.c (ffffffff8163a479)
Location: drivers/acpi/acpica/dbconvert.c:218
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute_method
```
**Symbols:**

```
ffffffff8163a479-ffffffff8163a621: acpi_db_convert_to_object (STB_GLOBAL)
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
