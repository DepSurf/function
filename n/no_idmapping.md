# Function: <code>no_idmapping</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810da772)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/open.c (ffffffff813ed3b8)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/stat.c (ffffffff813f8041)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff813f9dbc)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff8140313e)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff81416eeb)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/inode.c:inode_init_owner
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff81419b29)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (ffffffff81427d53)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
  - fs/xattr.c:xattr_permission
```
```
In fs/remap_range.c (ffffffff81441a90)
Location: include/linux/mnt_idmapping.h:44
Inline: True
```
```
In fs/posix_acl.c (ffffffff81484042)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff81485cd6)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ialloc.c (ffffffff814d71c2)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/fat/file.c (ffffffff8155e319)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
```
```
In fs/fuse/acl.c (0)
Location: include/linux/mnt_idmapping.h:44
Inline: True
```
```
In security/commoncap.c (ffffffff815b6bf5)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/apparmor/domain.c (ffffffff81617451)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81624b33)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff816287c6)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff81642dfc)
Location: include/linux/mnt_idmapping.h:44
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_match_rules
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
In kernel/capability.c (ffffffff810fa832)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/open.c (ffffffff81475ab7)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/stat.c (ffffffff81481498)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814836ad)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff8148d55e)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff814a280b)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff814a5d87)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_should_drop_suidgid
```
```
In fs/xattr.c (ffffffff814b548a)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
  - fs/xattr.c:may_write_xattr
```
```
In fs/remap_range.c (ffffffff814d0d51)
Location: include/linux/mnt_idmapping.h:165
Inline: True
```
```
In fs/posix_acl.c (ffffffff8151756c)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff81519496)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81528066)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/ialloc.c (ffffffff8156ff40)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81585650)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff81600320)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
```
```
In fs/fuse/acl.c (0)
Location: include/linux/mnt_idmapping.h:165
Inline: True
```
```
In security/commoncap.c (ffffffff81661db4)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/apparmor/domain.c (ffffffff816ca2c8)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff816d892a)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff816dcf6e)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fb071)
Location: include/linux/mnt_idmapping.h:165
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In security/integrity/evm/evm_main.c (ffffffff81701f11)
Location: include/linux/mnt_idmapping.h:165
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff81506ad8)
Location: fs/mnt_idmapping.c:69
Inline: True
Inline callers:
  - fs/mnt_idmapping.c:from_vfsgid
  - fs/mnt_idmapping.c:from_vfsuid
  - fs/mnt_idmapping.c:make_vfsgid
  - fs/mnt_idmapping.c:make_vfsuid
```
</details>
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
