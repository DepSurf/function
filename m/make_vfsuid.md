# Function: <code>make_vfsuid</code>

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
In kernel/capability.c (ffffffff810fa832)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff81481498)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814836ad)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff8148d55e)
Location: include/linux/mnt_idmapping.h:192
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
In fs/inode.c (ffffffff814a24cb)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff814a5b55)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (ffffffff814b548a)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
```
```
In fs/remap_range.c (ffffffff814d0d51)
Location: include/linux/mnt_idmapping.h:192
Inline: True
```
```
In fs/posix_acl.c (ffffffff815175ed)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff81519496)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/dquot.c (ffffffff81528010)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff81585171)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff8160048f)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In security/commoncap.c (ffffffff81661db4)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/apparmor/domain.c (ffffffff816ca2c8)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff816d892a)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff816dcf6e)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fb071)
Location: include/linux/mnt_idmapping.h:192
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In security/integrity/evm/evm_main.c (ffffffff81701f11)
Location: include/linux/mnt_idmapping.h:192
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vfsuid_t make_vfsuid(struct mnt_idmap *idmap, struct user_namespace *fs_userns, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff81506970)
Location: fs/mnt_idmapping.c:96
Inline: False
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - fs/stat.c:generic_fillattr
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:may_write_xattr
  - fs/locks.c:generic_setlease
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_transfer
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/file.c:__file_path_perm
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff81506970-ffffffff815069c1: make_vfsuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vfsuid_t make_vfsuid(struct mnt_idmap *idmap, struct user_namespace *fs_userns, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff8153b690)
Location: fs/mnt_idmapping.c:70
Inline: False
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/stat.c:generic_fillattr
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:may_write_xattr
  - fs/locks.c:generic_setlease
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_transfer
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/file.c:__file_path_perm
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff8153b690-ffffffff8153b6da: make_vfsuid (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
