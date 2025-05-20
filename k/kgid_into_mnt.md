# Function: <code>kgid_into_mnt</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b11f7)
Location: include/linux/fs.h:1602
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff8132b504)
Location: include/linux/fs.h:1602
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff8132f920)
Location: include/linux/fs.h:1602
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff81337560)
Location: include/linux/fs.h:1602
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff81346dbc)
Location: include/linux/fs.h:1602
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff81349cf6)
Location: include/linux/fs.h:1602
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (ffffffff81355ac0)
Location: include/linux/fs.h:1602
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
```
In fs/posix_acl.c (ffffffff813bd8dc)
Location: include/linux/fs.h:1602
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/fat/file.c (ffffffff8147a072)
Location: include/linux/fs.h:1602
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In fs/fuse/acl.c (ffffffff814a031b)
Location: include/linux/fs.h:1602
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
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
In kernel/capability.c (ffffffff810c32b7)
Location: include/linux/fs.h:1652
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff81378c76)
Location: include/linux/fs.h:1652
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff8137d0d0)
Location: include/linux/fs.h:1652
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff81384fc0)
Location: include/linux/fs.h:1652
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff8139481c)
Location: include/linux/fs.h:1652
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff81397bea)
Location: include/linux/fs.h:1652
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (ffffffff813a3ee0)
Location: include/linux/fs.h:1652
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
```
In fs/posix_acl.c (ffffffff8140d69c)
Location: include/linux/fs.h:1652
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/fat/file.c (ffffffff814d1702)
Location: include/linux/fs.h:1652
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In fs/fuse/acl.c (ffffffff814f833b)
Location: include/linux/fs.h:1652
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
```
</details>
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
