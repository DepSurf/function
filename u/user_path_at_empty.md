# Function: <code>user_path_at_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121c400)
Location: fs/namei.c:2329
Inline: False
Direct callers:
  - fs/open.c:do_sys_truncate
  - fs/open.c:SyS_access
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_lchown
  - fs/stat.c:vfs_fstatat
  - fs/stat.c:SyS_readlink
  - fs/namei.c:SyS_link
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff8121c400-ffffffff8121c43d: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81243880)
Location: fs/namei.c:2553
Inline: False
Direct callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:do_sys_truncate
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_fstatat
  - fs/namei.c:SyS_link
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff81243880-ffffffff812438bd: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81256800)
Location: fs/namei.c:2542
Inline: False
Direct callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:do_sys_truncate
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_fstatat
  - fs/namei.c:SyS_link
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff81256800-ffffffff8125683d: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812629a0)
Location: fs/namei.c:2587
Inline: False
Direct callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_statx
  - fs/namei.c:SyS_link
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812629a0-ffffffff812629dd: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812851f0)
Location: fs/namei.c:2585
Inline: False
Direct callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/stat.c:SyS_readlink
  - fs/stat.c:vfs_statx
  - fs/namei.c:SyS_link
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812851f0-ffffffff8128522d: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ac320)
Location: fs/namei.c:2581
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812ac320-ffffffff812ac365: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c1420)
Location: fs/namei.c:2605
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812c1420-ffffffff812c1465: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812de680)
Location: fs/namei.c:2603
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812de680-ffffffff812de6c2: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f0190)
Location: fs/namei.c:2596
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812f0190-ffffffff812f01d2: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81329527)
Location: fs/namei.c:2643
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_do_get
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__do_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff813284f0-ffffffff81328574: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813337a7)
Location: fs/namei.c:2641
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_do_get
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__x64_sys_umount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__do_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff813336b0-ffffffff81333734: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81339868)
Location: fs/namei.c:2731
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__x64_sys_umount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__do_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl_path
  - fs/quota/quota.c:__x64_sys_quotactl_path
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff81339770-ffffffff813397f4: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81386e10)
Location: fs/namei.c:2797
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__x64_sys_umount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__do_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff81386e10-ffffffff81386e67: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81407b70)
Location: fs/namei.c:2893
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
  - fs/stat.c:do_readlinkat
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff81407b70-ffffffff81407bd4: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81492010)
Location: fs/namei.c:2872
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
  - fs/stat.c:do_readlinkat
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff81492010-ffffffff81492074: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c7050)
Location: fs/namei.c:2903
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
  - fs/stat.c:do_readlinkat
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff814c7050-ffffffff814c70b4: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f99a0)
Location: fs/namei.c:2920
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - fs/open.c:do_fchownat
  - fs/open.c:__ia32_sys_chmod
  - fs/open.c:__x64_sys_chmod
  - fs/open.c:__ia32_sys_fchmodat
  - fs/open.c:__x64_sys_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:__x64_sys_truncate
  - fs/stat.c:do_readlinkat
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff814f99a0-ffffffff814f9a04: user_path_at_empty (STB_GLOBAL)
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
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103998a0)
Location: fs/namei.c:2596
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namei.c:do_linkat
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_move_mount
  - fs/namespace.c:__arm64_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__arm64_sys_fspick
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffff8000103998a0-ffff80001039990c: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057fe40)
Location: fs/namei.c:2596
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__se_sys_fspick
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/fhandle.c:__se_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
c057fe40-c057fe98: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000494250)
Location: fs/namei.c:2596
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__se_sys_fspick
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/fhandle.c:__se_sys_name_to_handle_at
  - fs/fhandle.c:__se_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
c000000000494250-c0000000004942bc: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002671a8)
Location: fs/namei.c:2596
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__se_sys_fspick
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/fhandle.c:__se_sys_name_to_handle_at
  - fs/fhandle.c:__se_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffe0002671a8-ffffffe000267200: user_path_at_empty (STB_GLOBAL)
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
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e8770)
Location: fs/namei.c:2596
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812e8770-ffffffff812e87b2: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d93b0)
Location: fs/namei.c:2596
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812d93b0-ffffffff812d93f2: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e6580)
Location: fs/namei.c:2596
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812e6580-ffffffff812e65c2: user_path_at_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int user_path_at_empty(int dfd, const char *name, unsigned int flags, struct path *path, int *empty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f7500)
Location: fs/namei.c:2596
Inline: False
Direct callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
  - fs/stat.c:do_readlinkat
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
  - fs/utimes.c:do_utimes
  - fs/statfs.c:user_statfs
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812f7500-ffffffff812f7542: user_path_at_empty (STB_GLOBAL)
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
