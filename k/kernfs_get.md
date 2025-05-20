# Function: <code>kernfs_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81289270)
Location: fs/kernfs/dir.c:531
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:sysfs_remove_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81289270-ffffffff812892a2: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b6740)
Location: fs/kernfs/dir.c:530
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff812b6740-ffffffff812b6772: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cc2a0)
Location: fs/kernfs/dir.c:480
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:__kernfs_remove
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff812cc2a0-ffffffff812cc2d2: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812d99c0)
Location: fs/kernfs/dir.c:490
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff812d99c0-ffffffff812d99dd: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812fe190)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff812fe190-ffffffff812fe1af: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132bef0)
Location: fs/kernfs/dir.c:491
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8132bef0-ffffffff8132bf0e: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81343250)
Location: fs/kernfs/dir.c:491
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81343250-ffffffff8134326e: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/kernfs/dir.c (0)
Location: fs/kernfs/dir.c:490
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8136cef6-ffffffff8136cf09: kernfs_get.cold (STB_LOCAL)
ffffffff8136b380-ffffffff8136b3a3: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81383560)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81383560-ffffffff8138357d: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cdea0)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_init_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:create_dir
```
**Symbols:**

```
ffffffff813cdea0-ffffffff813cdebd: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813dfad0)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_init_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:create_dir
```
**Symbols:**

```
ffffffff813dfad0-ffffffff813dfaed: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e6760)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:create_dir
```
**Symbols:**

```
ffffffff813e6760-ffffffff813e677d: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81438eaa)
Location: fs/kernfs/dir.c:493
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_get_parent
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:create_dir
```
**Symbols:**

```
ffffffff81438360-ffffffff8143837d: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b3fc1)
Location: fs/kernfs/dir.c:501
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_get_parent
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff814b3180-ffffffff814b31a5: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154adb0)
Location: fs/kernfs/dir.c:522
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_get_parent
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81549de0-ffffffff81549e05: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81582a04)
Location: fs/kernfs/dir.c:519
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_get_parent
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81581a00-ffffffff81581a25: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bb634)
Location: fs/kernfs/dir.c:523
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_by_name_ns
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff815b9f70-ffffffff815b9f95: kernfs_get (STB_GLOBAL)
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
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010452368)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffff800010452368-ffff8000104523c4: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0614a78)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/symlink.c:sysfs_do_create_link_sd
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c0614a78-c0614ad4: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c000000000569c90)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c000000000569c90-c000000000569cc4: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e546a)
Location: fs/kernfs/dir.c:491
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffe0002e4654-ffffffe0002e4686: kernfs_get (STB_GLOBAL)
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
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137bb40)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8137bb40-ffffffff8137bb5d: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c610)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8136c610-ffffffff8136c62d: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81379610)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81379610-ffffffff8137962d: kernfs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kernfs_get(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138d0c0)
Location: fs/kernfs/dir.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_info_resdir
  - kernel/cgroup/cgroup.c:cgroup_mkdir
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_walk_and_get_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_ns
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_get_parent
  - fs/kernfs/file.c:kernfs_notify
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:internal_create_group
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8138d0c0-ffffffff8138d0dd: kernfs_get (STB_GLOBAL)
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
