# Function: <code>__fs_parse</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __fs_parse(struct p_log *log, const struct fs_parameter_spec *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81357df0)
Location: fs/fs_parser.c:103
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
ffffffff81357df0-ffffffff81357fa1: __fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __fs_parse(struct p_log *log, const struct fs_parameter_spec *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81364840)
Location: fs/fs_parser.c:103
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
ffffffff81364840-ffffffff813649f1: __fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __fs_parse(struct p_log *log, const struct fs_parameter_spec *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8136b2a0)
Location: fs/fs_parser.c:103
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
ffffffff8136b2a0-ffffffff8136b44a: __fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __fs_parse(struct p_log *log, const struct fs_parameter_spec *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff81cc423e-ffffffff81cc4252: __fs_parse.cold (STB_LOCAL)
ffffffff813b9f60-ffffffff813ba11a: __fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __fs_parse(struct p_log *log, const struct fs_parameter_spec *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/squashfs/super.c:squashfs_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff81e76b52-ffffffff81e76b66: __fs_parse.cold (STB_LOCAL)
ffffffff8143faa0-ffffffff8143fc7f: __fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __fs_parse(struct p_log *log, const struct fs_parameter_spec *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/squashfs/super.c:squashfs_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff82068dbd-ffffffff82068dd1: __fs_parse.cold (STB_LOCAL)
ffffffff814ce7f0-ffffffff814ce9cf: __fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __fs_parse(struct p_log *log, const struct fs_parameter_spec *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/squashfs/super.c:squashfs_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff820e86e1-ffffffff820e86f5: __fs_parse.cold (STB_LOCAL)
ffffffff81504a50-ffffffff81504c2f: __fs_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __fs_parse(struct p_log *log, const struct fs_parameter_spec *desc, struct fs_parameter *param, struct fs_parse_result *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_parse_param
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - fs/proc/root.c:proc_parse_param
  - fs/ext4/super.c:ext4_parse_param
  - fs/squashfs/super.c:squashfs_parse_param
  - fs/ramfs/inode.c:ramfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/efivarfs/super.c:efivarfs_parse_param
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff821c54cc-ffffffff821c54e0: __fs_parse.cold (STB_LOCAL)
ffffffff81539710-ffffffff815398ef: __fs_parse (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
