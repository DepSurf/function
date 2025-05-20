# Function: <code>kernfs_find_and_get_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81289e80)
Location: fs/kernfs/dir.c:837
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_run
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff81289e80-ffffffff81289ed2: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b72d0)
Location: fs/kernfs/dir.c:862
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff812b72d0-ffffffff812b7322: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ccae0)
Location: fs/kernfs/dir.c:812
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff812ccae0-ffffffff812ccb32: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812da070)
Location: fs/kernfs/dir.c:822
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff812da070-ffffffff812da0c2: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812fe990)
Location: fs/kernfs/dir.c:888
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff812fe990-ffffffff812fe9e2: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132bfd0)
Location: fs/kernfs/dir.c:905
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff8132bfd0-ffffffff8132c022: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813434a0)
Location: fs/kernfs/dir.c:905
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff813434a0-ffffffff813434f2: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136b730)
Location: fs/kernfs/dir.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:of_led_classdev_register
```
**Symbols:**

```
ffffffff8136b730-ffffffff8136b784: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81383900)
Location: fs/kernfs/dir.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81383900-ffffffff81383954: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813ce140)
Location: fs/kernfs/dir.c:900
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff813ce140-ffffffff813ce194: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813dfd70)
Location: fs/kernfs/dir.c:899
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff813dfd70-ffffffff813dfdc4: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e6920)
Location: fs/kernfs/dir.c:899
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff813e6920-ffffffff813e6974: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81438650)
Location: fs/kernfs/dir.c:858
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff81438650-ffffffff814386b0: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b3840)
Location: fs/kernfs/dir.c:866
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff814b3840-ffffffff814b38b5: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154a6c0)
Location: fs/kernfs/dir.c:885
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff8154a6c0-ffffffff8154a735: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815822f0)
Location: fs/kernfs/dir.c:887
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff815822f0-ffffffff81582365: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815baf50)
Location: fs/kernfs/dir.c:903
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff815baf50-ffffffff815bafc5: kernfs_find_and_get_ns (STB_GLOBAL)
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
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff8000104523c8)
Location: fs/kernfs/dir.c:906
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/of/kobj.c:safe_name
```
**Symbols:**

```
ffff8000104523c8-ffff800010452430: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0615900)
Location: fs/kernfs/dir.c:906
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/of/kobj.c:safe_name
```
**Symbols:**

```
c0615900-c0615958: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056bd90)
Location: fs/kernfs/dir.c:906
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/of/kobj.c:safe_name
```
**Symbols:**

```
c00000000056bd90-c00000000056be14: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e4b26)
Location: fs/kernfs/dir.c:906
Inline: False
Direct callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/of/kobj.c:safe_name
```
**Symbols:**

```
ffffffe0002e4b26-ffffffe0002e4b96: kernfs_find_and_get_ns (STB_GLOBAL)
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
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137bee0)
Location: fs/kernfs/dir.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8137bee0-ffffffff8137bf34: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c9b0)
Location: fs/kernfs/dir.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_register_dimms
  - drivers/acpi/nfit/core.c:acpi_nfit_register_dimms
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8136c9b0-ffffffff8136ca04: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813799b0)
Location: fs/kernfs/dir.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff813799b0-ffffffff81379a04: kernfs_find_and_get_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_node *kernfs_find_and_get_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138dce0)
Location: fs/kernfs/dir.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/leds/led-class.c:led_classdev_register_ext
```
**Symbols:**

```
ffffffff8138dce0-ffffffff8138dd34: kernfs_find_and_get_ns (STB_GLOBAL)
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
