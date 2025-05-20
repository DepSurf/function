# Function: <code>fsnotify_dentry</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff8133829b)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81343a53)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fat/file.c (ffffffff81458760)
Location: include/linux/fsnotify.h:51
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
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
In fs/attr.c (ffffffff81343bee)
Location: include/linux/fsnotify.h:78
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8134fa9d)
Location: include/linux/fsnotify.h:78
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fat/file.c (ffffffff81474acc)
Location: include/linux/fsnotify.h:78
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
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
In fs/attr.c (ffffffff81349f66)
Location: include/linux/fsnotify.h:78
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff813565c5)
Location: include/linux/fsnotify.h:78
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fat/file.c (ffffffff8147a47a)
Location: include/linux/fsnotify.h:78
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
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
In fs/attr.c (ffffffff81397cf9)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff813a4b05)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fat/file.c (ffffffff814d1ada)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
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
In fs/attr.c (ffffffff81419e24)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81428660)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/fat/file.c (ffffffff8155e75d)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
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
In fs/attr.c (ffffffff814a5e99)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff814b5b80)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/posix_acl.c (ffffffff81516078)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/fat/file.c (ffffffff81600953)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
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
In fs/attr.c (ffffffff814dae4a)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff814ea3d0)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/posix_acl.c (ffffffff8154da0f)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/fat/file.c (ffffffff81638846)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
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
In fs/attr.c (ffffffff8150d3fc)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8151e270)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_noperm
  - fs/xattr.c:__vfs_setxattr_noperm
```
```
In fs/posix_acl.c (ffffffff8158383f)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/fat/file.c (ffffffff81671d36)
Location: include/linux/fsnotify.h:87
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
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
