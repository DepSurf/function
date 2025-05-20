# Function: <code>kernfs_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128ac90)
Location: fs/kernfs/dir.c:1252
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:sysfs_remove_group
```
**Symbols:**

```
ffffffff8128ac90-ffffffff8128acc0: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b81b0)
Location: fs/kernfs/dir.c:1301
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812b81b0-ffffffff812b81e0: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd950)
Location: fs/kernfs/dir.c:1252
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - kernel/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812cd950-ffffffff812cd980: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812daf30)
Location: fs/kernfs/dir.c:1262
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812daf30-ffffffff812daf76: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff820)
Location: fs/kernfs/dir.c:1327
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812ff820-ffffffff812ff866: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132d4d0)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8132d4d0-ffffffff8132d516: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81344870)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81344870-ffffffff813448b6: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136ca90)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8136ca90-ffffffff8136cadb: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384c40)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81384c40-ffffffff81384c8b: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf25e)
Location: fs/kernfs/dir.c:1354
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_add_file
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813cf750-ffffffff813cf79d: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e0e8e)
Location: fs/kernfs/dir.c:1353
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_create_info_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_add_file
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813e1380-ffffffff813e13cd: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7abe)
Location: fs/kernfs/dir.c:1355
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff813e7fb0-ffffffff813e7ffd: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814397de)
Location: fs/kernfs/dir.c:1382
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_destroy_root
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81439cf0-ffffffff81439d3d: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4dc0)
Location: fs/kernfs/dir.c:1417
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff814b4dc0-ffffffff814b4e26: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154bdc0)
Location: fs/kernfs/dir.c:1486
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8154bdc0-ffffffff8154be26: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583a80)
Location: fs/kernfs/dir.c:1493
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81583a80-ffffffff81583ae6: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bc560)
Location: fs/kernfs/dir.c:1509
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mkdir_ctrl_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_create
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff815bc560-ffffffff815bc5c6: kernfs_remove (STB_GLOBAL)
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
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010453b88)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffff800010453b88-ffff800010453be8: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c06166a8)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c06166a8-c0616708: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056d100)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c00000000056d100-c00000000056d18c: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e60c8)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffe0002e60c8-ffffffe0002e6122: kernfs_remove (STB_GLOBAL)
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
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137d220)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8137d220-ffffffff8137d26b: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136dce0)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8136dce0-ffffffff8136dd2b: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137acf0)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8137acf0-ffffffff8137ad3b: kernfs_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kernfs_remove(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e7f0)
Location: fs/kernfs/dir.c:1350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_all
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mongroup_create_dir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_destroy_locked
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/kernfs/dir.c:kernfs_destroy_root
  - fs/sysfs/dir.c:sysfs_remove_dir
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8138e7f0-ffffffff8138e83b: kernfs_remove (STB_GLOBAL)
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
