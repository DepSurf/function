# Function: <code>acpi_ex_access_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff814955c6)
Location: drivers/acpi/acpica/exfldio.c:230
Inline: True
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
```
**Symbols:**

```
ffffffff814955c6-ffffffff81495833: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff814e45d2)
Location: drivers/acpi/acpica/exfldio.c:232
Inline: True
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
```
**Symbols:**

```
ffffffff814e45d2-ffffffff814e4837: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff81506e26)
Location: drivers/acpi/acpica/exfldio.c:232
Inline: True
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
```
**Symbols:**

```
ffffffff81506e26-ffffffff8150708b: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff81517418)
Location: drivers/acpi/acpica/exfldio.c:232
Inline: True
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
```
**Symbols:**

```
ffffffff81517418-ffffffff81517674: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff81564017)
Location: drivers/acpi/acpica/exfldio.c:232
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
```
**Symbols:**

```
ffffffff81564017-ffffffff815644e0: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff8159ad5e)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
```
**Symbols:**

```
ffffffff8159ad5e-ffffffff8159b237: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff815b3250)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff815b3250-ffffffff815b3729: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff815e4d6c)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff815e4d6c-ffffffff815e5259: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff81606101)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff81606101-ffffffff816065ee: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff816b26a5)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff816b26a5-ffffffff816b2902: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff816cffd0)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff816cffd0-ffffffff816d022d: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff816b1f59)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff816b1f59-ffffffff816b21b8: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff81728de2)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff81728de2-ffffffff81729041: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff8185963f)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff8185963f-ffffffff818598b0: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff819951a0)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff819951a0-ffffffff8199542e: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff819dbdc0)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff819dbdc0-ffffffff819dc04e: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff81a26ab0)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff81a26ab0-ffffffff81a26d3e: acpi_ex_access_region (STB_GLOBAL)
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
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffff800010785178)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: True
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffff800010785178-ffff8000107853e4: acpi_ex_access_region (STB_GLOBAL)
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
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff815eb1e1)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: True
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff815eb1e1-ffffffff815eb436: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff815d67ff)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: True
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff815d67ff-ffffffff815d6a54: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff815fa3e1)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff815fa3e1-ffffffff815fa8ce: acpi_ex_access_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ex_access_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset, u64 *value, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff81614291)
Location: drivers/acpi/acpica/exfldio.c:198
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfield.c:acpi_ex_write_data_to_field
  - drivers/acpi/acpica/exfldio.c:acpi_ex_field_datum_io
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_serial_bus
  - drivers/acpi/acpica/exserial.c:acpi_ex_write_gpio
  - drivers/acpi/acpica/exserial.c:acpi_ex_read_gpio
```
**Symbols:**

```
ffffffff81614291-ffffffff8161477e: acpi_ex_access_region (STB_GLOBAL)
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
