# Function: <code>acpi_ut_trace_str</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8158202b)
Location: drivers/acpi/acpica/utdebug.c:347
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff8158202b-ffffffff8158209f: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815b91e0)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff815b91e0-ffffffff815b9254: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff815d25b1)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff815d25b1-ffffffff815d2625: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81603ea9)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff81603ea9-ffffffff81603f1b: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81625353)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff81625353-ffffffff816253c5: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d1af5)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff816d1af5-ffffffff816d1b68: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816efad3)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff816efad3-ffffffff816efb46: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816d1938)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff816d1938-ffffffff816d19ab: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81749092)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff81749092-ffffffff81749105: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff8187b317)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff8187b317-ffffffff8187b39e: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff819be310)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff819be310-ffffffff819be3c5: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a05500)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff81a05500-ffffffff81a055b5: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81a503a0)
Location: drivers/acpi/acpica/utdebug.c:332
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff81a503a0-ffffffff81a50455: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff81619633)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff81619633-ffffffff816196a5: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ut_trace_str(u32 line_number, const char *function_name, const char *module_name, u32 component_id, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdebug.c (ffffffff816334e3)
Location: drivers/acpi/acpica/utdebug.c:327
Inline: False
Direct callers:
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_1R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_1T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_1A_0T_0R
  - drivers/acpi/acpica/exoparg1.c:acpi_ex_opcode_0A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_1T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_2T_1R
  - drivers/acpi/acpica/exoparg2.c:acpi_ex_opcode_2A_0T_0R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_1T_1R
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
  - drivers/acpi/acpica/exoparg6.c:acpi_ex_opcode_6A_0T_1R
  - drivers/acpi/acpica/utobject.c:acpi_ut_create_internal_object_dbg
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_explicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_implicit_strtoul64
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
**Symbols:**

```
ffffffff816334e3-ffffffff81633555: acpi_ut_trace_str (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
