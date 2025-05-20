# Function: <code>from_vfsuid</code>

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
In fs/open.c (ffffffff81475afe)
Location: include/linux/mnt_idmapping.h:258
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/namei.c (ffffffff8148c07c)
Location: include/linux/mnt_idmapping.h:258
Inline: True
```
```
In fs/inode.c (ffffffff814a1e74)
Location: include/linux/mnt_idmapping.h:258
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
```
```
In fs/attr.c (ffffffff814a5d87)
Location: include/linux/mnt_idmapping.h:258
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
```
```
In fs/posix_acl.c (ffffffff81515b2c)
Location: include/linux/mnt_idmapping.h:258
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_set_acl
```
```
In fs/quota/dquot.c (ffffffff81528066)
Location: include/linux/mnt_idmapping.h:258
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/ialloc.c (ffffffff8156ff40)
Location: include/linux/mnt_idmapping.h:258
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81585650)
Location: include/linux/mnt_idmapping.h:258
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/fat/file.c (ffffffff81600320)
Location: include/linux/mnt_idmapping.h:258
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In security/commoncap.c (ffffffff81661c04)
Location: include/linux/mnt_idmapping.h:258
Inline: True
Inline callers:
  - security/commoncap.c:cap_convert_nscap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
kuid_t from_vfsuid(struct mnt_idmap *idmap, struct user_namespace *fs_userns, vfsuid_t vfsuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff815069e0)
Location: fs/mnt_idmapping.c:164
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
  - fs/attr.c:setattr_copy
  - fs/posix_acl.c:vfs_set_acl
  - fs/quota/dquot.c:dquot_transfer
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff815069e0-ffffffff81506a41: from_vfsuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
kuid_t from_vfsuid(struct mnt_idmap *idmap, struct user_namespace *fs_userns, vfsuid_t vfsuid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff8153b750)
Location: fs/mnt_idmapping.c:136
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
  - fs/attr.c:setattr_copy
  - fs/posix_acl.c:vfs_set_acl
  - fs/quota/dquot.c:dquot_transfer
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
  - security/commoncap.c:cap_convert_nscap
```
**Symbols:**

```
ffffffff8153b750-ffffffff8153b797: from_vfsuid (STB_GLOBAL)
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
