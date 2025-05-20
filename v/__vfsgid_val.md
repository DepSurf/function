# Function: <code>__vfsgid_val</code>

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
In kernel/capability.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/open.c (ffffffff81475acd)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/stat.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/inode.c (ffffffff814a5204)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/attr.c (ffffffff814a559c)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81528103)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff81585611)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff81600563)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In fs/fuse/acl.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fa0c0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:vfsgid_lt_kgid
  - security/integrity/ima/ima_policy.c:vfsgid_gt_kgid
  - security/integrity/ima/ima_policy.c:vfsgid_eq_kgid
```
```
In security/integrity/evm/evm_main.c (ffffffff81701f8d)
Location: include/linux/mnt_idmapping.h:33
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
In kernel/capability.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/stat.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/attr.c (ffffffff814daa5d)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/mnt_idmapping.c (ffffffff81506b55)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/mnt_idmapping.c:vfsgid_in_group_p
  - fs/mnt_idmapping.c:from_vfsgid
```
```
In fs/posix_acl.c (ffffffff8154eef6)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
```
```
In fs/quota/dquot.c (ffffffff81560585)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815bc0b5)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In security/integrity/ima/ima_policy.c (ffffffff817341f0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:vfsgid_lt_kgid
  - security/integrity/ima/ima_policy.c:vfsgid_gt_kgid
  - security/integrity/ima/ima_policy.c:vfsgid_eq_kgid
```
```
In security/integrity/evm/evm_main.c (ffffffff8173c8b8)
Location: include/linux/mnt_idmapping.h:33
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
In kernel/capability.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In mm/shmem.c (ffffffff813ec703)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
```
In fs/stat.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/attr.c (ffffffff8150cffd)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
```
```
In fs/mnt_idmapping.c (ffffffff8153b815)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/mnt_idmapping.c:vfsgid_in_group_p
```
```
In fs/posix_acl.c (ffffffff81584d36)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
```
```
In fs/quota/dquot.c (ffffffff81596c75)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815f4e8c)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In security/integrity/ima/ima_policy.c (ffffffff81774ce0)
Location: include/linux/mnt_idmapping.h:33
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:vfsgid_lt_kgid
  - security/integrity/ima/ima_policy.c:vfsgid_gt_kgid
  - security/integrity/ima/ima_policy.c:vfsgid_eq_kgid
```
```
In security/integrity/evm/evm_main.c (ffffffff8177d64b)
Location: include/linux/mnt_idmapping.h:33
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
