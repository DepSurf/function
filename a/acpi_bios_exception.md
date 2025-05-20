# Function: <code>acpi_bios_exception</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81609c6f)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff81609c6f-ffffffff81609d2a: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8162b110)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff8162b110-ffffffff8162b1cb: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d78f9)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff816d78f9-ffffffff816d79b4: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816f589f)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff816f589f-ffffffff816f595a: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d773c)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff816d773c-ffffffff816d77f7: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8174f2a8)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff8174f2a8-ffffffff8174f363: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81881d39)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff81881d39-ffffffff81881e17: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff819c6850)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff819c6850-ffffffff819c693a: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a0dc50)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff81a0dc50-ffffffff81a0dd3a: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a58c50)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff81a58c50-ffffffff81a58d3a: acpi_bios_exception (STB_GLOBAL)
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
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffff80001079f894)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffff80001079f894-ffff80001079f980: acpi_bios_exception (STB_GLOBAL)
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
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81602009)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff81602009-ffffffff816020c4: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815ed4bf)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff815ed4bf-ffffffff815ed57a: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8161f3f0)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff8161f3f0-ffffffff8161f4ab: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_bios_exception(const char *module_name, u32 line_number, acpi_status status, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816392a0)
Location: drivers/acpi/acpica/utxferror.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_init_buffer_field
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
```
**Symbols:**

```
ffffffff816392a0-ffffffff8163935b: acpi_bios_exception (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
