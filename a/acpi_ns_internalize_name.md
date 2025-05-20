# Function: <code>acpi_ns_internalize_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8149f06c)
Location: drivers/acpi/acpica/nsutils.c:345
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff8149f06c-ffffffff8149f132: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff814ee382)
Location: drivers/acpi/acpica/nsutils.c:346
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node
```
**Symbols:**

```
ffffffff814ee382-ffffffff814ee442: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81510dea)
Location: drivers/acpi/acpica/nsutils.c:346
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
**Symbols:**

```
ffffffff81510dea-ffffffff81510eaa: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8152149d)
Location: drivers/acpi/acpica/nsutils.c:346
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
**Symbols:**

```
ffffffff8152149d-ffffffff8152155d: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815754b4)
Location: drivers/acpi/acpica/nsutils.c:346
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff815754b4-ffffffff81575617: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815ac429)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff815ac429-ffffffff815ac58c: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815c5420)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff815c5420-ffffffff815c5583: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815f6d15)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff815f6d15-ffffffff815f6e7e: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816181bb)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff816181bb-ffffffff81618324: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816c46ee)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff816c46ee-ffffffff816c47d8: acpi_ns_internalize_name.part.0 (STB_LOCAL)
ffffffff816c47d8-ffffffff816c4854: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816e2732)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff816e2732-ffffffff816e281c: acpi_ns_internalize_name.part.0 (STB_LOCAL)
ffffffff816e281c-ffffffff816e2898: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816c461d)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff816c461d-ffffffff816c4766: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8173b96a)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff8173b96a-ffffffff8173bab3: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8186cff3)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff8186cff3-ffffffff8186d156: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff819acb30)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff819acb30-ffffffff819acce8: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff819f3a00)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff819f3a00-ffffffff819f3bb8: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81a3e820)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff81a3e820-ffffffff81a3e9d8: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffff800010790190)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
**Symbols:**

```
ffff800010790190-ffff800010790250: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815f5ab2)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
**Symbols:**

```
ffffffff815f5ab2-ffffffff815f5b76: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815e103d)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
```
**Symbols:**

```
ffffffff815e103d-ffffffff815e10dd: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8160c49b)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff8160c49b-ffffffff8160c604: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ns_internalize_name(const char *external_name, char **converted_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8162634b)
Location: drivers/acpi/acpica/nsutils.c:312
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_node_unlocked
  - drivers/acpi/acpica/dbutils.c:acpi_db_local_ns_lookup
```
**Symbols:**

```
ffffffff8162634b-ffffffff816264b4: acpi_ns_internalize_name (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
