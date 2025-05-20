# Function: <code>acpi_ut_evaluate_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff814a7b14)
Location: drivers/acpi/acpica/uteval.c:71
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_SUB
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
```
**Symbols:**

```
ffffffff814a7b14-ffffffff814a7caf: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff814f6e94)
Location: drivers/acpi/acpica/uteval.c:71
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff814f6e94-ffffffff814f7030: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff81519a57)
Location: drivers/acpi/acpica/uteval.c:71
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff81519a57-ffffffff81519bf3: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff8152a287)
Location: drivers/acpi/acpica/uteval.c:71
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff8152a287-ffffffff8152a423: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff81583337)
Location: drivers/acpi/acpica/uteval.c:71
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff81583337-ffffffff81583589: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff815ba4d4)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff815ba4d4-ffffffff815ba726: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff815d392e)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff815d392e-ffffffff815d3b80: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff816052ad)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff816052ad-ffffffff816054fd: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff81626757)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff81626757-ffffffff816269a7: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff816d2f07)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff816d2f07-ffffffff816d3157: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff816f0ee5)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff816f0ee5-ffffffff816f1135: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff816d2d8d)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff816d2d8d-ffffffff816d2fdd: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff8174a5d1)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff8174a5d1-ffffffff8174a821: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff8187ca7a)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff8187ca7a-ffffffff8187cce9: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff819c00a0)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff819c00a0-ffffffff819c031e: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff81a072a0)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff81a072a0-ffffffff81a0751e: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff81a52140)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff81a52140-ffffffff81a523f1: acpi_ut_evaluate_object (STB_GLOBAL)
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffff80001079bc70)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffff80001079bc70-ffff80001079be24: acpi_ut_evaluate_object (STB_GLOBAL)
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
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff815fefb9)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff815fefb9-ffffffff815ff152: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff815ea4b0)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff815ea4b0-ffffffff815ea644: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff8161aa37)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff8161aa37-ffffffff8161ac87: acpi_ut_evaluate_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ut_evaluate_object(struct acpi_namespace_node *prefix_node, const char *path, u32 expected_return_btypes, union acpi_operand_object **return_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/uteval.c (ffffffff816348e7)
Location: drivers/acpi/acpica/uteval.c:37
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_aei_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_crs_method_data
  - drivers/acpi/acpica/rsutils.c:acpi_rs_get_prt_method_data
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_power_methods
  - drivers/acpi/acpica/uteval.c:acpi_ut_execute_STA
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_numeric_object
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_UID
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_HID
```
**Symbols:**

```
ffffffff816348e7-ffffffff81634b37: acpi_ut_evaluate_object (STB_GLOBAL)
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
<code>char *path</code> ➡️ <code>const char *path</code>
</li>
</ul>
</details>
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
