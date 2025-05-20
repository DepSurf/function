# Function: <code>ext4_current_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81294fb8)
Location: fs/ext4/ext4.h:1429
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8129cb2b)
Location: fs/ext4/ext4.h:1429
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff812a13b1)
Location: fs/ext4/ext4.h:1429
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/namei.c (ffffffff812a1a10)
Location: fs/ext4/ext4.h:1429
Inline: True
Inline callers:
  - fs/ext4/namei.c:add_dirent_to_buf
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
```
```
In fs/ext4/extents.c (ffffffff812c34b8)
Location: fs/ext4/ext4.h:1429
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/xattr.c (ffffffff812de70a)
Location: fs/ext4/ext4.h:1429
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/inline.c (ffffffff812e03c3)
Location: fs/ext4/ext4.h:1429
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/acl.c (ffffffff812e3e61)
Location: fs/ext4/ext4.h:1429
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
**Symbols:**

```
ffffffff812a1a10-ffffffff812a1a30: ext4_current_time.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812c26be)
Location: fs/ext4/ext4.h:1526
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff812cd351)
Location: fs/ext4/ext4.h:1526
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff812cffd1)
Location: fs/ext4/ext4.h:1526
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/namei.c (ffffffff812d6ad4)
Location: fs/ext4/ext4.h:1526
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_link
  - fs/ext4/namei.c:add_dirent_to_buf
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
```
```
In fs/ext4/extents.c (ffffffff812f9e74)
Location: fs/ext4/ext4.h:1526
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/xattr.c (ffffffff8130e3ab)
Location: fs/ext4/ext4.h:1526
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/ext4/inline.c (ffffffff8131285b)
Location: fs/ext4/ext4.h:1526
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/acl.c (ffffffff81313e26)
Location: fs/ext4/ext4.h:1526
Inline: True
Inline callers:
  - fs/ext4/acl.c:__ext4_set_acl
```
**Symbols:**

```
ffffffff812d0940-ffffffff812d0960: ext4_current_time.isra.21 (STB_LOCAL)
```
</details>
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
