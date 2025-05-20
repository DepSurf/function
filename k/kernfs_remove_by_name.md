# Function: <code>kernfs_remove_by_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81113c37)
Location: include/linux/kernfs.h:465
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff8128c72a)
Location: include/linux/kernfs.h:465
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_bin_file
```
```
In fs/sysfs/symlink.c (ffffffff8128cee2)
Location: include/linux/kernfs.h:465
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff8128d2a1)
Location: include/linux/kernfs.h:465
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111be46)
Location: include/linux/kernfs.h:479
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff812b9df6)
Location: include/linux/kernfs.h:479
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff812ba562)
Location: include/linux/kernfs.h:479
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff812ba972)
Location: include/linux/kernfs.h:479
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043772)
Location: include/linux/kernfs.h:491
Inline: True
```
```
In kernel/cgroup.c (ffffffff81124186)
Location: include/linux/kernfs.h:491
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff812cf526)
Location: include/linux/kernfs.h:491
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff812cfc92)
Location: include/linux/kernfs.h:491
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff812d00a2)
Location: include/linux/kernfs.h:491
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043f92)
Location: include/linux/kernfs.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff8112373c)
Location: include/linux/kernfs.h:501
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff812dcc66)
Location: include/linux/kernfs.h:501
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff812dd362)
Location: include/linux/kernfs.h:501
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff812dd772)
Location: include/linux/kernfs.h:501
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047762)
Location: include/linux/kernfs.h:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff8112f5dc)
Location: include/linux/kernfs.h:525
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff81301576)
Location: include/linux/kernfs.h:525
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff81301c92)
Location: include/linux/kernfs.h:525
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff813020a2)
Location: include/linux/kernfs.h:525
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049d22)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff8113daca)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff8132f2b5)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff8132fb32)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff81330072)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a0a2)
Location: include/linux/kernfs.h:536
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff811494cf)
Location: include/linux/kernfs.h:536
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff81346675)
Location: include/linux/kernfs.h:536
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff81346ee2)
Location: include/linux/kernfs.h:536
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff81347412)
Location: include/linux/kernfs.h:536
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d35d)
Location: include/linux/kernfs.h:564
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff811548fd)
Location: include/linux/kernfs.h:564
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff8136e995)
Location: include/linux/kernfs.h:564
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff8136f242)
Location: include/linux/kernfs.h:564
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff8136f813)
Location: include/linux/kernfs.h:564
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105dc4d)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff8116052d)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff81386c15)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff813875b2)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff81387b73)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106359d)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff81171b13)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff813d17a5)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff813d2282)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff813d2d53)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061a2d)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff8116e784)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff813e33a5)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff813e3fa2)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff813e4ab3)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810621fd)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff8116f56b)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff813e9fe5)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff813eaba2)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff813eb6b3)
Location: include/linux/kernfs.h:590
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106c009)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff8119574c)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff8143bd65)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff8143c922)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff8143d443)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81079359)
Location: include/linux/kernfs.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff811c1eb9)
Location: include/linux/kernfs.h:555
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff814b71c5)
Location: include/linux/kernfs.h:555
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff814b8162)
Location: include/linux/kernfs.h:555
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff814b8d92)
Location: include/linux/kernfs.h:555
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089eb6)
Location: include/linux/kernfs.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff8120450b)
Location: include/linux/kernfs.h:615
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff8154e4e5)
Location: include/linux/kernfs.h:615
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff8154f6f2)
Location: include/linux/kernfs.h:615
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff81550472)
Location: include/linux/kernfs.h:615
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108cf2c)
Location: include/linux/kernfs.h:619
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff81219aa0)
Location: include/linux/kernfs.h:619
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff815861a5)
Location: include/linux/kernfs.h:619
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff815873c2)
Location: include/linux/kernfs.h:619
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff81588162)
Location: include/linux/kernfs.h:619
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810942bc)
Location: include/linux/kernfs.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff812315ad)
Location: include/linux/kernfs.h:620
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff815bec85)
Location: include/linux/kernfs.h:620
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff815bff52)
Location: include/linux/kernfs.h:620
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff815c0d22)
Location: include/linux/kernfs.h:620
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:create_files
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d109c)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffff8000104568ac)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffff80001045748c)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffff800010457cf4)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0412790)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (c06188e4)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (c0619580)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (c0619f70)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:remove_files
  - fs/sysfs/group.c:remove_files
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023b96c)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (c00000000057082c)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (c0000000005718e8)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (c0000000005722d0)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014af42)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffe0002e802e)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffe0002e8948)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffe0002e8f88)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d7cd)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff81158b4d)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff8137f1f5)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff8137fb92)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff81380153)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104d99d)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff8114bd41)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff8136fc85)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff81370622)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff81370be3)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105dbfd)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff8115691d)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff8137ccc5)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff8137d662)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff8137dc23)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f11d)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_mondata_subdir_allrdtgrp
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_add_files
```
```
In kernel/cgroup/cgroup.c (ffffffff81161cf0)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_addrm_files
```
```
In fs/sysfs/file.c (ffffffff813907a5)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_bin_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
```
```
In fs/sysfs/symlink.c (ffffffff81391142)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/symlink.c:sysfs_remove_link
```
```
In fs/sysfs/group.c (ffffffff81391723)
Location: include/linux/kernfs.h:565
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
  - fs/sysfs/group.c:internal_create_group
```
</details>
</li>
</ul>

## Differences
