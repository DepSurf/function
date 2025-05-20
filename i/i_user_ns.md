# Function: <code>i_user_ns</code>

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
In kernel/capability.c (ffffffff810da755)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/open.c (ffffffff813ed3ad)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/stat.c (ffffffff813f8033)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff813f9db1)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff81403133)
Location: include/linux/fs.h:1568
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
In fs/inode.c (ffffffff81416ee1)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/inode.c:inode_init_owner
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/attr.c (ffffffff81419b1a)
Location: include/linux/fs.h:1568
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
```
```
In fs/xattr.c (ffffffff81427d45)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
  - fs/xattr.c:xattr_permission
```
```
In fs/remap_range.c (ffffffff81441a7e)
Location: include/linux/fs.h:1568
Inline: True
```
```
In fs/posix_acl.c (ffffffff81484042)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_to_user
  - fs/posix_acl.c:posix_acl_fix_xattr_from_user
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff81485cc7)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ialloc.c (ffffffff814d65c5)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff814e61bf)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff814edee3)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff814fd11e)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8151896d)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff81531d0e)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/squashfs/inode.c (ffffffff8154f082)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fat/file.c (ffffffff8155e30e)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
```
```
In fs/ecryptfs/main.c (ffffffff81568571)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/fuse/acl.c (0)
Location: include/linux/fs.h:1568
Inline: True
```
```
In security/apparmor/domain.c (ffffffff8161743d)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81624b24)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff816287b8)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff81642df1)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81646c62)
Location: include/linux/fs.h:1568
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
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
In kernel/capability.c (ffffffff810fa815)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/open.c (ffffffff81475a20)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/stat.c (ffffffff81481475)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814836a1)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff8148d553)
Location: include/linux/fs.h:1607
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
In fs/inode.c (ffffffff814a2801)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/attr.c (ffffffff814a5b4a)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
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
In fs/xattr.c (ffffffff814b5480)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
  - fs/xattr.c:may_write_xattr
```
```
In fs/remap_range.c (ffffffff814d0d43)
Location: include/linux/fs.h:1607
Inline: True
```
```
In fs/posix_acl.c (ffffffff81517526)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff8151948b)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff8152805a)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/ialloc.c (ffffffff8156f381)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81585641)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff81587dc0)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff815978e1)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff815b455a)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff815ce79d)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In fs/squashfs/inode.c (ffffffff815efb2c)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fat/file.c (ffffffff81600312)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
```
```
In fs/ecryptfs/main.c (ffffffff8160bcdf)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/fuse/acl.c (ffffffff8162e7e3)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In security/apparmor/domain.c (ffffffff816ca2b1)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff816d891c)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff816dcf63)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fb063)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff816ff392)
Location: include/linux/fs.h:1607
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
```
```
In security/integrity/evm/evm_main.c (ffffffff81701f03)
Location: include/linux/fs.h:1607
Inline: True
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
In kernel/capability.c (ffffffff811068ae)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/open.c (ffffffff814aa3ba)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/stat.c (ffffffff814b60b0)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814bb5ae)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814c34d2)
Location: include/linux/fs.h:1287
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
In fs/inode.c (ffffffff814d7972)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/attr.c (ffffffff814dab97)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
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
In fs/xattr.c (ffffffff814ea00c)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
  - fs/xattr.c:may_write_xattr
```
```
In fs/remap_range.c (ffffffff815078b4)
Location: include/linux/fs.h:1287
Inline: True
```
```
In fs/locks.c (ffffffff81543e33)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
```
```
In fs/posix_acl.c (ffffffff8154ee43)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff81550da3)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81560530)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/ialloc.c (ffffffff815a71be)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff815bbeba)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff815be640)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff815ce31a)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff815eb2ba)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8160606d)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In fs/squashfs/inode.c (ffffffff81627af2)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fat/file.c (ffffffff816382ed)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
```
```
In fs/ecryptfs/main.c (ffffffff81643bbf)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/fuse/acl.c (ffffffff81666b3a)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In security/apparmor/domain.c (ffffffff81702f63)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff8171176a)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff8171655e)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff8173517b)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81739405)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
```
```
In security/integrity/evm/evm_main.c (ffffffff8173c85e)
Location: include/linux/fs.h:1287
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_inode_setattr
  - security/integrity/evm/evm_main.c:evm_inode_setattr
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
In kernel/capability.c (ffffffff811101fe)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In mm/shmem.c (ffffffff813ec5cc)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
```
In fs/open.c (ffffffff814db85a)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/stat.c (ffffffff814e83c5)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814edb1e)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814f59a2)
Location: include/linux/fs.h:1332
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
In fs/inode.c (ffffffff81509d62)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/inode.c:inode_init_always
```
```
In fs/attr.c (ffffffff8150d149)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
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
In fs/xattr.c (ffffffff8151deac)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
  - fs/xattr.c:may_write_xattr
```
```
In fs/remap_range.c (ffffffff8153bfdc)
Location: include/linux/fs.h:1332
Inline: True
```
```
In fs/locks.c (ffffffff81579312)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
```
```
In fs/posix_acl.c (ffffffff81584c83)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff81586c34)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81596c20)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/ialloc.c (ffffffff815e0012)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff815f4ada)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/ioctl.c (ffffffff815f73f9)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/migrate.c (ffffffff81606b9a)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81623caa)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8163ed8d)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In fs/squashfs/inode.c (ffffffff81660c52)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fat/file.c (ffffffff816717dd)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
```
```
In fs/ecryptfs/main.c (ffffffff8167d14f)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/fuse/acl.c (ffffffff816a0e4a)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_set_acl
  - fs/fuse/acl.c:fuse_get_acl
```
```
In security/apparmor/domain.c (ffffffff81740753)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff8174fad1)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff8175502e)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff81775c6a)
Location: include/linux/fs.h:1332
Inline: True
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81779f25)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
```
```
In security/integrity/evm/evm_main.c (ffffffff8177d65d)
Location: include/linux/fs.h:1332
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_inode_setattr
  - security/integrity/evm/evm_main.c:evm_inode_setattr
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
