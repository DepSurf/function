# Function: <code>i_uid_into_vfsuid</code>

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
In <code>5.19</code>: Absent ⚠️
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
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff81481475)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814836a1)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff8148d553)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff814a24c1)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff814a5b4a)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (ffffffff814b5480)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
```
```
In fs/remap_range.c (ffffffff814d0d43)
Location: include/linux/fs.h:1645
Inline: True
```
```
In fs/posix_acl.c (ffffffff8151707d)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff8151948b)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81528006)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff81585162)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff81600484)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In security/apparmor/domain.c (ffffffff816ca2b1)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff816d891c)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff816dcf63)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fb063)
Location: include/linux/fs.h:1645
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In security/integrity/evm/evm_main.c (ffffffff81701f03)
Location: include/linux/fs.h:1645
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
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff814b60b0)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814bb5ae)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814c34d2)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff814d7055)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff814dab97)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (ffffffff814ea00c)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
```
```
In fs/remap_range.c (ffffffff815078b4)
Location: include/linux/fs.h:1325
Inline: True
```
```
In fs/locks.c (ffffffff81543e33)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
```
```
In fs/posix_acl.c (ffffffff8154e92d)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff81550da3)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81560513)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815bbadc)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff81638446)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In security/apparmor/domain.c (ffffffff81702f63)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff8171176a)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff8171655e)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff8173517b)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In security/integrity/evm/evm_main.c (ffffffff8173c85e)
Location: include/linux/fs.h:1325
Inline: True
Inline callers:
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
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In mm/shmem.c (ffffffff813ec5cc)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
```
In fs/stat.c (ffffffff814e83c5)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814edb1e)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814f59a2)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff815093d5)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff8150d149)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (ffffffff8151deac)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
```
```
In fs/remap_range.c (ffffffff8153bfdc)
Location: include/linux/fs.h:1370
Inline: True
```
```
In fs/locks.c (ffffffff81579312)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
```
```
In fs/posix_acl.c (ffffffff8158477d)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff81586c34)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81596c03)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815f48b5)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff81671936)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In security/apparmor/domain.c (ffffffff81740753)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff8174fad1)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff8175502e)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff81775c6a)
Location: include/linux/fs.h:1370
Inline: True
```
```
In security/integrity/evm/evm_main.c (ffffffff8177d65d)
Location: include/linux/fs.h:1370
Inline: True
Inline callers:
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
