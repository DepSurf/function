# Function: <code>mapped_kuid_fs</code>

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
In kernel/capability.c (ffffffff810da772)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/stat.c (ffffffff813f8041)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - fs/stat.c:generic_fillattr
```
```
In fs/exec.c (ffffffff813f9dbc)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/namei.c (ffffffff8140313e)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
```
```
In fs/inode.c (ffffffff81416eeb)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff81419b29)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
```
```
In fs/xattr.c (ffffffff81427d53)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
```
In fs/remap_range.c (ffffffff81441a90)
Location: include/linux/mnt_idmapping.h:70
Inline: True
```
```
In fs/posix_acl.c (ffffffff81482e9a)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
```
```
In fs/coredump.c (ffffffff81485cd6)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/fat/file.c (ffffffff8155e319)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - fs/fat/file.c:fat_setattr
```
```
In security/commoncap.c (ffffffff815b6bf5)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/apparmor/domain.c (ffffffff81617451)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81624b33)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff816287c6)
Location: include/linux/mnt_idmapping.h:70
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_policy.c (ffffffff81642dfc)
Location: include/linux/mnt_idmapping.h:70
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
