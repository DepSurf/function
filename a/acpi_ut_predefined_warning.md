# Function: <code>acpi_ut_predefined_warning</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u8 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff814a7764)
Location: drivers/acpi/acpica/uterror.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff814a7764-ffffffff814a780c: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u8 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff814f6ae4)
Location: drivers/acpi/acpica/uterror.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff814f6ae4-ffffffff814f6b8c: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u8 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff815196a7)
Location: drivers/acpi/acpica/uterror.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff815196a7-ffffffff8151974f: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u8 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff81529ed7)
Location: drivers/acpi/acpica/uterror.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff81529ed7-ffffffff81529f7f: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u8 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff81582f87)
Location: drivers/acpi/acpica/uterror.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff81582f87-ffffffff8158302f: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u8 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff815ba145)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff815ba145-ffffffff815ba1e9: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u8 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff815d359f)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff815d359f-ffffffff815d3643: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u8 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff81604f22)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff81604f22-ffffffff81604fc4: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff816263cc)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff816263cc-ffffffff8162646e: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff816d2b7c)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff816d2b7c-ffffffff816d2c1e: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff816f0b5a)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff816f0b5a-ffffffff816f0bfc: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff816d2a04)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff816d2a04-ffffffff816d2aa6: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff8174a248)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff8174a248-ffffffff8174a2ea: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff8187c650)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff8187c650-ffffffff8187c717: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff819bfbd0)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff819bfbd0-ffffffff819bfc9c: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff81a06dd0)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff81a06dd0-ffffffff81a06e9c: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff81a51c70)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_custom_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff81a51c70-ffffffff81a51d3c: acpi_ut_predefined_warning (STB_GLOBAL)
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
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffff80001079b7e4)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffff80001079b7e4-ffff80001079b8c4: acpi_ut_predefined_warning (STB_GLOBAL)
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
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff815fec2e)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff815fec2e-ffffffff815fecd0: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff815ea125)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff815ea125-ffffffff815ea1c7: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff8161a6ac)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff8161a6ac-ffffffff8161a74e: acpi_ut_predefined_warning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ut_predefined_warning(const char *module_name, u32 line_number, char *pathname, u16 node_flags, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uterror.c (ffffffff8163455c)
Location: drivers/acpi/acpica/uterror.c:39
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_count
  - drivers/acpi/acpica/nsarguments.c:acpi_ns_check_argument_types
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nspredef.c:acpi_ns_check_object_type
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package_list
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsprepkg.c:acpi_ns_check_package
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair.c:acpi_ns_simple_repair
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PSS
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_PRT
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_HID
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_CST
  - drivers/acpi/acpica/nsrepair2.c:acpi_ns_repair_FDE
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
**Symbols:**

```
ffffffff8163455c-ffffffff816345fe: acpi_ut_predefined_warning (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 node_flags</code> ➡️ <code>u16 node_flags</code>
</li>
</ul>
</details>
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
