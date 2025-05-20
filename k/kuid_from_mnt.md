# Function: <code>kuid_from_mnt</code>

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
In fs/open.c (ffffffff81321695)
Location: include/linux/fs.h:1644
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/namei.c (ffffffff81335e6a)
Location: include/linux/fs.h:1644
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff81346d84)
Location: include/linux/fs.h:1644
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
```
```
In fs/posix_acl.c (ffffffff813bd8b0)
Location: include/linux/fs.h:1644
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
```
```
In fs/ext4/ialloc.c (ffffffff814067a1)
Location: include/linux/fs.h:1644
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In security/commoncap.c (ffffffff814c9fe9)
Location: include/linux/fs.h:1644
Inline: True
Inline callers:
  - security/commoncap.c:cap_convert_nscap
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
In fs/open.c (ffffffff8136eb75)
Location: include/linux/fs.h:1694
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/namei.c (ffffffff81383953)
Location: include/linux/fs.h:1694
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/inode.c (ffffffff813947e4)
Location: include/linux/fs.h:1694
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
```
```
In fs/posix_acl.c (ffffffff8140d670)
Location: include/linux/fs.h:1694
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
```
```
In fs/ext4/ialloc.c (ffffffff81459016)
Location: include/linux/fs.h:1694
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In security/commoncap.c (ffffffff81522c89)
Location: include/linux/fs.h:1694
Inline: True
Inline callers:
  - security/commoncap.c:cap_convert_nscap
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
