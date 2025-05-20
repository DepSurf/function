# Function: <code>clear_nlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8122779d)
Location: fs/inode.c:288
Inline: True
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff81227af0-ffffffff81227b15: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124ff2d)
Location: fs/inode.c:295
Inline: True
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff81250220-ffffffff81250245: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262fcd)
Location: fs/inode.c:297
Inline: True
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812631f0-ffffffff81263215: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81270870)
Location: fs/inode.c:298
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff81270a00-ffffffff81270a25: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812931b0)
Location: fs/inode.c:298
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff81293330-ffffffff81293357: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8e20)
Location: fs/inode.c:300
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812b9040-ffffffff812b9066: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cdf60)
Location: fs/inode.c:300
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812ce180-ffffffff812ce1a6: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eada0)
Location: fs/inode.c:313
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812eb040-ffffffff812eb065: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc8d0)
Location: fs/inode.c:317
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812fcb80-ffffffff812fcba5: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335170)
Location: fs/inode.c:318
Inline: True
Direct callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rmdir
```
**Symbols:**

```
ffffffff813353f0-ffffffff81335415: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81340ae0)
Location: fs/inode.c:319
Inline: True
Direct callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rmdir
```
**Symbols:**

```
ffffffff81340d60-ffffffff81340d85: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81346f60)
Location: fs/inode.c:319
Inline: True
Direct callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rmdir
```
**Symbols:**

```
ffffffff81347150-ffffffff81347175: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813949c0)
Location: fs/inode.c:323
Inline: True
Direct callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rmdir
```
**Symbols:**

```
ffffffff81394bb0-ffffffff81394bd5: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81416ba0)
Location: fs/inode.c:347
Inline: True
Direct callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_entry_unlinked
```
**Symbols:**

```
ffffffff81416ea0-ffffffff81416ecd: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a2030)
Location: fs/inode.c:345
Inline: True
Direct callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_entry_unlinked
```
**Symbols:**

```
ffffffff814a2210-ffffffff814a223d: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d71c0)
Location: fs/inode.c:345
Inline: True
Direct callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_entry_unlinked
```
**Symbols:**

```
ffffffff814d7440-ffffffff814d746d: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81509540)
Location: fs/inode.c:346
Inline: True
Direct callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_entry_unlinked
```
**Symbols:**

```
ffffffff81509750-ffffffff8150977d: clear_nlink (STB_GLOBAL)
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
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ac6b8)
Location: fs/inode.c:317
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffff8000103ac6b8-ffff8000103ac720: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (c058d634)
Location: fs/inode.c:317
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
c058d634-c058d674: clear_nlink.part.0 (STB_LOCAL)
c058d674-c058d69c: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a7954)
Location: fs/inode.c:317
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
c0000000004a84f0-c0000000004a8528: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe0002708f6)
Location: fs/inode.c:317
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffe0002708f6-ffffffe00027092a: clear_nlink (STB_GLOBAL)
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
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4eb0)
Location: fs/inode.c:317
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812f5160-ffffffff812f5185: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5ad0)
Location: fs/inode.c:317
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812e5d80-ffffffff812e5da5: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2cc0)
Location: fs/inode.c:317
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812f2f70-ffffffff812f2f95: clear_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clear_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813043d0)
Location: fs/inode.c:317
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff813048a0-ffffffff813048c5: clear_nlink (STB_GLOBAL)
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
