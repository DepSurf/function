# Function: <code>vfsgid_in_group_p</code>

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
In fs/namei.c (ffffffff8148b7a8)
Location: include/linux/mnt_idmapping.h:126
Inline: True
```
```
In fs/inode.c (ffffffff814a283e)
Location: include/linux/mnt_idmapping.h:126
Inline: True
Inline callers:
  - fs/inode.c:mode_strip_sgid
```
```
In fs/attr.c (ffffffff814a59c5)
Location: include/linux/mnt_idmapping.h:126
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
```
```
In fs/posix_acl.c (ffffffff81515e49)
Location: include/linux/mnt_idmapping.h:126
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/fat/file.c (ffffffff816005bf)
Location: include/linux/mnt_idmapping.h:126
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In fs/fuse/acl.c (ffffffff8162e8fa)
Location: include/linux/mnt_idmapping.h:126
Inline: True
Inline callers:
  - fs/fuse/acl.c:fuse_set_acl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfsgid_in_group_p(vfsgid_t vfsgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff81506b50)
Location: fs/mnt_idmapping.c:219
Inline: False
Direct callers:
  - fs/inode.c:mode_strip_sgid
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/fat/file.c:fat_setattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff81506b50-ffffffff81506b66: vfsgid_in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfsgid_in_group_p(vfsgid_t vfsgid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/mnt_idmapping.c (ffffffff8153b810)
Location: fs/mnt_idmapping.c:189
Inline: False
Direct callers:
  - fs/inode.c:mode_strip_sgid
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/fat/file.c:fat_setattr
  - fs/fuse/acl.c:fuse_set_acl
```
**Symbols:**

```
ffffffff8153b810-ffffffff8153b826: vfsgid_in_group_p (STB_GLOBAL)
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
