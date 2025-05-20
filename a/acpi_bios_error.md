# Function: <code>acpi_bios_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff814aa71a)
Location: drivers/acpi/acpica/utxferror.c:210
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff814aa71a-ffffffff814aa7c1: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff814f9970)
Location: drivers/acpi/acpica/utxferror.c:210
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff814f9970-ffffffff814f9a17: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8151c4f3)
Location: drivers/acpi/acpica/utxferror.c:210
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff8151c4f3-ffffffff8151c59a: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8152ccfe)
Location: drivers/acpi/acpica/utxferror.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_install_standard_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff8152ccfe-ffffffff8152cda5: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81587a59)
Location: drivers/acpi/acpica/utxferror.c:206
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81587a59-ffffffff81587b00: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815bebe5)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff815bebe5-ffffffff815bec87: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815d804c)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff815d804c-ffffffff815d80ee: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81609a6c)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81609a6c-ffffffff81609b10: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8162af0d)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff8162af0d-ffffffff8162afb1: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d76f6)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff816d76f6-ffffffff816d779a: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816f569c)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff816f569c-ffffffff816f5740: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d7539)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff816d7539-ffffffff816d75dd: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8174f0a5)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff8174f0a5-ffffffff8174f149: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81881acd)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81881acd-ffffffff81881b94: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff819c6590)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff819c6590-ffffffff819c6660: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a0d990)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81a0d990-ffffffff81a0da60: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a58990)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81a58990-ffffffff81a58a60: acpi_bios_error (STB_GLOBAL)
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
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffff80001079f620)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffff80001079f620-ffff80001079f6e4: acpi_bios_error (STB_GLOBAL)
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
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81601e06)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff81601e06-ffffffff81601eaa: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815ed2bc)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff815ed2bc-ffffffff815ed360: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8161f1ed)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff8161f1ed-ffffffff8161f291: acpi_bios_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_bios_error(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8163909d)
Location: drivers/acpi/acpica/utxferror.c:170
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbutils.c:acpi_tb_parse_root_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_check_dsdt_header
  - drivers/acpi/acpica/tbxfroot.c:acpi_find_root_pointer
```
**Symbols:**

```
ffffffff8163909d-ffffffff81639141: acpi_bios_error (STB_GLOBAL)
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
