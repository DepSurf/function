# Function: <code>in_group_p</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810a4190)
Location: kernel/groups.c:255
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_filter_rules
  - kernel/auditsc.c:audit_filter_rules
  - fs/attr.c:setattr_copy
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810a4190-ffffffff810a4202: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810a78d0)
Location: kernel/groups.c:255
Inline: False
Direct callers:
  - fs/attr.c:setattr_copy
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810a78d0-ffffffff810a7942: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810ada70)
Location: kernel/groups.c:230
Inline: False
Direct callers:
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810ada70-ffffffff810adace: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810aa630)
Location: kernel/groups.c:217
Inline: False
Direct callers:
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810aa630-ffffffff810aa695: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b12f0)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810b12f0-ffffffff810b1355: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b80f0)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810b80f0-ffffffff810b8153: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c11d0)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810c11d0-ffffffff810c1233: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c72c0)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810c72c0-ffffffff810c732c: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d0390)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810d0390-ffffffff810d03fc: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810da560)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810da560-ffffffff810da5d1: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d5cc0)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810d5cc0-ffffffff810d5d31: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d7980)
Location: kernel/groups.c:214
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - fs/fuse/acl.c:fuse_set_acl
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810d7980-ffffffff810d79f1: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810eb230)
Location: kernel/groups.c:214
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - fs/fuse/acl.c:fuse_set_acl
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810eb230-ffffffff810eb2a1: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81106110)
Location: kernel/groups.c:214
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - fs/fuse/acl.c:fuse_set_acl
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff81106110-ffffffff811061ac: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff8112bd40)
Location: kernel/groups.c:227
Inline: False
Direct callers:
  - fs/inode.c:mode_strip_sgid
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - fs/fuse/acl.c:fuse_set_acl
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff8112bd40-ffffffff8112bddc: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff81138ba0)
Location: kernel/groups.c:227
Inline: False
Direct callers:
  - fs/mnt_idmapping.c:vfsgid_in_group_p
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff81138ba0-ffffffff81138c3c: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff811438e0)
Location: kernel/groups.c:227
Inline: False
Direct callers:
  - fs/mnt_idmapping.c:vfsgid_in_group_p
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - io_uring/io_uring.c:__ia32_sys_io_uring_setup
  - io_uring/io_uring.c:__x64_sys_io_uring_setup
```
**Symbols:**

```
ffffffff811438e0-ffffffff8114397c: in_group_p (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffff800010130a20)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffff800010130a20-ffff800010130ab4: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c0380280)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
c0380280-c038030c: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (c00000000017a120)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
c00000000017a120-c00000000017a1b8: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffe0000e3dd2)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffe0000e3dd2-ffffffe0000e3e4e: in_group_p (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810ca710)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810ca710-ffffffff810ca77c: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810b8f20)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810b8f20-ffffffff810b8f8c: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810c9c40)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810c9c40-ffffffff810c9cac: in_group_p (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int in_group_p(kgid_t grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/groups.c (ffffffff810d2190)
Location: kernel/groups.c:219
Inline: False
Direct callers:
  - fs/inode.c:inode_init_owner
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_permission
  - fs/configfs/inode.c:configfs_setattr
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/file.c:fat_setattr
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcperms
  - security/keys/keyctl.c:keyctl_chown_key
```
**Symbols:**

```
ffffffff810d2190-ffffffff810d21fc: in_group_p (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
