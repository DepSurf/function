# Function: <code>from_vfsgid</code>

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
In fs/open.c (ffffffff81475ab7)
Location: include/linux/mnt_idmapping.h:323
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/namei.c (ffffffff8148c0c0)
Location: include/linux/mnt_idmapping.h:323
Inline: True
```
```
In fs/inode.c (ffffffff814a1ef7)
Location: include/linux/mnt_idmapping.h:323
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
```
```
In fs/attr.c (ffffffff814a5bb4)
Location: include/linux/mnt_idmapping.h:323
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
```
```
In fs/posix_acl.c (ffffffff81515ace)
Location: include/linux/mnt_idmapping.h:323
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff8152811c)
Location: include/linux/mnt_idmapping.h:323
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815855fd)
Location: include/linux/mnt_idmapping.h:323
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff81600555)
Location: include/linux/mnt_idmapping.h:323
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
kgid_t from_vfsgid(struct mnt_idmap *idmap, struct user_namespace *fs_userns, vfsgid_t vfsgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff81506ad0)
Location: fs/mnt_idmapping.c:192
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
  - fs/inode.c:inode_init_owner
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/posix_acl.c:vfs_set_acl
  - fs/quota/dquot.c:dquot_transfer
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81506ad0-ffffffff81506b31: from_vfsgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
kgid_t from_vfsgid(struct mnt_idmap *idmap, struct user_namespace *fs_userns, vfsgid_t vfsgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff8153b7b0)
Location: fs/mnt_idmapping.c:163
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
  - fs/inode.c:inode_init_owner
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/posix_acl.c:vfs_set_acl
  - fs/quota/dquot.c:dquot_transfer
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff8153b7b0-ffffffff8153b7fb: from_vfsgid (STB_GLOBAL)
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
