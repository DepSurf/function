# Function: <code>acpi_warning</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff814aa5e5)
Location: drivers/acpi/acpica/utxferror.c:144
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff814aa5e5-ffffffff814aa68c: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff814f9833)
Location: drivers/acpi/acpica/utxferror.c:145
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff814f9833-ffffffff814f98da: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8151c3b6)
Location: drivers/acpi/acpica/utxferror.c:145
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff8151c3b6-ffffffff8151c45d: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8152cbc1)
Location: drivers/acpi/acpica/utxferror.c:145
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff8152cbc1-ffffffff8152cc68: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8158791c)
Location: drivers/acpi/acpica/utxferror.c:145
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff8158791c-ffffffff815879c3: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815beab0)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff815beab0-ffffffff815beb52: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815d7f17)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/psloop.c:acpi_ps_parse_loop
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff815d7f17-ffffffff815d7fb9: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81609933)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff81609933-ffffffff816099d7: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8162add4)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff8162add4-ffffffff8162ae78: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d75bd)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff816d75bd-ffffffff816d7661: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816f5563)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff816f5563-ffffffff816f5607: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff816d7400)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff816d7400-ffffffff816d74a4: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8174ef6c)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff8174ef6c-ffffffff8174f010: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8188194e)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff8188194e-ffffffff81881a15: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff819c63e0)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff819c63e0-ffffffff819c64b0: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a0d7e0)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff81a0d7e0-ffffffff81a0d8b0: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81a587e0)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_remove_fixed_event_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_fixed_event_handler
  - drivers/acpi/acpica/evxfevnt.c:acpi_enable
  - drivers/acpi/acpica/exconfig.c:acpi_ex_unload_table
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_do_stall
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff81a587e0-ffffffff81a588b0: acpi_warning (STB_GLOBAL)
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
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffff80001079f4b4)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
```
**Symbols:**

```
ffff80001079f4b4-ffff80001079f578: acpi_warning (STB_GLOBAL)
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
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81601ccd)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff81601ccd-ffffffff81601d71: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff815ed183)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff815ed183-ffffffff815ed227: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff8161f0b4)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff8161f0b4-ffffffff8161f158: acpi_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_warning(const char *module_name, u32 line_number, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utxferror.c (ffffffff81638f64)
Location: drivers/acpi/acpica/utxferror.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_init_object_from_op
  - drivers/acpi/acpica/dsopcode.c:acpi_ds_eval_region_operands
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/dswscope.c:acpi_ds_scope_stack_push
  - drivers/acpi/acpica/evglock.c:acpi_ev_release_global_lock
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/exstoren.c:acpi_ex_store_object_to_object
  - drivers/acpi/acpica/exutils.c:acpi_ex_eisa_id_to_string
  - drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register
  - drivers/acpi/acpica/nsaccess.c:acpi_ns_lookup
  - drivers/acpi/acpica/nsobject.c:acpi_ns_get_attached_object
  - drivers/acpi/acpica/nsutils.c:acpi_ns_opens_scope
  - drivers/acpi/acpica/nsutils.c:acpi_ns_local
  - drivers/acpi/acpica/nsutils.c:acpi_ns_get_type
  - drivers/acpi/acpica/rslist.c:acpi_rs_convert_aml_to_resources
  - drivers/acpi/acpica/rsmisc.c:acpi_rs_convert_aml_to_resource
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_get_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/utstring.c:acpi_ut_repair_name
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
  - drivers/acpi/acpica/utxfinit.c:acpi_enable_subsystem
```
**Symbols:**

```
ffffffff81638f64-ffffffff81639008: acpi_warning (STB_GLOBAL)
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
