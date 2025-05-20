# Function: <code>drop_nlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812277e0)
Location: fs/inode.c:271
Inline: True
Direct callers:
  - mm/shmem.c:shmem_unlink
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_unlink
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_link
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff812277e0-ffffffff81227823: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124ff70)
Location: fs/inode.c:278
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff8124ff70-ffffffff8124ffb3: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81263010)
Location: fs/inode.c:280
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff81263010-ffffffff81263053: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812708a0)
Location: fs/inode.c:281
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff812708a0-ffffffff812708d3: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812931e0)
Location: fs/inode.c:281
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff812931e0-ffffffff81293213: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8e50)
Location: fs/inode.c:283
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff812b8e50-ffffffff812b8e83: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cdf90)
Location: fs/inode.c:283
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff812cdf90-ffffffff812cdfc3: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812eadf0)
Location: fs/inode.c:296
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff812ecf43-ffffffff812ecf59: drop_nlink.cold (STB_LOCAL)
ffffffff812eadd0-ffffffff812eadff: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc900)
Location: fs/inode.c:300
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff812fc900-ffffffff812fc933: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335320)
Location: fs/inode.c:301
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff81335320-ffffffff81335353: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81340c90)
Location: fs/inode.c:302
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff81340c90-ffffffff81340cc3: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81347080)
Location: fs/inode.c:302
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff81347080-ffffffff813470b3: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81394ae0)
Location: fs/inode.c:306
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff81394ae0-ffffffff81394b13: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81416db0)
Location: fs/inode.c:330
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff81416db0-ffffffff81416df1: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a21b0)
Location: fs/inode.c:328
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff814a21b0-ffffffff814a21f1: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d7370)
Location: fs/inode.c:328
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff814d7370-ffffffff814d73b1: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff815096f0)
Location: fs/inode.c:329
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rename_exchange
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_recursive_removal
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_link
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename_exchange
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_entry_unlinked
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff815096f0-ffffffff81509731: drop_nlink (STB_GLOBAL)
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
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ac720)
Location: fs/inode.c:300
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffff8000103ac720-ffff8000103ac79c: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058d700)
Location: fs/inode.c:300
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_update_dir_count
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
c058d700-c058d774: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a79b0)
Location: fs/inode.c:300
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
c0000000004a79b0-c0000000004a79f4: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000270cb2)
Location: fs/inode.c:300
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffe000270cb2-ffffffe000270cfa: drop_nlink (STB_GLOBAL)
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
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4ee0)
Location: fs/inode.c:300
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff812f4ee0-ffffffff812f4f13: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5b00)
Location: fs/inode.c:300
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff812e5b00-ffffffff812e5b33: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2cf0)
Location: fs/inode.c:300
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff812f2cf0-ffffffff812f2d23: drop_nlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void drop_nlink(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81304400)
Location: fs/inode.c:300
Inline: True
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_unlink
  - fs/dcache.c:d_tmpfile
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rename
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_rmdir
  - fs/libfs.c:simple_unlink
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:ext4_symlink
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/efivarfs/inode.c:efivarfs_unlink
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/mqueue.c:mqueue_unlink
```
**Symbols:**

```
ffffffff81304400-ffffffff81304433: drop_nlink (STB_GLOBAL)
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
