# Function: <code>kstrdup_const</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811abc80)
Location: mm/util.c:69
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:kernfs_rename_ns
  - lib/kobject.c:kobject_rename
  - lib/dynamic_debug.c:ddebug_add_module
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_class.c:alloc_fw_cache_entry
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff811abc80-ffffffff811abca5: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4700)
Location: mm/util.c:69
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kobject.c:kobject_rename
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - lib/dynamic_debug.c:ddebug_add_module
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_class.c:alloc_fw_cache_entry
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff811c4700-ffffffff811c4726: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d47f0)
Location: mm/util.c:69
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kobject.c:kobject_rename
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - lib/dynamic_debug.c:ddebug_add_module
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_class.c:alloc_fw_cache_entry
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff811d47f0-ffffffff811d4816: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd5a0)
Location: mm/util.c:72
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - lib/dynamic_debug.c:ddebug_add_module
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_class.c:alloc_fw_cache_entry
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:assign_firmware_buf
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff811dd5a0-ffffffff811dd5c7: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f3020)
Location: mm/util.c:72
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - lib/dynamic_debug.c:ddebug_add_module
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_class.c:alloc_fw_cache_entry
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:assign_firmware_buf
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff811f3020-ffffffff811f3047: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214310)
Location: mm/util.c:72
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - lib/dynamic_debug.c:ddebug_add_module
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:alloc_fw_cache_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff81214310-ffffffff81214336: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812271e0)
Location: mm/util.c:65
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - lib/dynamic_debug.c:ddebug_add_module
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:alloc_fw_cache_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff812271e0-ffffffff81227206: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81236ce0)
Location: mm/util.c:70
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:alloc_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:alloc_fw_cache_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff81236ce0-ffffffff81236d06: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81244ea0)
Location: mm/util.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:alloc_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:alloc_fw_cache_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff81244ea0-ffffffff81244ec6: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81272b50)
Location: mm/util.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:create_new_subsystem
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - lib/kobject.c:kobject_rename
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffffffff81272b50-ffffffff81272b76: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d200)
Location: mm/util.c:78
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:create_new_subsystem
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - lib/kobject.c:kobject_rename
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_add_cells_from_table
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff8127d200-ffffffff8127d226: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282390)
Location: mm/util.c:78
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - lib/kobject.c:kobject_rename
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff81282390-ffffffff812823b6: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0400)
Location: mm/util.c:78
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - lib/kobject.c:kobject_rename
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff812c0400-ffffffff812c0426: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131ced0)
Location: mm/util.c:79
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - lib/kobject.c:kobject_rename
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:fw_add_devm_name
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
  - drivers/hte/hte.c:hte_init_line_attr
```
**Symbols:**

```
ffffffff8131ced0-ffffffff8131cf06: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81390fa0)
Location: mm/util.c:79
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:fw_add_devm_name
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
  - drivers/hte/hte.c:hte_init_line_attr
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff81390fa0-ffffffff81390fd6: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c38b0)
Location: mm/util.c:80
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:fw_add_devm_name
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/leds/led-class.c:led_get
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_one_cell
  - drivers/hte/hte.c:hte_init_line_attr
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff813c38b0-ffffffff813c38e6: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ee470)
Location: mm/util.c:80
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:parse_unary
  - kernel/trace/trace_events_hist.c:init_var_ref
  - kernel/trace/trace_events_hist.c:create_hist_field
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/tracefs/event_inode.c:eventfs_create_dir
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:alloc_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:fw_add_devm_name
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/gpu/drm/drm_managed.c:drmm_kmalloc
  - drivers/gpu/drm/drm_managed.c:__drmm_add_action
  - drivers/leds/led-class.c:led_get
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_one_cell
  - drivers/hte/hte.c:hte_init_line_attr
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff813ee470-ffffffff813ee4a6: kstrdup_const (STB_GLOBAL)
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
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d7e70)
Location: mm/util.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pinctrl/devicetree.c:dt_remember_or_free_map
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:alloc_clk
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:alloc_fw_cache_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffff8000102d7e70-ffff8000102d7ed4: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff2e0)
Location: mm/util.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pinctrl/devicetree.c:dt_remember_or_free_map
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:alloc_clk
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:alloc_fw_cache_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
c04ff2e0-c04ff31c: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000397960)
Location: mm/util.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pinctrl/devicetree.c:dt_remember_or_free_map
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:alloc_fw_cache_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
c000000000397960-c00000000039799c: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f2700)
Location: mm/util.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/pinctrl/devicetree.c:dt_remember_or_free_map
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:alloc_clk
  - drivers/regulator/core.c:create_regulator
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffe0001f2700-ffffffe0001f274c: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d4f0)
Location: mm/util.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:alloc_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:alloc_fw_cache_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff8123d4f0-ffffffff8123d516: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812304f0)
Location: mm/util.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:alloc_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:alloc_fw_cache_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff812304f0-ffffffff81230516: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b290)
Location: mm/util.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:alloc_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:alloc_fw_cache_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff8123b290-ffffffff8123b2b6: kstrdup_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *kstrdup_const(const char *s, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124a9a0)
Location: mm/util.c:77
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kasprintf.c:kvasprintf_const
  - lib/kasprintf.c:kvasprintf_const
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:alloc_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/regulator/core.c:create_regulator
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:alloc_fw_cache_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_info_to_nvmem_cell
  - lib/kobject.c:kobject_rename
```
**Symbols:**

```
ffffffff8124a9a0-ffffffff8124a9c6: kstrdup_const (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
