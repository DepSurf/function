# Function: <code>acpi_ut_create_internal_object_dbg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff814a9265)
Location: drivers/acpi/acpica/utobject.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff814a9265-ffffffff814a92ee: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff814f84fb)
Location: drivers/acpi/acpica/utobject.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff814f84fb-ffffffff814f8582: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8151af09)
Location: drivers/acpi/acpica/utobject.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff8151af09-ffffffff8151af90: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8152b724)
Location: drivers/acpi/acpica/utobject.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff8152b724-ffffffff8152b7ab: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81585857)
Location: drivers/acpi/acpica/utobject.c:86
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81585857-ffffffff8158596e: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff815bca0d)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff815bca0d-ffffffff815bcb24: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff815d5e53)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff815d5e53-ffffffff815d5f6a: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816077fb)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff816077fb-ffffffff81607914: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81628c96)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81628c96-ffffffff81628daf: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816d553f)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_create_method_mutex
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff816d553f-ffffffff816d5658: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816f34fb)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_create_method_mutex
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff816f34fb-ffffffff816f3614: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816d52ba)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff816d52ba-ffffffff816d53d0: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8174cce1)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff8174cce1-ffffffff8174cdf7: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8187f412)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff8187f412-ffffffff8187f532: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff819c3330)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff819c3330-ffffffff819c3462: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81a0a6d0)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81a0a6d0-ffffffff81a0a7fd: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81a55670)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_notify_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_install_gpe_block
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nsxfname.c:acpi_install_method
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_esimple_to_isimple
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81a55670-ffffffff81a5579d: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
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
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffff80001079d694)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffff80001079d694-ffff80001079d750: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
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
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8160050a)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff8160050a-ffffffff8160058f: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff815eb9cf)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/exconfig.c:acpi_ex_add_table
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff815eb9cf-ffffffff815eba54: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8161cf76)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff8161cf76-ffffffff8161d08f: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ut_create_internal_object_dbg(const char *module_name, u32 line_number, u32 component_id, acpi_object_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81636e26)
Location: drivers/acpi/acpica/utobject.c:53
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsfield.c:acpi_ds_create_buffer_field
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_object
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_method
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_power_resource
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_processor
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_mutex
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_event
  - drivers/acpi/acpica/exmisc.c:acpi_ex_get_object_reference
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_root_initialize
  - drivers/acpi/acpica/nsconvert.c:acpi_ns_convert_to_reference
  - drivers/acpi/acpica/nsobject.c:acpi_ns_attach_data
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_iobject_to_iobject
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_ielement_to_ielement
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_eobject_to_iobject
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_string_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_buffer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_integer_object
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_package_object
  - drivers/acpi/acpica/utosi.c:acpi_ut_osi_implementation
```
**Symbols:**

```
ffffffff81636e26-ffffffff81636f3f: acpi_ut_create_internal_object_dbg (STB_GLOBAL)
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
