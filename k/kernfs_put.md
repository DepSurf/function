# Function: <code>kernfs_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812898c0)
Location: fs/kernfs/dir.c:546
Inline: True
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dop_release
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:sysfs_remove_group
  - lib/kobject.c:kobject_del
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:md_free
  - drivers/md/bitmap.c:bitmap_destroy
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff812898c0-ffffffff81289a52: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b6d20)
Location: fs/kernfs/dir.c:545
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_get_from_path
  - kernel/cgroup.c:css_free_work_fn
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_dop_release
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_del
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_free
```
**Symbols:**

```
ffffffff812b6d20-ffffffff812b6eb6: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cc530)
Location: fs/kernfs/dir.c:495
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup.c:cgroup_get_from_path
  - kernel/cgroup.c:css_free_work_fn
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_dop_release
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_del
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_free
```
**Symbols:**

```
ffffffff812cc530-ffffffff812cc6c6: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812d9b00)
Location: fs/kernfs/dir.c:505
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_dop_release
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_free
  - drivers/leds/led-class.c:led_classdev_unregister
```
**Symbols:**

```
ffffffff812d9b00-ffffffff812d9c79: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812fe400)
Location: fs/kernfs/dir.c:506
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_free
  - drivers/leds/led-class.c:led_classdev_unregister
```
**Symbols:**

```
ffffffff812fe400-ffffffff812fe596: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132c430)
Location: fs/kernfs/dir.c:506
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_kn_unlock
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_free
  - drivers/leds/led-class.c:led_classdev_unregister
```
**Symbols:**

```
ffffffff8132c430-ffffffff8132c5c4: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813435a0)
Location: fs/kernfs/dir.c:506
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/leds/led-class.c:led_classdev_unregister
```
**Symbols:**

```
ffffffff813435a0-ffffffff81343734: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136b830)
Location: fs/kernfs/dir.c:505
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/leds/led-class.c:led_classdev_unregister
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff8136b830-ffffffff8136b9af: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81383a00)
Location: fs/kernfs/dir.c:506
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff81383a00-ffffffff81383b7f: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cea37)
Location: fs/kernfs/dir.c:506
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:__kobject_del
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
**Symbols:**

```
ffffffff813ce630-ffffffff813ce7b6: kernfs_put.part.0 (STB_LOCAL)
ffffffff813ce7c0-ffffffff813ce7db: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e0667)
Location: fs/kernfs/dir.c:506
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:__kobject_del
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
**Symbols:**

```
ffffffff813e0260-ffffffff813e03e6: kernfs_put.part.0 (STB_LOCAL)
ffffffff813e03f0-ffffffff813e040b: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7197)
Location: fs/kernfs/dir.c:506
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:__kobject_del
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
**Symbols:**

```
ffffffff813e6cd0-ffffffff813e6e56: kernfs_put.part.0 (STB_LOCAL)
ffffffff813e6e60-ffffffff813e6e7b: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81438d47)
Location: fs/kernfs/dir.c:508
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:__kobject_del
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
**Symbols:**

```
ffffffff81438870-ffffffff81438a05: kernfs_put.part.0 (STB_LOCAL)
ffffffff81cc85d5-ffffffff81cc85ea: kernfs_put.part.0.cold (STB_LOCAL)
ffffffff81438a10-ffffffff81438a2b: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b3e27)
Location: fs/kernfs/dir.c:516
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:__kobject_del
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/leds/led-class.c:led_classdev_unregister
```
**Symbols:**

```
ffffffff814b38c0-ffffffff814b3a6a: kernfs_put.part.0 (STB_LOCAL)
ffffffff81e7b310-ffffffff81e7b325: kernfs_put.part.0.cold (STB_LOCAL)
ffffffff814b3a70-ffffffff814b3a97: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154ac07)
Location: fs/kernfs/dir.c:537
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/leds/led-class.c:led_classdev_unregister
  - lib/kobject.c:__kobject_del
```
**Symbols:**

```
ffffffff8154a750-ffffffff8154a8c4: kernfs_put.part.0 (STB_LOCAL)
ffffffff8206bbfb-ffffffff8206bc10: kernfs_put.part.0.cold (STB_LOCAL)
ffffffff8154a8e0-ffffffff8154a907: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81582857)
Location: fs/kernfs/dir.c:534
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/leds/led-class.c:led_classdev_unregister
  - lib/kobject.c:__kobject_del
```
**Symbols:**

```
ffffffff81582380-ffffffff815824e0: kernfs_put.part.0 (STB_LOCAL)
ffffffff820eba89-ffffffff820eba9e: kernfs_put.part.0.cold (STB_LOCAL)
ffffffff815824f0-ffffffff81582517: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bb487)
Location: fs/kernfs/dir.c:538
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:free_all_child_rdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/leds/led-class.c:led_classdev_unregister
  - lib/kobject.c:__kobject_del
```
**Symbols:**

```
ffffffff815bafe0-ffffffff815bb142: kernfs_put.part.0 (STB_LOCAL)
ffffffff821c8ced-ffffffff821c8d02: kernfs_put.part.0.cold (STB_LOCAL)
ffffffff815bb160-ffffffff815bb187: kernfs_put (STB_GLOBAL)
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
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010451ff8)
Location: fs/kernfs/dir.c:506
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/of/kobj.c:safe_name
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffff800010451ff8-ffff800010452240: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0614de4)
Location: fs/kernfs/dir.c:506
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/of/kobj.c:safe_name
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
c0614de4-c061500c: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056aa70)
Location: fs/kernfs/dir.c:506
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init
  - drivers/of/kobj.c:safe_name
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
c00000000056aa70-c00000000056ad74: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e4ec6)
Location: fs/kernfs/dir.c:506
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - drivers/of/kobj.c:safe_name
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffe0002e4c3a-ffffffe0002e4e02: kernfs_put.part.0 (STB_LOCAL)
ffffffe0002e4e02-ffffffe0002e4e46: kernfs_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137bfe0)
Location: fs/kernfs/dir.c:506
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff8137bfe0-ffffffff8137c15f: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136cab0)
Location: fs/kernfs/dir.c:506
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_register_dimms
  - drivers/acpi/nfit/core.c:shutdown_dimm_notify
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/pmem.c:nd_pmem_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff8136cab0-ffffffff8136cc2f: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81379ab0)
Location: fs/kernfs/dir.c:506
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff81379ab0-ffffffff81379c2f: kernfs_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kernfs_put(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138d3e0)
Location: fs/kernfs/dir.c:506
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restore
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_mode_restrict
  - kernel/cgroup/cgroup.c:cgroup_get_from_path
  - kernel/cgroup/cgroup.c:cgroup_path_from_kernfs_id
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/mount.c:kernfs_get_node_by_id
  - fs/kernfs/inode.c:kernfs_evict_inode
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_link_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_unbreak_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/dir.c:sysfs_rename_dir_ns
  - fs/sysfs/symlink.c:sysfs_rename_link_ns
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
  - lib/kobject.c:kobject_del
```
**Symbols:**

```
ffffffff8138d3e0-ffffffff8138d565: kernfs_put (STB_GLOBAL)
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
