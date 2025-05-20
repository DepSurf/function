# Function: <code>vfsuid_eq_kuid</code>

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
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool vfsuid_eq_kuid(vfsuid_t vfsuid, kuid_t kuid);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148f9f7)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/namei.c:do_open
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
```
```
In fs/inode.c (ffffffff814a2501)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
```
```
In fs/attr.c (ffffffff814a578f)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/remap_range.c (ffffffff814d0d92)
Location: include/linux/mnt_idmapping.h:79
Inline: True
```
```
In fs/posix_acl.c (ffffffff815170c2)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff815194fb)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/fat/file.c (ffffffff816004de)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fa000)
Location: include/linux/mnt_idmapping.h:79
Inline: False
```
**Symbols:**

```
ffffffff816fa000-ffffffff816fa015: vfsuid_eq_kuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool vfsuid_eq_kuid(vfsuid_t vfsuid, kuid_t kuid);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c21a9)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/namei.c:do_open
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
```
```
In fs/inode.c (ffffffff814d707a)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
```
```
In fs/attr.c (ffffffff814da8dd)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/remap_range.c (ffffffff815078c0)
Location: include/linux/mnt_idmapping.h:79
Inline: True
```
```
In fs/locks.c (ffffffff81543e50)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
```
```
In fs/posix_acl.c (ffffffff8154e94d)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff81550da8)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/fat/file.c (ffffffff8163844b)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In security/integrity/ima/ima_policy.c (ffffffff81734130)
Location: include/linux/mnt_idmapping.h:79
Inline: False
```
**Symbols:**

```
ffffffff81734130-ffffffff81734145: vfsuid_eq_kuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool vfsuid_eq_kuid(vfsuid_t vfsuid, kuid_t kuid);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f4669)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/namei.c:do_open
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
```
```
In fs/inode.c (ffffffff815093fa)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
```
```
In fs/attr.c (ffffffff8150ce7d)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/remap_range.c (ffffffff8153bfe8)
Location: include/linux/mnt_idmapping.h:79
Inline: True
```
```
In fs/locks.c (ffffffff8157932f)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
```
```
In fs/posix_acl.c (ffffffff8158479d)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff81586c39)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/fat/file.c (ffffffff8167193b)
Location: include/linux/mnt_idmapping.h:79
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In security/integrity/ima/ima_policy.c (ffffffff81774c20)
Location: include/linux/mnt_idmapping.h:79
Inline: False
```
**Symbols:**

```
ffffffff81774c20-ffffffff81774c35: vfsuid_eq_kuid (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
