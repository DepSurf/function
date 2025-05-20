# Function: <code>acpi_ut_delete_object_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff814a921b)
Location: drivers/acpi/acpica/utobject.c:419
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff814a921b-ffffffff814a9265: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff814f84b1)
Location: drivers/acpi/acpica/utobject.c:421
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff814f84b1-ffffffff814f84fb: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8151aebf)
Location: drivers/acpi/acpica/utobject.c:421
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_ref_count
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff8151aebf-ffffffff8151af09: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8152b6da)
Location: drivers/acpi/acpica/utobject.c:421
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff8152b6da-ffffffff8152b724: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff815857b5)
Location: drivers/acpi/acpica/utobject.c:421
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff815857b5-ffffffff81585857: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff815bc96b)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff815bc96b-ffffffff815bca0d: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff815d5db1)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff815d5db1-ffffffff815d5e53: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81607755)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81607755-ffffffff816077fb: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81628bf0)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81628bf0-ffffffff81628c96: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816d5499)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_create_method_mutex
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff816d5499-ffffffff816d553f: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816f3455)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_create_method_mutex
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff816f3455-ffffffff816f34fb: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816d5214)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff816d5214-ffffffff816d52ba: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8174cc3b)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff8174cc3b-ffffffff8174cce1: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8187f35f)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff8187f35f-ffffffff8187f412: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff819c3250)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff819c3250-ffffffff819c3320: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81a0a5f0)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81a0a5f0-ffffffff81a0a6c0: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81a55590)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81a55590-ffffffff81a55660: acpi_ut_delete_object_desc (STB_GLOBAL)
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
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffff80001079d628)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffff80001079d628-ffff80001079d694: acpi_ut_delete_object_desc (STB_GLOBAL)
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
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff816004be)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff816004be-ffffffff8160050a: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff815eb983)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff815eb983-ffffffff815eb9cf: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff8161ced0)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff8161ced0-ffffffff8161cf76: acpi_ut_delete_object_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_ut_delete_object_desc(union acpi_operand_object *object);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utobject.c (ffffffff81636d80)
Location: drivers/acpi/acpica/utobject.c:389
Inline: True
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
  - drivers/acpi/acpica/dsobject.c:acpi_ds_build_internal_buffer_obj
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
  - drivers/acpi/acpica/dsutils.c:acpi_ds_create_operand
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utdelete.c:acpi_ut_delete_internal_obj
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
```
**Symbols:**

```
ffffffff81636d80-ffffffff81636e26: acpi_ut_delete_object_desc (STB_GLOBAL)
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
