# Function: <code>acpi_ns_get_secondary_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8149d76a)
Location: drivers/acpi/acpica/nsobject.c:313
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
```
**Symbols:**

```
ffffffff8149d76a-ffffffff8149d797: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff814ec9b0)
Location: drivers/acpi/acpica/nsobject.c:313
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
```
**Symbols:**

```
ffffffff814ec9b0-ffffffff814ec9e2: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8150f271)
Location: drivers/acpi/acpica/nsobject.c:313
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
```
**Symbols:**

```
ffffffff8150f271-ffffffff8150f2a3: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff8151f92c)
Location: drivers/acpi/acpica/nsobject.c:313
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
```
**Symbols:**

```
ffffffff8151f92c-ffffffff8151f955: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81572a29)
Location: drivers/acpi/acpica/nsobject.c:313
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff81572a29-ffffffff81572ab9: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815a9996)
Location: drivers/acpi/acpica/nsobject.c:277
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff815a9996-ffffffff815a9a26: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815c283e)
Location: drivers/acpi/acpica/nsobject.c:277
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff815c283e-ffffffff815c28ce: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815f4239)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff815f4239-ffffffff815f42d0: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816156d8)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff816156d8-ffffffff8161576f: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816c1bf9)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff816c1bf9-ffffffff816c1c90: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816df761)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff816df761-ffffffff816df7f8: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816c164c)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff816c164c-ffffffff816c16e3: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81738939)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff81738939-ffffffff817389d0: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81869d36)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff81869d36-ffffffff81869dd5: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff819a8de0)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff819a8de0-ffffffff819a8e98: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff819efc90)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff819efc90-ffffffff819efd48: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81a3aa80)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff81a3aa80-ffffffff81a3ab38: acpi_ns_get_secondary_object (STB_GLOBAL)
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
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffff80001078e004)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
```
**Symbols:**

```
ffff80001078e004-ffff80001078e058: acpi_ns_get_secondary_object (STB_GLOBAL)
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
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815f3ec0)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
```
**Symbols:**

```
ffffffff815f3ec0-ffffffff815f3ee9: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff815df444)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
```
**Symbols:**

```
ffffffff815df444-ffffffff815df46d: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff816099b8)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff816099b8-ffffffff81609a4f: acpi_ns_get_secondary_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
union acpi_operand_object *acpi_ns_get_secondary_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsobject.c (ffffffff81623868)
Location: drivers/acpi/acpica/nsobject.c:281
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_deactivate_mem_region
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_region_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_bank_field_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_get_buffer_field_arguments
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_address_space_dispatch
  - drivers/acpi/acpica/excreate.c:acpi_ex_create_region
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/dbstats.c:acpi_db_enumerate_object
```
**Symbols:**

```
ffffffff81623868-ffffffff816238ff: acpi_ns_get_secondary_object (STB_GLOBAL)
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
