# Function: <code>logfc</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void logfc(struct fs_context *fc, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (0)
Location: fs/fs_context.c:390
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
**Symbols:**

```
ffffffff8130ae56-ffffffff8130aea6: logfc.cold (STB_LOCAL)
ffffffff81309fa0-ffffffff8130a18b: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void logfc(struct fs_context *fc, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (0)
Location: fs/fs_context.c:388
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff8131de26-ffffffff8131de76: logfc.cold (STB_LOCAL)
ffffffff8131d010-ffffffff8131d1fb: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void logfc(struct fc_log *log, const char *prefix, char level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (0)
Location: fs/fs_context.c:362
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u64
  - fs/fs_parser.c:fs_param_is_s32
  - fs/fs_parser.c:fs_param_is_u32
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:__fs_parse
  - fs/fs_parser.c:__fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff81357be9-ffffffff81357c7b: logfc.cold (STB_LOCAL)
ffffffff81356d70-ffffffff81356eba: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void logfc(struct fc_log *log, const char *prefix, char level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (0)
Location: fs/fs_context.c:362
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u64
  - fs/fs_parser.c:fs_param_is_s32
  - fs/fs_parser.c:fs_param_is_u32
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:__fs_parse
  - fs/fs_parser.c:__fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff81bea8cb-ffffffff81bea95d: logfc.cold (STB_LOCAL)
ffffffff81363720-ffffffff8136386a: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void logfc(struct fc_log *log, const char *prefix, char level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (0)
Location: fs/fs_context.c:362
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u64
  - fs/fs_parser.c:fs_param_is_s32
  - fs/fs_parser.c:fs_param_is_u32
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:__fs_parse
  - fs/fs_parser.c:__fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff81bdc8e0-ffffffff81bdc970: logfc.cold (STB_LOCAL)
ffffffff8136a1b0-ffffffff8136a303: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void logfc(struct fc_log *log, const char *prefix, char level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (0)
Location: fs/fs_context.c:385
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:vfs_parse_fs_param_source
  - fs/fs_context.c:vfs_parse_fs_param_source
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u64
  - fs/fs_parser.c:fs_param_is_s32
  - fs/fs_parser.c:fs_param_is_u32
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:__fs_parse
  - fs/fs_parser.c:__fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff81cc41ae-ffffffff81cc423e: logfc.cold (STB_LOCAL)
ffffffff813b8ee0-ffffffff813b902f: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void logfc(struct fc_log *log, const char *prefix, char level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (0)
Location: fs/fs_context.c:385
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/fs_context.c:vfs_parse_fs_param_source
  - fs/fs_context.c:vfs_parse_fs_param_source
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u32
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:__fs_parse
  - fs/fs_parser.c:__fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff81e76abe-ffffffff81e76b52: logfc.cold (STB_LOCAL)
ffffffff8143e8f0-ffffffff8143ea60: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void logfc(struct fc_log *log, const char *prefix, char level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814cd460)
Location: fs/fs_context.c:385
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/fs_context.c:vfs_parse_fs_param_source
  - fs/fs_context.c:vfs_parse_fs_param_source
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u32
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:__fs_parse
  - fs/fs_parser.c:__fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff814cd460-ffffffff814cd66f: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void logfc(struct fc_log *log, const char *prefix, char level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81503640)
Location: fs/fs_context.c:406
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/fs_context.c:vfs_parse_fs_param_source
  - fs/fs_context.c:vfs_parse_fs_param_source
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u32
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:__fs_parse
  - fs/fs_parser.c:__fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff81503640-ffffffff81503836: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void logfc(struct fc_log *log, const char *prefix, char level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81538290)
Location: fs/fs_context.c:436
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:setup_bdev_super
  - fs/super.c:setup_bdev_super
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/fs_context.c:vfs_parse_fs_param
  - fs/fs_context.c:vfs_parse_fs_param_source
  - fs/fs_context.c:vfs_parse_fs_param_source
  - fs/fs_parser.c:fs_param_is_fd
  - fs/fs_parser.c:fs_param_is_blob
  - fs/fs_parser.c:fs_param_is_string
  - fs/fs_parser.c:fs_param_is_u32
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:__fs_parse
  - fs/fs_parser.c:__fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff81538290-ffffffff81538486: logfc (STB_GLOBAL)
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
void logfc(struct fs_context *fc, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d4f70)
Location: fs/fs_context.c:388
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffff8000103d4f70-ffff8000103d51c8: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void logfc(struct fs_context *fc, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05aed50)
Location: fs/fs_context.c:388
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - drivers/mtd/mtdsuper.c:get_tree_mtd
  - drivers/mtd/mtdsuper.c:get_tree_mtd
  - drivers/mtd/mtdsuper.c:get_tree_mtd
  - drivers/mtd/mtdsuper.c:get_tree_mtd
  - drivers/mtd/mtdsuper.c:mtd_get_sb_by_nr
```
**Symbols:**

```
c05aed50-c05aef78: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void logfc(struct fs_context *fc, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d7d80)
Location: fs/fs_context.c:388
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
c0000000004d7d80-c0000000004d8048: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void logfc(struct fs_context *fc, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028f17c)
Location: fs/fs_context.c:388
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffe00028f17c-ffffffe00028f34e: logfc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void logfc(struct fs_context *fc, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (0)
Location: fs/fs_context.c:388
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff81316406-ffffffff81316456: logfc.cold (STB_LOCAL)
ffffffff813155f0-ffffffff813157db: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void logfc(struct fs_context *fc, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (0)
Location: fs/fs_context.c:388
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff81306ff6-ffffffff81307046: logfc.cold (STB_LOCAL)
ffffffff813061e0-ffffffff813063cb: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void logfc(struct fs_context *fc, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (0)
Location: fs/fs_context.c:388
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff813141f6-ffffffff81314246: logfc.cold (STB_LOCAL)
ffffffff813133e0-ffffffff813135cb: logfc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void logfc(struct fs_context *fc, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_context.c (0)
Location: fs/fs_context.c:388
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_parse_one
  - mm/shmem.c:shmem_parse_one
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_context.c:legacy_parse_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
  - fs/proc/root.c:proc_parse_param
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_parse_param
```
**Symbols:**

```
ffffffff81325a46-ffffffff81325a96: logfc.cold (STB_LOCAL)
ffffffff81324c30-ffffffff81324e1b: logfc (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fc_log *log</code>
</li>
<li>
<b>Param added. </b>
<code>const char *prefix</code>
</li>
<li>
<b>Param added. </b>
<code>char level</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fs_context *fc</code>
</li>
<li>
<b>Param reordered. </b>
<code>fc, fmt, (anon)</code> ➡️ <code>log, prefix, level, fmt, (anon)</code>
</li>
</ul>
</details>
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
