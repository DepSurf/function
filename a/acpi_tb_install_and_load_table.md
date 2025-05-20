# Function: <code>acpi_tb_install_and_load_table</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81516935)
Location: drivers/acpi/acpica/tbdata.c:847
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
**Symbols:**

```
ffffffff81516935-ffffffff8151699b: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8152723b)
Location: drivers/acpi/acpica/tbdata.c:847
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffffffff8152723b-ffffffff815272a1: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8157e8bd)
Location: drivers/acpi/acpica/tbdata.c:1008
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
**Symbols:**

```
ffffffff8157e8bd-ffffffff8157e981: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815b5a8a)
Location: drivers/acpi/acpica/tbdata.c:980
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
**Symbols:**

```
ffffffff815b5a8a-ffffffff815b5b4e: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815cee46)
Location: drivers/acpi/acpica/tbdata.c:980
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
**Symbols:**

```
ffffffff815cee46-ffffffff815cef0a: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816006b4)
Location: drivers/acpi/acpica/tbdata.c:968
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
**Symbols:**

```
ffffffff816006b4-ffffffff81600778: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81621b5f)
Location: drivers/acpi/acpica/tbdata.c:969
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
**Symbols:**

```
ffffffff81621b5f-ffffffff81621c23: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816ce180)
Location: drivers/acpi/acpica/tbdata.c:972
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffffffff816ce180-ffffffff816ce244: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816ec186)
Location: drivers/acpi/acpica/tbdata.c:972
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffffffff816ec186-ffffffff816ec24a: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816ce05f)
Location: drivers/acpi/acpica/tbdata.c:972
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffffffff816ce05f-ffffffff816ce123: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8174552f)
Location: drivers/acpi/acpica/tbdata.c:972
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffffffff8174552f-ffffffff817455f3: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, struct acpi_table_header *table, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81877306)
Location: drivers/acpi/acpica/tbdata.c:1003
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffffffff81877306-ffffffff818773eb: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, struct acpi_table_header *table, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819b92d0)
Location: drivers/acpi/acpica/tbdata.c:1003
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffffffff819b92d0-ffffffff819b93b7: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, struct acpi_table_header *table, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81a00460)
Location: drivers/acpi/acpica/tbdata.c:1003
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffffffff81a00460-ffffffff81a00547: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, struct acpi_table_header *table, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81a4b2e0)
Location: drivers/acpi/acpica/tbdata.c:1003
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffffffff81a4b2e0-ffffffff81a4b3c7: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffff800010797248)
Location: drivers/acpi/acpica/tbdata.c:969
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffff800010797248-ffff8000107972e0: acpi_tb_install_and_load_table (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815fbec3)
Location: drivers/acpi/acpica/tbdata.c:969
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffffffff815fbec3-ffffffff815fbf29: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815e73ee)
Location: drivers/acpi/acpica/tbdata.c:969
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbxfload.c:acpi_load_table
```
**Symbols:**

```
ffffffff815e73ee-ffffffff815e7454: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81615e3f)
Location: drivers/acpi/acpica/tbdata.c:969
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
**Symbols:**

```
ffffffff81615e3f-ffffffff81615f03: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_tb_install_and_load_table(acpi_physical_address address, u8 flags, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8162fcef)
Location: drivers/acpi/acpica/tbdata.c:969
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
**Symbols:**

```
ffffffff8162fcef-ffffffff8162fdb3: acpi_tb_install_and_load_table (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_table_header *table</code>
</li>
<li>
<b>Param reordered. </b>
<code>address, flags, override, table_index</code> ➡️ <code>address, flags, table, override, table_index</code>
</li>
</ul>
</details>
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
