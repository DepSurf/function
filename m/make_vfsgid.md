# Function: <code>make_vfsgid</code>

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
In kernel/capability.c (ffffffff810fa88d)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff814814df)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814836f7)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff8148d5ad)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff814a280b)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff814a5dec)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_should_drop_suidgid
```
```
In fs/xattr.c (ffffffff814b54c8)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
```
```
In fs/posix_acl.c (ffffffff8151756c)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/quota/dquot.c (ffffffff815280c2)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff81585332)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff81600503)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In fs/fuse/acl.c (ffffffff8162e8fa)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fb0df)
Location: include/linux/mnt_idmapping.h:230
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In security/integrity/evm/evm_main.c (ffffffff81701f5d)
Location: include/linux/mnt_idmapping.h:230
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vfsgid_t make_vfsgid(struct mnt_idmap *idmap, struct user_namespace *fs_userns, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff81506a60)
Location: fs/mnt_idmapping.c:135
Inline: False
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - fs/stat.c:generic_fillattr
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_should_drop_suidgid
  - fs/xattr.c:may_write_xattr
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/quota/dquot.c:dquot_transfer
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fuse/acl.c:fuse_set_acl
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff81506a60-ffffffff81506ab1: make_vfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vfsgid_t make_vfsgid(struct mnt_idmap *idmap, struct user_namespace *fs_userns, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff8153b6f0)
Location: fs/mnt_idmapping.c:108
Inline: False
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/stat.c:generic_fillattr
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_should_drop_suidgid
  - fs/xattr.c:may_write_xattr
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/quota/dquot.c:dquot_transfer
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fuse/acl.c:fuse_set_acl
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
**Symbols:**

```
ffffffff8153b6f0-ffffffff8153b73b: make_vfsgid (STB_GLOBAL)
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
