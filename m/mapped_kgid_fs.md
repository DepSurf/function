# Function: <code>mapped_kgid_fs</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810da7cd)
Location: include/linux/mnt_idmapping.h:107
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff813f807d)
Location: include/linux/mnt_idmapping.h:107
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff813f9e04)
Location: include/linux/mnt_idmapping.h:107
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff8140318d)
Location: include/linux/mnt_idmapping.h:107
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff814169fb)
Location: include/linux/mnt_idmapping.h:107
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff81419bc6)
Location: include/linux/mnt_idmapping.h:107
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (ffffffff81427da4)
Location: include/linux/mnt_idmapping.h:107
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
```
In fs/posix_acl.c (ffffffff81482eb4)
Location: include/linux/mnt_idmapping.h:107
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/fat/file.c (ffffffff8155e392)
Location: include/linux/mnt_idmapping.h:107
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In fs/fuse/acl.c (0)
Location: include/linux/mnt_idmapping.h:107
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81642e5c)
Location: include/linux/mnt_idmapping.h:107
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_rules
```
</details>
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
