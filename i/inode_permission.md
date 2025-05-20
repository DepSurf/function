# Function: <code>inode_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81216f00)
Location: fs/namei.c:458
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:vfs_truncate
  - fs/open.c:SyS_access
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_chroot
  - fs/exec.c:setup_new_exec
  - fs/namei.c:may_linkat
  - fs/namei.c:may_open
  - fs/namei.c:lookup_one_len
  - fs/namei.c:may_delete
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_link
  - fs/namei.c:path_init
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/xattr.c:xattr_permission
  - fs/utimes.c:utimes_common
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81216f00-ffffffff81216f42: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123dda0)
Location: fs/namei.c:468
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:vfs_truncate
  - fs/exec.c:setup_new_exec
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_open
  - fs/namei.c:may_open
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:may_linkat
  - fs/xattr.c:xattr_permission
  - fs/utimes.c:utimes_common
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff8123dda0-ffffffff8123dde1: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81250b80)
Location: fs/namei.c:468
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_open
  - fs/namei.c:may_open
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:may_linkat
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81250b80-ffffffff81250bc1: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125cd00)
Location: fs/namei.c:468
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_open
  - fs/namei.c:may_open
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:may_linkat
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff8125cd00-ffffffff8125cd41: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127f110)
Location: fs/namei.c:468
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_fchdir
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_open
  - fs/namei.c:may_open
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:may_linkat
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff8127f110-ffffffff8127f151: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a7970)
Location: fs/namei.c:427
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812a7970-ffffffff812a7b0d: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bca10)
Location: fs/namei.c:427
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812bca10-ffffffff812bcbad: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9510)
Location: fs/namei.c:425
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/ext4/super.c:handle_mount_opt
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812d9510-ffffffff812d96b4: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812eb020)
Location: fs/namei.c:425
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812eb020-ffffffff812eb1c4: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81326886)
Location: fs/namei.c:439
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_len_common
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_do_get
  - mm/mincore.c:do_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_o_create
  - fs/namei.c:may_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_len_common
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81323680-ffffffff81323794: inode_permission.part.0 (STB_LOCAL)
ffffffff813237a0-ffffffff813237e1: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81331cfb)
Location: fs/namei.c:439
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_len_common
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_do_get
  - mm/mincore.c:do_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_o_create
  - fs/namei.c:may_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_len_common
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff8132ec20-ffffffff8132ed34: inode_permission.part.0 (STB_LOCAL)
ffffffff8132ed40-ffffffff8132ed81: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int inode_permission(struct user_namespace *mnt_userns, struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334980)
Location: fs/namei.c:488
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__do_sys_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_len_common
  - fs/namei.c:may_linkat
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/init.c:path_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81334980-ffffffff81334b07: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int inode_permission(struct user_namespace *mnt_userns, struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813822c0)
Location: fs/namei.c:499
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__do_sys_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_common
  - fs/namei.c:may_linkat
  - fs/xattr.c:xattr_permission
  - fs/init.c:path_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff813822c0-ffffffff81382447: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int inode_permission(struct user_namespace *mnt_userns, struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81401760)
Location: fs/namei.c:500
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__do_sys_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_common
  - fs/namei.c:may_linkat
  - fs/attr.c:may_setattr
  - fs/xattr.c:xattr_permission
  - fs/init.c:path_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81401760-ffffffff81401952: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int inode_permission(struct user_namespace *mnt_userns, struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148b860)
Location: fs/namei.c:500
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:do_mincore
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_common
  - fs/namei.c:may_linkat
  - fs/attr.c:may_setattr
  - fs/xattr.c:xattr_permission
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff8148b860-ffffffff8148ba52: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int inode_permission(struct mnt_idmap *idmap, struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814bf900)
Location: fs/namei.c:503
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:do_mincore
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_common
  - fs/namei.c:may_linkat
  - fs/attr.c:may_setattr
  - fs/xattr.c:xattr_permission
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff814bf900-ffffffff814bfaa7: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int inode_permission(struct mnt_idmap *idmap, struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f1df0)
Location: fs/namei.c:504
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/trace/bpf_trace.c:bpf_get_file_xattr
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:do_mincore
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:may_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_common
  - fs/namei.c:may_linkat
  - fs/attr.c:may_setattr
  - fs/xattr.c:xattr_permission
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff814f1df0-ffffffff814f1f97: inode_permission (STB_GLOBAL)
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
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010394700)
Location: fs/namei.c:425
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__do_sys_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__arm64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffff800010394700-ffff8000103948f0: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0579be4)
Location: fs/namei.c:425
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__se_sys_mincore
  - mm/madvise.c:__se_sys_madvise
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:may_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:__se_sys_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
c0579be4-c0579da4: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048b0b0)
Location: fs/namei.c:425
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__se_sys_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
c00000000048b0b0-c00000000048b33c: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002631fa)
Location: fs/namei.c:425
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__se_sys_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__se_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:lookup_one_len_common
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:__se_sys_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffe0002631fa-ffffffe00026338c: inode_permission (STB_GLOBAL)
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
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e3600)
Location: fs/namei.c:425
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812e3600-ffffffff812e37a4: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d4240)
Location: fs/namei.c:425
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812d4240-ffffffff812d43e4: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e1410)
Location: fs/namei.c:425
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812e1410-ffffffff812e15b4: inode_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inode_permission(struct inode *inode, int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f09f0)
Location: fs/namei.c:425
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/bpf/inode.c:bpf_prog_get_type_path
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/madvise.c:madvise_pageout
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:ksys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:vfs_truncate
  - fs/exec.c:would_dump
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/attr.c:notify_change
  - fs/xattr.c:xattr_permission
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/configfs/symlink.c:configfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_permission
  - ipc/mqueue.c:do_mq_open
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff812f09f0-ffffffff812f0b92: inode_permission (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, mask</code> ➡️ <code>mnt_userns, inode, mask</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
