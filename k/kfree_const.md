# Function: <code>kfree_const</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811abbf0)
Location: mm/util.c:32
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:slab_kmem_cache_release
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/kernfs/dir.c:kernfs_rename_ns
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
  - lib/dynamic_debug.c:ddebug_remove_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/base/power/wakeup.c:wakeup_source_destroy
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/firmware_class.c:request_firmware_work_func
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff811abbf0-ffffffff811abc14: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4670)
Location: mm/util.c:32
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/base/power/wakeup.c:wakeup_source_destroy
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/firmware_class.c:request_firmware_work_func
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:__fw_free_buf
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff811c4670-ffffffff811c4693: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4760)
Location: mm/util.c:32
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/base/power/wakeup.c:wakeup_source_destroy
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/firmware_class.c:request_firmware_work_func
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:__fw_free_buf
```
**Symbols:**

```
ffffffff811d4760-ffffffff811d4783: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd510)
Location: mm/util.c:35
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/firmware_class.c:request_firmware_work_func
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:fw_free_buf
  - lib/kobject.c:kobject_put
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff811dd510-ffffffff811dd534: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f2f90)
Location: mm/util.c:35
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
  - drivers/base/firmware_class.c:dev_cache_fw_image
  - drivers/base/firmware_class.c:request_firmware_nowait
  - drivers/base/firmware_class.c:request_firmware_work_func
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:fw_name_devm_release
  - drivers/base/firmware_class.c:__fw_free_buf
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff811f2f90-ffffffff811f2fb4: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214280)
Location: mm/util.c:35
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81214280-ffffffff812142a3: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227150)
Location: mm/util.c:28
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_remove_module
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:__clk_free_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81227150-ffffffff81227173: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81236c50)
Location: mm/util.c:30
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81236c50-ffffffff81236c73: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81244e10)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_drop
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81244e10-ffffffff81244e33: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81272ac0)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:create_new_subsystem
  - kernel/trace/trace_events.c:__put_system
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/genalloc.c:gen_pool_destroy
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_device_release
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_core_free_parent_map
  - drivers/clk/clk.c:clk_core_free_parent_map
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:__device_uncache_fw_images
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_init_cache_dev
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_cell_drop
  - drivers/interconnect/core.c:icc_put
```
**Symbols:**

```
ffffffff81272ac0-ffffffff81272ae3: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d170)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:create_new_subsystem
  - kernel/trace/trace_events.c:__put_system
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/genalloc.c:gen_pool_destroy
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/acpi/scan.c:acpi_device_release
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_core_free_parent_map
  - drivers/clk/clk.c:clk_core_free_parent_map
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:destroy_regulator
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:__device_uncache_fw_images
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_init_cache_dev
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/nvmem/core.c:nvmem_cell_drop
  - drivers/interconnect/core.c:icc_put
```
**Symbols:**

```
ffffffff8127d170-ffffffff8127d193: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282300)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:__put_system
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/genalloc.c:gen_pool_destroy
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/acpi/scan.c:acpi_device_release
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_core_free_parent_map
  - drivers/clk/clk.c:clk_core_free_parent_map
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/clk.c:clk_core_populate_parent_map
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/nvmem/core.c:nvmem_cell_drop
  - drivers/interconnect/core.c:icc_put
```
**Symbols:**

```
ffffffff81282300-ffffffff81282323: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0370)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:__put_system
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_var_field
  - kernel/trace/trace_events_hist.c:create_var
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/genalloc.c:gen_pool_destroy
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del
  - drivers/acpi/scan.c:acpi_device_release
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_core_free_parent_map
  - drivers/clk/clk.c:clk_core_free_parent_map
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/nvmem/core.c:nvmem_cell_drop
  - drivers/interconnect/core.c:icc_put
```
**Symbols:**

```
ffffffff812c0370-ffffffff812c0393: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131ce30)
Location: mm/util.c:38
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:__put_system
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/genalloc.c:gen_pool_destroy
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:__acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/scan.c:acpi_device_release
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:_regulator_put
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_entry_drop
  - drivers/interconnect/core.c:icc_put
  - drivers/hte/hte.c:hte_ts_put
```
**Symbols:**

```
ffffffff8131ce30-ffffffff8131ce5f: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81390870)
Location: mm/util.c:38
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:__put_system
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/char_dev.c:cdev_add
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/genalloc.c:gen_pool_destroy
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/scan.c:acpi_device_release
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:create_regulator
  - drivers/base/class.c:__class_register
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_cell_entry_drop
  - drivers/interconnect/core.c:icc_put
  - drivers/hte/hte.c:hte_ts_put
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81390870-ffffffff8139089f: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c3170)
Location: mm/util.c:38
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:__put_system
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/char_dev.c:cdev_add
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/genalloc.c:gen_pool_destroy
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodev_release
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/scan.c:acpi_device_release
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:create_regulator
  - drivers/base/class.c:class_register
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/leds/led-class.c:led_get
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
  - drivers/hte/hte.c:hte_ts_put
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff813c3170-ffffffff813c319f: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813edc90)
Location: mm/util.c:38
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:__put_system
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:create_var_fields
  - kernel/trace/trace_events_hist.c:create_var
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/char_dev.c:cdev_add
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - fs/tracefs/event_inode.c:release_ei
  - lib/genalloc.c:gen_pool_destroy
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodev_release
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/scan.c:acpi_device_release
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/regulator/core.c:_regulator_put
  - drivers/regulator/core.c:create_regulator
  - drivers/base/class.c:class_register
  - drivers/base/power/wakeup.c:wakeup_source_register
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/gpu/drm/drm_managed.c:drm_managed_release
  - drivers/thermal/thermal_core.c:thermal_release
  - drivers/leds/led-class.c:led_get
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_type_release
  - drivers/remoteproc/remoteproc_core.c:rproc_set_firmware
  - drivers/nvmem/core.c:nvmem_cell_put
  - drivers/nvmem/core.c:nvmem_device_remove_all_cells
  - drivers/nvmem/core.c:nvmem_cell_attr_read
  - drivers/hte/hte.c:hte_ts_put
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_cleanup
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff813edc90-ffffffff813edcbf: kfree_const (STB_GLOBAL)
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
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d7da0)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - drivers/pinctrl/devicetree.c:dt_free_map
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_drop
  - lib/kobject.c:kobject_put
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffff8000102d7da0-ffff8000102d7df8: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff23c)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - drivers/pinctrl/devicetree.c:dt_free_map
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_core_free_parent_map
  - drivers/clk/clk.c:clk_core_free_parent_map
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/renesas/renesas-soc.c:renesas_soc_init
  - drivers/soc/samsung/pm_domains.c:exynos4_pm_init_power_domain
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_drop
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked
  - sound/soc/soc-dapm.c:snd_soc_dapm_free_widget
  - sound/soc/soc-dapm.c:snd_soc_dapm_free_widget
  - lib/kobject.c:kobject_put
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
c04ff23c-c04ff280: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000397810)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - lib/genalloc.c:gen_pool_destroy
  - drivers/pinctrl/devicetree.c:dt_free_map
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_drop
  - lib/kobject.c:kobject_put
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
c000000000397810-c000000000397894: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f2650)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - drivers/pinctrl/devicetree.c:dt_free_map
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_drop
  - lib/kobject.c:kobject_put
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffe0001f2650-ffffffe0001f269c: kfree_const (STB_GLOBAL)
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
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d460)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvmem/core.c:nvmem_cell_drop
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8123d460-ffffffff8123d483: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230460)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/nvmem/core.c:nvmem_cell_drop
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81230460-ffffffff81230483: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b200)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_drop
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8123b200-ffffffff8123b223: kfree_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kfree_const(const void *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124a910)
Location: mm/util.c:37
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:event_create_dir
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slab_common.c:kmem_cache_create_usercopy
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:alloc_vfsmnt
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_new_node
  - drivers/gpio/gpiolib.c:gpiod_set_consumer_name
  - drivers/gpio/gpiolib.c:gpiod_free_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiodevice_release
  - drivers/acpi/scan.c:acpi_free_pnp_ids
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_release
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_free_parent_names_loop
  - drivers/base/power/wakeup.c:wakeup_source_free
  - drivers/base/power/wakeup.c:wakeup_source_create
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_work_func
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:fw_name_devm_release
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/regmap/regmap.c:regmap_exit
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/nvmem/core.c:nvmem_cell_drop
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_set_name_vargs
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8124a910-ffffffff8124a933: kfree_const (STB_GLOBAL)
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
