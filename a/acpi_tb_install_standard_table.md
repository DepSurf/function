# Function: <code>acpi_tb_install_standard_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff814a53d8)
Location: drivers/acpi/acpica/tbinstal.c:243
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff814a53d8-ffffffff814a55fd: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff814f4747)
Location: drivers/acpi/acpica/tbinstal.c:243
Inline: False
Direct callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff814f4747-ffffffff814f495e: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff81517355)
Location: drivers/acpi/acpica/tbinstal.c:180
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff81517355-ffffffff815175c0: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff81527b71)
Location: drivers/acpi/acpica/tbinstal.c:180
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff81527b71-ffffffff81527de0: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff8157f47f)
Location: drivers/acpi/acpica/tbinstal.c:131
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff8157f47f-ffffffff8157f64d: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff815b6677)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff815b6677-ffffffff815b6845: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff815cfa37)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff815cfa37-ffffffff815cfc02: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff816012c3)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff816012c3-ffffffff8160148c: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff8162276e)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff8162276e-ffffffff81622937: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff816ceda7)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff816ceda7-ffffffff816cef70: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff816ecdad)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff816ecdad-ffffffff816ecf76: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff816cec73)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff816cec73-ffffffff816cee3c: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff817462e3)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff817462e3-ffffffff817464ac: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, struct acpi_table_header *table, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff8187818c)
Location: drivers/acpi/acpica/tbinstal.c:99
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_physical_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff8187818c-ffffffff8187837f: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, struct acpi_table_header *table, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff819ba480)
Location: drivers/acpi/acpica/tbinstal.c:99
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_physical_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff819ba480-ffffffff819ba6b1: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, struct acpi_table_header *table, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff81a015e0)
Location: drivers/acpi/acpica/tbinstal.c:99
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_physical_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff81a015e0-ffffffff81a01811: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, struct acpi_table_header *table, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff81a4c460)
Location: drivers/acpi/acpica/tbinstal.c:99
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_physical_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff81a4c460-ffffffff81a4c691: acpi_tb_install_standard_table (STB_GLOBAL)
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
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffff800010797c8c)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffff800010797c8c-ffff800010797e04: acpi_tb_install_standard_table (STB_GLOBAL)
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
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff815fc8c3)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff815fc8c3-ffffffff815fca16: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff815e7dee)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff815e7dee-ffffffff815e7f41: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff81616a4e)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff81616a4e-ffffffff81616c17: acpi_tb_install_standard_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_tb_install_standard_table(acpi_physical_address address, u8 flags, u8 reload, u8 override, u32 *table_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbinstal.c (ffffffff816308fe)
Location: drivers/acpi/acpica/tbinstal.c:97
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_install_and_load_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfload.c:acpi_install_table
```
**Symbols:**

```
ffffffff816308fe-ffffffff81630ac7: acpi_tb_install_standard_table (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_table_header *table</code>
</li>
<li>
<b>Param reordered. </b>
<code>address, flags, reload, override, table_index</code> ➡️ <code>address, flags, table, reload, override, table_index</code>
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
