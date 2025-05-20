# Function: <code>acpi_tb_delete_namespace_by_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff814a47f0)
Location: drivers/acpi/acpica/tbdata.c:584
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff814a47f0-ffffffff814a487b: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff814f3b32)
Location: drivers/acpi/acpica/tbdata.c:584
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbxfload.c:acpi_unload_parent_table
```
**Symbols:**

```
ffffffff814f3b32-ffffffff814f3bba: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81516680)
Location: drivers/acpi/acpica/tbdata.c:585
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff81516680-ffffffff815166fa: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81526ee8)
Location: drivers/acpi/acpica/tbdata.c:585
Inline: True
```
**Symbols:**

```
ffffffff81526ee8-ffffffff81526f62: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8157e43a)
Location: drivers/acpi/acpica/tbdata.c:750
Inline: True
```
**Symbols:**

```
ffffffff8157e43a-ffffffff8157e557: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815b5619)
Location: drivers/acpi/acpica/tbdata.c:716
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff815b5619-ffffffff815b5736: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815ce9d5)
Location: drivers/acpi/acpica/tbdata.c:716
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff815ce9d5-ffffffff815ceaf2: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81600243)
Location: drivers/acpi/acpica/tbdata.c:717
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff81600243-ffffffff81600360: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816216ed)
Location: drivers/acpi/acpica/tbdata.c:717
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff816216ed-ffffffff8162180a: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816cdcea)
Location: drivers/acpi/acpica/tbdata.c:717
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff816cdcea-ffffffff816cde07: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816ebcf0)
Location: drivers/acpi/acpica/tbdata.c:717
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff816ebcf0-ffffffff816ebe0d: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816cdbc9)
Location: drivers/acpi/acpica/tbdata.c:717
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff816cdbc9-ffffffff816cdce6: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81745099)
Location: drivers/acpi/acpica/tbdata.c:717
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff81745099-ffffffff817451b6: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81876df4)
Location: drivers/acpi/acpica/tbdata.c:745
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff81876df4-ffffffff81876f21: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819b8b60)
Location: drivers/acpi/acpica/tbdata.c:745
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff819b8b60-ffffffff819b8cdb: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819ffcf0)
Location: drivers/acpi/acpica/tbdata.c:745
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff819ffcf0-ffffffff819ffe6b: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81a4ab70)
Location: drivers/acpi/acpica/tbdata.c:745
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff81a4ab70-ffffffff81a4aceb: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
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
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffff800010796ea0)
Location: drivers/acpi/acpica/tbdata.c:717
Inline: True
```
**Symbols:**

```
ffff800010796ea0-ffff800010796f44: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
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
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815fbc08)
Location: drivers/acpi/acpica/tbdata.c:717
Inline: True
```
**Symbols:**

```
ffffffff815fbc08-ffffffff815fbc82: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815e7133)
Location: drivers/acpi/acpica/tbdata.c:717
Inline: True
```
**Symbols:**

```
ffffffff815e7133-ffffffff815e71ad: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816159cd)
Location: drivers/acpi/acpica/tbdata.c:717
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff816159cd-ffffffff81615aea: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_tb_delete_namespace_by_owner(u32 table_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8162f87d)
Location: drivers/acpi/acpica/tbdata.c:717
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_unload_table
```
**Symbols:**

```
ffffffff8162f87d-ffffffff8162f99a: acpi_tb_delete_namespace_by_owner (STB_GLOBAL)
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
