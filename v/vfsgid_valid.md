# Function: <code>vfsgid_valid</code>

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
In fs/namei.c (0)
Location: include/linux/mnt_idmapping.h:54
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/mnt_idmapping.h:54
Inline: True
```
```
In fs/attr.c (ffffffff814a59b4)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (0)
Location: include/linux/mnt_idmapping.h:54
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81528103)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff8158536a)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fa030)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:vfsgid_eq_kgid
```
```
In security/integrity/evm/evm_main.c (ffffffff81701f8d)
Location: include/linux/mnt_idmapping.h:54
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
In fs/namei.c (0)
Location: include/linux/mnt_idmapping.h:54
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/mnt_idmapping.h:54
Inline: True
```
```
In fs/attr.c (ffffffff814daa5d)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (0)
Location: include/linux/mnt_idmapping.h:54
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81560585)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815bc0b5)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In security/integrity/ima/ima_policy.c (ffffffff81734160)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:vfsgid_eq_kgid
```
```
In security/integrity/evm/evm_main.c (ffffffff8173c8b8)
Location: include/linux/mnt_idmapping.h:54
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
In mm/shmem.c (ffffffff813ec703)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
```
In fs/namei.c (0)
Location: include/linux/mnt_idmapping.h:54
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/mnt_idmapping.h:54
Inline: True
```
```
In fs/attr.c (ffffffff8150cffd)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (0)
Location: include/linux/mnt_idmapping.h:54
Inline: True
```
```
In fs/quota/dquot.c (ffffffff81596c75)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815f4e8c)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In security/integrity/ima/ima_policy.c (ffffffff81774c50)
Location: include/linux/mnt_idmapping.h:54
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:vfsgid_eq_kgid
```
```
In security/integrity/evm/evm_main.c (ffffffff8177d64b)
Location: include/linux/mnt_idmapping.h:54
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
