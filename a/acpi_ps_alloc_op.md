# Function: <code>acpi_ps_alloc_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff814a23f7)
Location: drivers/acpi/acpica/psutils.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff814a23f7-ffffffff814a2469: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff814f1724)
Location: drivers/acpi/acpica/psutils.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff814f1724-ffffffff814f1796: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff81514185)
Location: drivers/acpi/acpica/psutils.c:116
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff81514185-ffffffff815141f7: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff81524921)
Location: drivers/acpi/acpica/psutils.c:117
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff81524921-ffffffff8152499e: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff8157a596)
Location: drivers/acpi/acpica/psutils.c:117
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff8157a596-ffffffff8157a62b: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff815b168a)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff815b168a-ffffffff815b171f: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff815ca7ca)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff815ca7ca-ffffffff815ca85f: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff815fbf79)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff815fbf79-ffffffff815fc010: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff8161d423)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff8161d423-ffffffff8161d4ba: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff816c99ac)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff816c99ac-ffffffff816c9a43: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff816e79d2)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff816e79d2-ffffffff816e7a69: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff816c9895)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff816c9895-ffffffff816c992c: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff81740c37)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff81740c37-ffffffff81740cce: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff818725e4)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff818725e4-ffffffff81872687: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff819b33c0)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff819b33c0-ffffffff819b34e7: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff819fa2c0)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff819fa2c0-ffffffff819fa3e7: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff81a45110)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_field
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff81a45110-ffffffff81a45237: acpi_ps_alloc_op (STB_GLOBAL)
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
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffff800010793d68)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffff800010793d68-ffff800010793e10: acpi_ps_alloc_op (STB_GLOBAL)
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
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff815f91c7)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff815f91c7-ffffffff815f9244: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff815e4701)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff815e4701-ffffffff815e477e: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff81611703)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff81611703-ffffffff8161179a: acpi_ps_alloc_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
union acpi_parse_object *acpi_ps_alloc_op(u16 opcode, u8 *aml);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/psutils.c (ffffffff8162b5b3)
Location: drivers/acpi/acpica/psutils.c:85
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dswload.c:acpi_ds_load1_begin_op
  - drivers/acpi/acpica/dswload2.c:acpi_ds_load2_begin_op
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_arg
  - drivers/acpi/acpica/psargs.c:acpi_ps_get_next_namepath
  - drivers/acpi/acpica/psobject.c:acpi_ps_create_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psparse.c:acpi_ps_complete_this_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_create_scope_op
```
**Symbols:**

```
ffffffff8162b5b3-ffffffff8162b64a: acpi_ps_alloc_op (STB_GLOBAL)
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
