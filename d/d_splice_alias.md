# Function: <code>d_splice_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81224cd0)
Location: fs/dcache.c:2768
Inline: False
Direct callers:
  - fs/dcache.c:d_add_ci
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff81224cd0-ffffffff81224f74: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124ced0)
Location: fs/dcache.c:2940
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff8124ced0-ffffffff8124d2a8: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125ff90)
Location: fs/dcache.c:2950
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff8125ff90-ffffffff81260368: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126d8c0)
Location: fs/dcache.c:2980
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff8126d8c0-ffffffff8126dcb1: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81290360)
Location: fs/dcache.c:2992
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff81290360-ffffffff81290751: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2977
Inline: True
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff812b7fe2-ffffffff812b8011: d_splice_alias.cold.54 (STB_LOCAL)
ffffffff812b6b10-ffffffff812b6ee6: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dcache.c (ffffffff812cbcd4)
Location: fs/dcache.c:2931
Inline: True
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff812cd142-ffffffff812cd170: d_splice_alias.cold.52 (STB_LOCAL)
ffffffff812cbca0-ffffffff812cc07b: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:3000
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff812e9e2c-ffffffff812e9e5b: d_splice_alias.cold (STB_LOCAL)
ffffffff812e82c0-ffffffff812e86b2: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:3000
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff812fb8ce-ffffffff812fb8fd: d_splice_alias.cold (STB_LOCAL)
ffffffff812f9e50-ffffffff812fa242: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:3021
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff813345ae-ffffffff813345dd: d_splice_alias.cold (STB_LOCAL)
ffffffff81333060-ffffffff81333303: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:3028
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff81bea6e0-ffffffff81bea70f: d_splice_alias.cold (STB_LOCAL)
ffffffff8133e9c0-ffffffff8133ec63: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:3054
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff81bdc71c-ffffffff81bdc74b: d_splice_alias.cold (STB_LOCAL)
ffffffff81344db0-ffffffff81345053: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:3056
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff81cc3b6f-ffffffff81cc3b9e: d_splice_alias.cold (STB_LOCAL)
ffffffff813928a0-ffffffff81392b43: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:3080
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff81e763a3-ffffffff81e763cb: d_splice_alias.cold (STB_LOCAL)
ffffffff81414140-ffffffff81414403: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149f5c0)
Location: fs/dcache.c:3136
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff8149f5c0-ffffffff8149f8a1: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d48e0)
Location: fs/dcache.c:3136
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff814d48e0-ffffffff814d4bc1: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81506c20)
Location: fs/dcache.c:2963
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/ext4/namei.c:ext4_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff81506c20-ffffffff81506f01: d_splice_alias (STB_GLOBAL)
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
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a89d0)
Location: fs/dcache.c:3000
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffff8000103a89d0-ffff8000103a8f0c: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058a058)
Location: fs/dcache.c:3000
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c058a058-c058a4f4: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a34f0)
Location: fs/dcache.c:3000
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c0000000004a34f0-c0000000004a3b48: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026ed6c)
Location: fs/dcache.c:3000
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe00026ed6c-ffffffe00026f214: d_splice_alias (STB_GLOBAL)
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
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:3000
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff812f3eae-ffffffff812f3edd: d_splice_alias.cold (STB_LOCAL)
ffffffff812f2430-ffffffff812f2822: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:3000
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff812e4ade-ffffffff812e4b0d: d_splice_alias.cold (STB_LOCAL)
ffffffff812e3060-ffffffff812e3452: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:3000
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff812f1cbe-ffffffff812f1ced: d_splice_alias.cold (STB_LOCAL)
ffffffff812f0240-ffffffff812f0632: d_splice_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *d_splice_alias(struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:3000
Inline: False
Direct callers:
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/kernfs/dir.c:kernfs_iop_lookup
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff81302ede-ffffffff81302f0d: d_splice_alias.cold (STB_LOCAL)
ffffffff81301330-ffffffff813017fc: d_splice_alias (STB_GLOBAL)
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
