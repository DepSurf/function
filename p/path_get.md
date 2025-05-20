# Function: <code>path_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81216450)
Location: fs/namei.c:475
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:trailing_symlink
  - fs/namei.c:trailing_symlink
  - fs/namei.c:follow_dotdot
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/fs_struct.c:set_fs_root
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/fd.c:proc_fd_link
  - fs/dcookies.c:get_dcookie
  - ipc/shm.c:do_shmat
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff81216450-ffffffff8121647a: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123d230)
Location: fs/namei.c:485
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:get_dcookie
  - ipc/shm.c:do_shmat
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff8123d230-ffffffff8123d25a: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8124ffd0)
Location: fs/namei.c:485
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:mntns_install
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/dcookies.c:get_dcookie
  - ipc/shm.c:do_shmat
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff8124ffd0-ffffffff8124fffa: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125bf10)
Location: fs/namei.c:485
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - ipc/shm.c:do_shmat
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff8125bf10-ffffffff8125bf3a: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127e2d0)
Location: fs/namei.c:485
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - ipc/shm.c:do_shmat
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff8127e2d0-ffffffff8127e2fa: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a5130)
Location: fs/namei.c:469
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/pipe.c:create_pipe_files
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - ipc/shm.c:do_shmat
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff812a5130-ffffffff812a515a: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ba2a0)
Location: fs/namei.c:469
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/path.c:aa_path_name
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff812ba2a0-ffffffff812ba2ca: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d6e90)
Location: fs/namei.c:467
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff812d6e90-ffffffff812d6eba: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e8a00)
Location: fs/namei.c:467
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff812e8a00-ffffffff812e8a2a: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81322d06)
Location: fs/namei.c:481
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/exec.c:kernel_read_file_from_path_initns
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_open_file
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff81320bb0-ffffffff81320bdd: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132e2ad)
Location: fs/namei.c:481
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
Direct callers:
  - kernel/auditsc.c:audit_alloc_name
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_open_file
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff8132c140-ffffffff8132c16d: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334866)
Location: fs/namei.c:531
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
Direct callers:
  - kernel/auditsc.c:audit_alloc_name
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/landlock/syscalls.c:get_path_from_fd
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff81332180-ffffffff813321ad: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813821b1)
Location: fs/namei.c:542
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
Direct callers:
  - kernel/auditsc.c:audit_alloc_name
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/landlock/syscalls.c:get_path_from_fd
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff8137f910-ffffffff8137f93d: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81403e71)
Location: fs/namei.c:543
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
Direct callers:
  - kernel/auditsc.c:audit_alloc_name
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/fs.c:check_access_path_dual
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff813ffab0-ffffffff813ffae5: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148e2dd)
Location: fs/namei.c:543
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
Direct callers:
  - kernel/auditsc.c:audit_alloc_name
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/fs.c:is_access_to_paths_allowed
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff81489a80-ffffffff81489ab5: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c3a29)
Location: fs/namei.c:546
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
Direct callers:
  - kernel/auditsc.c:audit_alloc_name
  - fs/open.c:backing_file_open
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/landlock/syscalls.c:get_path_from_fd
  - security/landlock/fs.c:is_access_to_paths_allowed
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff814bea70-ffffffff814beaa5: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f5ef9)
Location: fs/namei.c:547
Inline: True
Inline callers:
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
Direct callers:
  - kernel/auditsc.c:audit_alloc_name
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:__do_sys_statmount
  - fs/namespace.c:__do_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/backing-file.c:backing_file_open
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/landlock/syscalls.c:add_rule_path_beneath
  - security/landlock/fs.c:is_access_to_paths_allowed
  - drivers/block/loop.c:loop_get_status
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff814f0ef0-ffffffff814f0f25: path_get (STB_GLOBAL)
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
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010391da0)
Location: fs/namei.c:467
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffff800010391da0-ffff800010391ddc: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057849c)
Location: fs/namei.c:467
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
c057849c-c05784d4: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000489d70)
Location: fs/namei.c:467
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
c000000000489d70-c000000000489dcc: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000260fa4)
Location: fs/namei.c:467
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffe000260fa4-ffffffe000260fde: path_get (STB_GLOBAL)
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
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e0fe0)
Location: fs/namei.c:467
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff812e0fe0-ffffffff812e100a: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d1c20)
Location: fs/namei.c:467
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff812d1c20-ffffffff812d1c4a: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dedf0)
Location: fs/namei.c:467
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff812dedf0-ffffffff812dee1a: path_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void path_get(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812efd60)
Location: fs/namei.c:467
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_getname
  - fs/open.c:do_dentry_open
  - fs/file_table.c:alloc_file_clone
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:path_init
  - fs/namei.c:nd_jump_root
  - fs/namei.c:set_root
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:copy_fs_struct
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:chroot_fs_refs
  - fs/fs_struct.c:set_fs_pwd
  - fs/fs_struct.c:set_fs_root
  - fs/proc_namespace.c:mounts_open_common
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
  - fs/proc/fd.c:proc_fd_link
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/dcookies.c:get_dcookie
  - security/keys/big_key.c:big_key_preparse
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - net/unix/af_unix.c:unix_ioctl
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff812efd60-ffffffff812efd8a: path_get (STB_GLOBAL)
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
