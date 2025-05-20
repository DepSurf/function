# Function: <code>acpi_ns_walk_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff8149f4ef)
Location: drivers/acpi/acpica/nswalk.c:184
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
**Symbols:**

```
ffffffff8149f4ef-ffffffff8149f682: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff814ee7fb)
Location: drivers/acpi/acpica/nswalk.c:184
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
**Symbols:**

```
ffffffff814ee7fb-ffffffff814ee998: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff8151128b)
Location: drivers/acpi/acpica/nswalk.c:184
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
**Symbols:**

```
ffffffff8151128b-ffffffff81511428: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff8152195a)
Location: drivers/acpi/acpica/nswalk.c:184
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
```
**Symbols:**

```
ffffffff8152195a-ffffffff81521af4: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff81575cd9)
Location: drivers/acpi/acpica/nswalk.c:184
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff81575cd9-ffffffff81575f51: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff815acc4b)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff815acc4b-ffffffff815acec6: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff815c5c42)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_table_op
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff815c5c42-ffffffff815c5ebd: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff815f7528)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff815f7528-ffffffff815f77aa: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff816189ce)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816189ce-ffffffff81618c50: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff816c4ed5)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816c4ed5-ffffffff816c5157: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff816e2f19)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816e2f19-ffffffff816e319b: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff816c4df5)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff816c4df5-ffffffff816c5070: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff8173c15a)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff8173c15a-ffffffff8173c3d5: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff8186d86c)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff8186d86c-ffffffff8186db4a: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff819ad600)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff819ad600-ffffffff819ad96a: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff819f44d0)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff819f44d0-ffffffff819f482e: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff81a3f2f0)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_walk_namespace
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff81a3f2f0-ffffffff81a3f64e: acpi_ns_walk_namespace (STB_GLOBAL)
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffff800010790714)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
```
**Symbols:**

```
ffff800010790714-ffff8000107908e8: acpi_ns_walk_namespace (STB_GLOBAL)
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
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff815f5f2e)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
```
**Symbols:**

```
ffffffff815f5f2e-ffffffff815f60de: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff815e1488)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
```
**Symbols:**

```
ffffffff815e1488-ffffffff815e1638: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff8160ccae)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff8160ccae-ffffffff8160cf30: acpi_ns_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ns_walk_namespace(acpi_object_type type, acpi_handle start_node, u32 max_depth, u32 flags, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nswalk.c (ffffffff81626b5e)
Location: drivers/acpi/acpica/nswalk.c:150
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsinit.c:acpi_ds_initialize_objects
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_update_gpes
  - drivers/acpi/acpica/evhandler.c:acpi_ev_install_space_handler
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_methods
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_object_paths
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_objects
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
  - drivers/acpi/acpica/nsxfeval.c:acpi_get_devices
  - drivers/acpi/acpica/dbstats.c:acpi_db_display_statistics
```
**Symbols:**

```
ffffffff81626b5e-ffffffff81626de0: acpi_ns_walk_namespace (STB_GLOBAL)
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
