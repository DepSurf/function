# Function: <code>kuid_into_mnt</code>

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
In kernel/capability.c (ffffffff810b11ce)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff8132b4f6)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff8132f90c)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff8133754e)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff81346e45)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff81349ce1)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (ffffffff81355aaf)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
```
In fs/remap_range.c (ffffffff8136cb99)
Location: include/linux/fs.h:1588
Inline: True
```
```
In fs/posix_acl.c (ffffffff813bd8e5)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff813c04a4)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/fat/file.c (ffffffff8147a041)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In security/commoncap.c (ffffffff814ca1f7)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/apparmor/domain.c (ffffffff8151b2cd)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81526cf2)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff81529d46)
Location: include/linux/fs.h:1588
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff8153e66e)
Location: include/linux/fs.h:1588
Inline: True
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
In kernel/capability.c (ffffffff810c328e)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff81378c66)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff8137d0bc)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff81384fae)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff813948a5)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff81397a94)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (ffffffff813a3ecf)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
```
In fs/remap_range.c (ffffffff813bb859)
Location: include/linux/fs.h:1638
Inline: True
```
```
In fs/posix_acl.c (ffffffff8140d6a5)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff814102cc)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/fat/file.c (ffffffff814d16d1)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In security/commoncap.c (ffffffff81522e97)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/apparmor/domain.c (ffffffff8157934d)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81584f82)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff815880e6)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159d9ec)
Location: include/linux/fs.h:1638
Inline: True
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
