# Function: <code>current_fs_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct timespec current_fs_time(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eb080)
Location: kernel/time/time.c:240
Inline: False
Direct callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
  - fs/inode.c:touch_atime
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/locks.c:lease_get_mtime
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fuse/dir.c:fuse_removexattr
  - fs/fuse/dir.c:fuse_setxattr
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
```
**Symbols:**

```
ffffffff810eb080-ffffffff810eb0a6: current_fs_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct timespec current_fs_time(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1d50)
Location: kernel/time/time.c:240
Inline: False
Direct callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:touch_atime
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/bad_inode.c:make_bad_inode
  - fs/locks.c:lease_get_mtime
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fat/file.c:fat_generic_ioctl
  - fs/fuse/dir.c:fuse_removexattr
  - fs/fuse/dir.c:fuse_setxattr
  - fs/fuse/dir.c:fuse_link
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/debugfs/inode.c:debugfs_get_inode
```
**Symbols:**

```
ffffffff810f1d50-ffffffff810f1d76: current_fs_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct timespec current_fs_time(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8ed0)
Location: kernel/time/time.c:240
Inline: False
```
**Symbols:**

```
ffffffff810f8ed0-ffffffff810f8ef6: current_fs_time (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
