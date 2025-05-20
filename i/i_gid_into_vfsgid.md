# Function: <code>i_gid_into_vfsgid</code>

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
In kernel/capability.c (ffffffff810fa87f)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff814814d1)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814836e6)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff8148d59e)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff814a2801)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff814a5ddd)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_should_drop_suidgid
```
```
In fs/xattr.c (ffffffff814b54ba)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
```
```
In fs/posix_acl.c (ffffffff81515e08)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/quota/dquot.c (ffffffff815280b1)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff81585323)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff816004f4)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In fs/fuse/acl.c (ffffffff8162e8fa)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fb0d1)
Location: include/linux/fs.h:1697
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In security/integrity/evm/evm_main.c (ffffffff81701f4e)
Location: include/linux/fs.h:1697
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
In kernel/capability.c (ffffffff811068e0)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff814b60d5)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814bb5cd)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814c34ef)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff814d7972)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff814dabdd)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_should_drop_suidgid
```
```
In fs/xattr.c (ffffffff814ea034)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
```
```
In fs/posix_acl.c (ffffffff8154d23f)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/quota/dquot.c (ffffffff81560567)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815bc096)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff81638479)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In fs/fuse/acl.c (ffffffff81666b3a)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
```
```
In security/integrity/ima/ima_policy.c (ffffffff817351be)
Location: include/linux/fs.h:1377
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
```
In security/integrity/evm/evm_main.c (ffffffff8173c899)
Location: include/linux/fs.h:1377
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
In kernel/capability.c (ffffffff81110230)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In mm/shmem.c (ffffffff813ec6e7)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
```
In fs/stat.c (ffffffff814e83ea)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff814edb3d)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814f59bf)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff81509d62)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff8150d18f)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_should_drop_suidgid
```
```
In fs/xattr.c (ffffffff8151ded4)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - fs/xattr.c:may_write_xattr
```
```
In fs/posix_acl.c (ffffffff8158306f)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/quota/dquot.c (ffffffff81596c57)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815f4e6d)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff81671969)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In fs/fuse/acl.c (ffffffff816a0e4a)
Location: include/linux/fs.h:1422
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
```
```
In security/integrity/ima/ima_policy.c (ffffffff81775cac)
Location: include/linux/fs.h:1422
Inline: True
```
```
In security/integrity/evm/evm_main.c (ffffffff8177d62c)
Location: include/linux/fs.h:1422
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
