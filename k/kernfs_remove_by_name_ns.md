# Function: <code>kernfs_remove_by_name_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128ae50)
Location: fs/kernfs/dir.c:1399
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8128ae50-ffffffff8128aee2: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b8370)
Location: fs/kernfs/dir.c:1448
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812b8370-ffffffff812b8402: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cdb10)
Location: fs/kernfs/dir.c:1399
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812cdb10-ffffffff812cdba2: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812db110)
Location: fs/kernfs/dir.c:1409
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812db110-ffffffff812db1a6: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ffa00)
Location: fs/kernfs/dir.c:1474
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff812ffa00-ffffffff812ffa96: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132d6b0)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8132d6b0-ffffffff8132d741: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81344a50)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81344a50-ffffffff81344ae1: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136cc70)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8136cc70-ffffffff8136cd03: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384e20)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff81384e20-ffffffff81384eb3: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf950)
Location: fs/kernfs/dir.c:1501
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
**Symbols:**

```
ffffffff813cf950-ffffffff813cf9e3: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e1580)
Location: fs/kernfs/dir.c:1500
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
**Symbols:**

```
ffffffff813e1580-ffffffff813e1613: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e81b0)
Location: fs/kernfs/dir.c:1502
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
**Symbols:**

```
ffffffff813e81b0-ffffffff813e8243: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439ef0)
Location: fs/kernfs/dir.c:1529
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
**Symbols:**

```
ffffffff81439ef0-ffffffff81439f83: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b5060)
Location: fs/kernfs/dir.c:1572
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
**Symbols:**

```
ffffffff814b5060-ffffffff814b5111: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154c0b0)
Location: fs/kernfs/dir.c:1644
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
**Symbols:**

```
ffffffff8154c0b0-ffffffff8154c183: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583d70)
Location: fs/kernfs/dir.c:1651
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
**Symbols:**

```
ffffffff81583d70-ffffffff81583e43: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bc850)
Location: fs/kernfs/dir.c:1667
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
**Symbols:**

```
ffffffff815bc850-ffffffff815bc923: kernfs_remove_by_name_ns (STB_GLOBAL)
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
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010453e20)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffff800010453e20-ffff800010453ed0: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0616944)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
**Symbols:**

```
c0616944-c0616a04: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056d3e0)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
c00000000056d3e0-c00000000056d4dc: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e6338)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffe0002e6338-ffffffe0002e63da: kernfs_remove_by_name_ns (STB_GLOBAL)
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
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137d400)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8137d400-ffffffff8137d493: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136dec0)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8136dec0-ffffffff8136df53: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137aed0)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8137aed0-ffffffff8137af63: kernfs_remove_by_name_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernfs_remove_by_name_ns(struct kernfs_node *parent, const char *name, const void *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e9d0)
Location: fs/kernfs/dir.c:1497
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_files
  - fs/sysfs/file.c:sysfs_create_files
  - fs/sysfs/dir.c:sysfs_remove_mount_point
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_remove_link
  - fs/sysfs/symlink.c:sysfs_delete_link
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
**Symbols:**

```
ffffffff8138e9d0-ffffffff8138ea63: kernfs_remove_by_name_ns (STB_GLOBAL)
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
