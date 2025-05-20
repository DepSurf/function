# Function: <code>acpi_tb_init_generic_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_tb_init_generic_address(struct acpi_generic_address *generic_address, u8 space_id, u8 byte_width, u64 address, char *register_name, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff814a4a07)
Location: drivers/acpi/acpica/tbfadt.c:192
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
**Symbols:**

```
ffffffff814a4a07-ffffffff814a4a79: acpi_tb_init_generic_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_tb_init_generic_address(struct acpi_generic_address *generic_address, u8 space_id, u8 byte_width, u64 address, const char *register_name, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff814f3d46)
Location: drivers/acpi/acpica/tbfadt.c:192
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
**Symbols:**

```
ffffffff814f3d46-ffffffff814f3db8: acpi_tb_init_generic_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff81516cab)
Location: drivers/acpi/acpica/tbfadt.c:192
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff815274b3)
Location: drivers/acpi/acpica/tbfadt.c:192
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff8157ec9d)
Location: drivers/acpi/acpica/tbfadt.c:192
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff815b5e7a)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff815cf236)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff81600aba)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff81621f65)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_tb_init_generic_address(struct acpi_generic_address *generic_address, u8 space_id, u8 byte_width, u64 address, const char *register_name, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff816ce356)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_setup_fadt_registers
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
```
**Symbols:**

```
ffffffff816ce356-ffffffff816ce3c6: acpi_tb_init_generic_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_tb_init_generic_address(struct acpi_generic_address *generic_address, u8 space_id, u8 byte_width, u64 address, const char *register_name, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff816ec35c)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_setup_fadt_registers
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
```
**Symbols:**

```
ffffffff816ec35c-ffffffff816ec3cc: acpi_tb_init_generic_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_tb_init_generic_address(struct acpi_generic_address *generic_address, u8 space_id, u8 byte_width, u64 address, const char *register_name, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff816ce235)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
**Symbols:**

```
ffffffff816ce235-ffffffff816ce2a5: acpi_tb_init_generic_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_tb_init_generic_address(struct acpi_generic_address *generic_address, u8 space_id, u8 byte_width, u64 address, const char *register_name, u8 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff81745705)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
**Symbols:**

```
ffffffff81745705-ffffffff81745775: acpi_tb_init_generic_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff8187773f)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff819b95b2)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff81a007f5)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff81a4b675)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_convert_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffff80001079759c)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff815fc1e9)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff815e7714)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff81616245)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbfadt.c (ffffffff816300f5)
Location: drivers/acpi/acpica/tbfadt.c:158
Inline: True
Inline callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_create_local_fadt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *register_name</code> ➡️ <code>const char *register_name</code>
</li>
</ul>
</details>
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
</ul>
