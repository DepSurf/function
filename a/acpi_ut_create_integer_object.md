# Function: <code>acpi_ut_create_integer_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff814a9353)
Location: drivers/acpi/acpica/utobject.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff814a9353-ffffffff814a9387: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff814f85e5)
Location: drivers/acpi/acpica/utobject.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff814f85e5-ffffffff814f8619: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8151aff3)
Location: drivers/acpi/acpica/utobject.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8151aff3-ffffffff8151b027: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8152b80e)
Location: drivers/acpi/acpica/utobject.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8152b80e-ffffffff8152b842: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81585a4e)
Location: drivers/acpi/acpica/utobject.c:204
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff81585a4e-ffffffff81585ae6: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff815bcc04)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff815bcc04-ffffffff815bcc9c: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff815d604a)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff815d604a-ffffffff815d60e2: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816079f5)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff816079f5-ffffffff81607a8d: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81628e90)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff81628e90-ffffffff81628f28: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816d5739)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff816d5739-ffffffff816d57d1: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816f36f5)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff816f36f5-ffffffff816f378d: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816d54b1)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff816d54b1-ffffffff816d5549: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8174ced8)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff8174ced8-ffffffff8174cf70: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8187f621)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff8187f621-ffffffff8187f6c8: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff819c35b0)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff819c35b0-ffffffff819c365c: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81a0a940)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff81a0a940-ffffffff81a0aa01: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81a558e0)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_repair_null_element
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff81a558e0-ffffffff81a559a1: acpi_ut_create_integer_object (STB_GLOBAL)
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
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffff80001079d7c0)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffff80001079d7c0-ffff80001079d804: acpi_ut_create_integer_object (STB_GLOBAL)
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
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816005f3)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff816005f3-ffffffff81600627: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff815ebab8)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815ebab8-ffffffff815ebaec: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8161d170)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff8161d170-ffffffff8161d208: acpi_ut_create_integer_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_integer_object(u64 initial_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81637020)
Location: drivers/acpi/acpica/utobject.c:172
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmthdat.c:acpi_ds_method_data_get_value
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/exconvrt.c:acpi_ex_convert_to_integer
  - drivers/acpi/acpica/exfield.c:acpi_ex_read_data_from_field
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_integer
  - drivers/acpi/acpica/psparse.c:acpi_ps_parse_aml
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_set_method_data
```
**Symbols:**

```
ffffffff81637020-ffffffff816370b8: acpi_ut_create_integer_object (STB_GLOBAL)
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
