# Function: <code>fs_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fs_parse(struct fs_context *fc, const struct fs_parameter_description *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8130b0b0)
Location: fs/fs_parser.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff8130b0b0-ffffffff8130b412: fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fs_parse(struct fs_context *fc, const struct fs_parameter_description *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8131e080)
Location: fs/fs_parser.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff8131e080-ffffffff8131e419: fs_parse (STB_GLOBAL)
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fa53)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
```
```
In kernel/cgroup/cgroup.c (ffffffff8116ec83)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117adf1)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
```
```
In kernel/bpf/inode.c (ffffffff81213f13)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_parse_param
```
```
In mm/shmem.c (ffffffff8126b5ed)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/proc/root.c (ffffffff813ba2a1)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/proc/root.c:proc_parse_param
```
```
In fs/ramfs/inode.c (ffffffff8144faf3)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff8145055d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fuse/inode.c (ffffffff8147ca8e)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In security/selinux/hooks.c (ffffffff814b2017)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
```
```
In security/smack/smack_lsm.c (ffffffff814d3637)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105de43)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
```
```
In kernel/cgroup/cgroup.c (ffffffff8116b6b3)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177c21)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
```
```
In kernel/bpf/inode.c (ffffffff81215753)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_parse_param
```
```
In mm/shmem.c (ffffffff81275f8d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/proc/root.c (ffffffff813cbda1)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/proc/root.c:proc_parse_param
```
```
In fs/ramfs/inode.c (ffffffff8146c003)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff8146ca6d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fuse/inode.c (ffffffff81497bee)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In security/selinux/hooks.c (ffffffff814cf397)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
```
```
In security/smack/smack_lsm.c (ffffffff814f07f7)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e663)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
```
```
In kernel/cgroup/cgroup.c (ffffffff8116c233)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178781)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
```
```
In kernel/bpf/inode.c (ffffffff81218343)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_parse_param
```
```
In mm/shmem.c (ffffffff8127b39d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/proc/root.c (ffffffff813d2d91)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/proc/root.c:proc_parse_param
```
```
In fs/ramfs/inode.c (ffffffff81471683)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff81471e3d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fuse/inode.c (ffffffff8149ce21)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In security/selinux/hooks.c (ffffffff814d5ad7)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
```
```
In security/smack/smack_lsm.c (ffffffff814f7777)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81067de3)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
```
```
In kernel/cgroup/cgroup.c (ffffffff81191e93)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811a00e1)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
```
```
In kernel/bpf/inode.c (ffffffff8124ea8d)
Location: include/linux/fs_parser.h:68
Inline: True
```
```
In mm/shmem.c (ffffffff812b924d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/proc/root.c (ffffffff814242e1)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/proc/root.c:proc_parse_param
```
```
In fs/squashfs/super.c (ffffffff814c5243)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_parse_param
```
```
In fs/ramfs/inode.c (ffffffff814c8113)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff814c87cd)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fuse/inode.c (ffffffff814f4881)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In security/selinux/hooks.c (ffffffff8152e617)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
```
```
In security/smack/smack_lsm.c (ffffffff81552317)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81074c53)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
```
```
In kernel/cgroup/cgroup.c (ffffffff811c18a3)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0821)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
```
```
In kernel/bpf/inode.c (ffffffff812959ed)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_parse_param
```
```
In mm/shmem.c (ffffffff81315115)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/proc/root.c (ffffffff8149ce91)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/proc/root.c:proc_parse_param
```
```
In fs/ext4/super.c (ffffffff815282df)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/squashfs/super.c (ffffffff815500b3)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_parse_param
```
```
In fs/ramfs/inode.c (ffffffff8155360d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff81553e45)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fuse/inode.c (ffffffff8158448d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In security/selinux/hooks.c (ffffffff815c77d7)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
```
```
In security/smack/smack_lsm.c (ffffffff815ebd67)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81086e25)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
```
```
In kernel/cgroup/cgroup.c (ffffffff81203e93)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214311)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
```
```
In kernel/bpf/inode.c (ffffffff812f07cd)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_parse_param
```
```
In mm/shmem.c (ffffffff81388ff5)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/proc/root.c (ffffffff815318f1)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/proc/root.c:proc_parse_param
```
```
In fs/ext4/super.c (ffffffff815c63fd)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/squashfs/super.c (ffffffff815f0c58)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_parse_param
```
```
In fs/ramfs/inode.c (ffffffff815f4dbd)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff815f5695)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fuse/inode.c (ffffffff8162a56d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In security/selinux/hooks.c (ffffffff81674677)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
```
```
In security/smack/smack_lsm.c (ffffffff8169b9b7)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810898d5)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
```
```
In kernel/cgroup/cgroup.c (ffffffff812193f3)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81229c21)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
```
```
In kernel/bpf/inode.c (ffffffff8131d1ed)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_parse_param
```
```
In mm/shmem.c (ffffffff813bb227)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/proc/root.c (ffffffff81569ac1)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/proc/root.c:proc_parse_param
```
```
In fs/ext4/super.c (ffffffff815fe18f)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/squashfs/super.c (ffffffff81628cb8)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_parse_param
```
```
In fs/ramfs/inode.c (ffffffff8162ce3d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff8162d715)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fuse/inode.c (ffffffff8166277d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In security/selinux/hooks.c (ffffffff816acce7)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
```
```
In security/smack/smack_lsm.c (ffffffff816d4217)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108e565)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
```
```
In kernel/cgroup/cgroup.c (ffffffff81230f03)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81241ac1)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
```
```
In kernel/bpf/inode.c (ffffffff8133f48f)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_parse_param
```
```
In mm/shmem.c (ffffffff813e5b27)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/proc/root.c (ffffffff815a20a1)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/proc/root.c:proc_parse_param
```
```
In fs/ext4/super.c (ffffffff81636bcf)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/squashfs/super.c (ffffffff81661ea8)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_parse_param
```
```
In fs/ramfs/inode.c (ffffffff8166632d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff81666bf5)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fuse/inode.c (ffffffff8169c57d)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In fs/efivarfs/super.c (ffffffff816aedd3)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_parse_param
```
```
In security/selinux/hooks.c (ffffffff816ea0d7)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
```
```
In security/smack/smack_lsm.c (ffffffff81710327)
Location: include/linux/fs_parser.h:68
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
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
int fs_parse(struct fs_context *fc, const struct fs_parameter_description *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffff8000103d62e8)
Location: fs/fs_parser.c:79
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffff8000103d62e8-ffff8000103d66c8: fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fs_parse(struct fs_context *fc, const struct fs_parameter_description *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (c05afd4c)
Location: fs/fs_parser.c:79
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
c05afd4c-c05b0134: fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fs_parse(struct fs_context *fc, const struct fs_parameter_description *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (c0000000004d9e20)
Location: fs/fs_parser.c:79
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
c0000000004d9e20-c0000000004da660: fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fs_parse(struct fs_context *fc, const struct fs_parameter_description *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffe000290024)
Location: fs/fs_parser.c:79
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffe000290024-ffffffe00029034c: fs_parse (STB_GLOBAL)
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
int fs_parse(struct fs_context *fc, const struct fs_parameter_description *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81316660)
Location: fs/fs_parser.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff81316660-ffffffff813169f9: fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fs_parse(struct fs_context *fc, const struct fs_parameter_description *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81307250)
Location: fs/fs_parser.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff81307250-ffffffff813075e9: fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fs_parse(struct fs_context *fc, const struct fs_parameter_description *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81314450)
Location: fs/fs_parser.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff81314450-ffffffff813147e9: fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fs_parse(struct fs_context *fc, const struct fs_parameter_description *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81325ca0)
Location: fs/fs_parser.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff81325ca0-ffffffff81326039: fs_parse (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
