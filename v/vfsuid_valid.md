# Function: <code>vfsuid_valid</code>

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
In fs/namei.c (ffffffff8148efe1)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/inode.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/attr.c (ffffffff814a599e)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81528051)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815851a9)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fa000)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:vfsuid_eq_kuid
```
```
In security/integrity/evm/evm_main.c (ffffffff81701f41)
Location: include/linux/mnt_idmapping.h:49
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
In fs/namei.c (ffffffff814c47a0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/inode.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/attr.c (ffffffff814daa44)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/posix_acl.c (ffffffff8154ea06)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81560527)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815bbafb)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In security/commoncap.c (ffffffff8169a3ca)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
```
```
In security/integrity/ima/ima_policy.c (ffffffff81734130)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:vfsuid_eq_kuid
```
```
In security/integrity/evm/evm_main.c (ffffffff8173c87d)
Location: include/linux/mnt_idmapping.h:49
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
In mm/shmem.c (ffffffff813ec5e8)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
```
In fs/namei.c (ffffffff814f6f80)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/inode.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/attr.c (ffffffff8150cfe4)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/remap_range.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/locks.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/posix_acl.c (ffffffff81584856)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81596c17)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815f48d4)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (0)
Location: include/linux/mnt_idmapping.h:49
Inline: True
```
```
In security/commoncap.c (ffffffff816d6b0a)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
```
```
In security/integrity/ima/ima_policy.c (ffffffff81774c20)
Location: include/linux/mnt_idmapping.h:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:vfsuid_eq_kuid
```
```
In security/integrity/evm/evm_main.c (ffffffff8177d67c)
Location: include/linux/mnt_idmapping.h:49
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
