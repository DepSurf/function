# Function: <code>selinux_superblock</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813aa623)
Location: security/selinux/include/objsec.h:184
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_alloc_security
  - security/selinux/hooks.c:superblock_has_perm
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/selinux/ss/services.c (ffffffff813bc526)
Location: security/selinux/include/objsec.h:184
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cfae5)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_alloc_security
  - security/selinux/hooks.c:superblock_has_perm
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/selinux/ss/services.c (ffffffff813e2696)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
```
</details>
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
In security/selinux/hooks.c (ffffffff814da198)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_alloc_security
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/selinux/ss/services.c (ffffffff814f0665)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
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
In security/selinux/hooks.c (ffffffff81533098)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_alloc_security
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/selinux/ss/services.c (ffffffff8154abfc)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c85ae)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_alloc_security
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/selinux/ss/services.c (ffffffff815e391c)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816756de)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_alloc_security
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/selinux/ss/services.c (ffffffff81692bbc)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
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
In security/selinux/hooks.c (ffffffff816add3e)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_fs_context_submount
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_alloc_security
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/selinux/ss/services.c (ffffffff816cb113)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
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
In security/selinux/hooks.c (ffffffff816eadce)
Location: security/selinux/include/objsec.h:193
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_fs_context_submount
  - security/selinux/hooks.c:selinux_umount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_sb_statfs
  - security/selinux/hooks.c:selinux_sb_kern_mount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_alloc_security
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:selinux_quotactl
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_determine_inode_label
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/selinux/hooks.c:sb_finish_set_opts
```
```
In security/selinux/ss/services.c (ffffffff81707d53)
Location: security/selinux/include/objsec.h:193
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_fs_use
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
