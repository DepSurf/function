# Function: <code>d_make_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812259f0)
Location: fs/dcache.c:1886
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/proc/inode.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/devpts/inode.c:devpts_mount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff812259f0-ffffffff81225a44: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124db30)
Location: fs/dcache.c:1847
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/proc/inode.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/devpts/inode.c:devpts_mount
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff8124db30-ffffffff8124db7f: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81260c10)
Location: fs/dcache.c:1856
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/proc/inode.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81260c10-ffffffff81260c5f: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126e3e0)
Location: fs/dcache.c:1886
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/proc/inode.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff8126e3e0-ffffffff8126e429: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81290d00)
Location: fs/dcache.c:1898
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/proc/inode.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81290d00-ffffffff81290d49: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b7510)
Location: fs/dcache.c:1928
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/proc/inode.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff812b7510-ffffffff812b7562: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cc670)
Location: fs/dcache.c:1909
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/proc/inode.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff812cc670-ffffffff812cc6c2: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e9260)
Location: fs/dcache.c:1983
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff812e9260-ffffffff812e92b0: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fae00)
Location: fs/dcache.c:1983
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff812fae00-ffffffff812fae50: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81331550)
Location: fs/dcache.c:2004
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/configfs/mount.c:configfs_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81331550-ffffffff813315a0: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133cee0)
Location: fs/dcache.c:2011
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/configfs/mount.c:configfs_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff8133cee0-ffffffff8133cf30: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81343360)
Location: fs/dcache.c:2038
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81343360-ffffffff813433b0: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81390eb0)
Location: fs/dcache.c:2039
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81390eb0-ffffffff81390f42: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814128e0)
Location: fs/dcache.c:2064
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff814128e0-ffffffff81412971: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149db40)
Location: fs/dcache.c:2064
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff8149db40-ffffffff8149dbd1: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d2f80)
Location: fs/dcache.c:2064
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff814d2f80-ffffffff814d3011: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81505810)
Location: fs/dcache.c:1908
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/nsfs.c:__ns_get_path
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff81505810-ffffffff815058a1: d_make_root (STB_GLOBAL)
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
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103aa0f0)
Location: fs/dcache.c:1983
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffff8000103aa0f0-ffff8000103aa154: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058b110)
Location: fs/dcache.c:1983
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
c058b110-c058b164: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a4f20)
Location: fs/dcache.c:1983
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/pstore/inode.c:pstore_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
c0000000004a4f20-c0000000004a4fb8: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026fe9c)
Location: fs/dcache.c:1983
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/pstore/inode.c:pstore_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffe00026fe9c-ffffffe00026fef8: d_make_root (STB_GLOBAL)
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
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f33e0)
Location: fs/dcache.c:1983
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff812f33e0-ffffffff812f3430: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e4010)
Location: fs/dcache.c:1983
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff812e4010-ffffffff812e4060: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f11f0)
Location: fs/dcache.c:1983
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff812f11f0-ffffffff812f1240: d_make_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *d_make_root(struct inode *root_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813023b0)
Location: fs/dcache.c:1983
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fill_super
  - fs/libfs.c:simple_fill_super
  - fs/libfs.c:pseudo_fs_fill_super
  - fs/proc/root.c:proc_fill_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/configfs/mount.c:configfs_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/pstore/inode.c:pstore_fill_super
  - fs/efivarfs/super.c:efivarfs_fill_super
  - ipc/mqueue.c:mqueue_fill_super
```
**Symbols:**

```
ffffffff813023b0-ffffffff81302400: d_make_root (STB_GLOBAL)
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
