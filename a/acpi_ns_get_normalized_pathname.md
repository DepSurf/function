# Function: <code>acpi_ns_get_normalized_pathname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff8149d4da)
Location: drivers/acpi/acpica/nsnames.c:274
Inline: False
Direct callers:
  - drivers/acpi/acpica/exdebug.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/exdebug.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
```
**Symbols:**

```
ffffffff8149d4da-ffffffff8149d576: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff814ec720)
Location: drivers/acpi/acpica/nsnames.c:276
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffffffff814ec720-ffffffff814ec7bc: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff8150efe1)
Location: drivers/acpi/acpica/nsnames.c:321
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffffffff8150efe1-ffffffff8150f07d: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff8151f6b9)
Location: drivers/acpi/acpica/nsnames.c:318
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffffffff8151f6b9-ffffffff8151f753: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff81572467)
Location: drivers/acpi/acpica/nsnames.c:325
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff81572467-ffffffff81572587: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff815a91f2)
Location: drivers/acpi/acpica/nsnames.c:293
Inline: False
Direct callers:
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff815a91f2-ffffffff815a9332: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff815c2093)
Location: drivers/acpi/acpica/nsnames.c:293
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff815c2093-ffffffff815c21d3: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff815f3a61)
Location: drivers/acpi/acpica/nsnames.c:293
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff815f3a61-ffffffff815f3ba9: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff81614f00)
Location: drivers/acpi/acpica/nsnames.c:293
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff81614f00-ffffffff81615048: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff816c141f)
Location: drivers/acpi/acpica/nsnames.c:289
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff816c141f-ffffffff816c1567: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff816def87)
Location: drivers/acpi/acpica/nsnames.c:289
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff816def87-ffffffff816df0cf: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff816c0e73)
Location: drivers/acpi/acpica/nsnames.c:289
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff816c0e73-ffffffff816c0fbb: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff81738160)
Location: drivers/acpi/acpica/nsnames.c:289
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff81738160-ffffffff817382a8: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff818694d2)
Location: drivers/acpi/acpica/nsnames.c:289
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff818694d2-ffffffff81869625: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff819a8310)
Location: drivers/acpi/acpica/nsnames.c:289
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff819a8310-ffffffff819a8491: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff819ef000)
Location: drivers/acpi/acpica/nsnames.c:289
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff819ef000-ffffffff819ef181: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff81a39df0)
Location: drivers/acpi/acpica/nsnames.c:289
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff81a39df0-ffffffff81a39f71: acpi_ns_get_normalized_pathname (STB_GLOBAL)
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
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffff80001078dae8)
Location: drivers/acpi/acpica/nsnames.c:293
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffff80001078dae8-ffff80001078db84: acpi_ns_get_normalized_pathname (STB_GLOBAL)
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
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff815f3a83)
Location: drivers/acpi/acpica/nsnames.c:293
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffffffff815f3a83-ffffffff815f3afc: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff815df007)
Location: drivers/acpi/acpica/nsnames.c:293
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
```
**Symbols:**

```
ffffffff815df007-ffffffff815df080: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff816091e0)
Location: drivers/acpi/acpica/nsnames.c:293
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff816091e0-ffffffff81609328: acpi_ns_get_normalized_pathname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *acpi_ns_get_normalized_pathname(struct acpi_namespace_node *node, u8 no_trailing);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsnames.c (ffffffff81623090)
Location: drivers/acpi/acpica/nsnames.c:293
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_stop_trace_method
  - drivers/acpi/acpica/extrace.c:acpi_ex_start_trace_method
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_one_object_path
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_device
  - drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname
  - drivers/acpi/acpica/nsnames.c:acpi_ns_get_external_pathname
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utaddress.c:acpi_ut_check_address_range
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_non_root_handlers
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_predefined_names
```
**Symbols:**

```
ffffffff81623090-ffffffff816231d8: acpi_ns_get_normalized_pathname (STB_GLOBAL)
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
