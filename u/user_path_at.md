# Function: <code>user_path_at</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81209a41)
Location: include/linux/namei.h:49
Inline: True
Inline callers:
  - fs/open.c:do_sys_truncate
  - fs/open.c:SyS_access
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_lchown
```
```
In fs/stat.c (ffffffff812115d1)
Location: include/linux/namei.h:49
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstatat
```
```
In fs/namei.c (ffffffff8121d964)
Location: include/linux/namei.h:49
Inline: True
Inline callers:
  - fs/namei.c:SyS_link
```
```
In fs/xattr.c (ffffffff812322ac)
Location: include/linux/namei.h:49
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81240f10)
Location: include/linux/namei.h:49
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81241b2f)
Location: include/linux/namei.h:49
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8125246d)
Location: include/linux/namei.h:49
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81253715)
Location: include/linux/namei.h:49
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff8127008e)
Location: include/linux/namei.h:49
Inline: True
Inline callers:
  - fs/fhandle.c:SyS_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff8127604f)
Location: include/linux/namei.h:49
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81230f4e)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:do_sys_truncate
```
```
In fs/stat.c (ffffffff81238081)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstatat
```
```
In fs/namei.c (ffffffff812451d6)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/namei.c:SyS_link
```
```
In fs/xattr.c (ffffffff8125afab)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81269241)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81269e7f)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8127ac2d)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127bd11)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff8129b8ae)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/fhandle.c:SyS_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff812a2830)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812434fe)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
  - fs/open.c:do_sys_truncate
```
```
In fs/stat.c (ffffffff8124ad41)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/stat.c:vfs_fstatat
```
```
In fs/namei.c (ffffffff81258146)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/namei.c:SyS_link
```
```
In fs/xattr.c (ffffffff8126e54b)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff8127c1f1)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8127ce2f)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8128e7dd)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8128f8c1)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff812b046e)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/fhandle.c:SyS_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff812b81f0)
Location: include/linux/namei.h:52
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124ec51)
Location: include/linux/namei.h:53
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
```
```
In fs/stat.c (ffffffff81256842)
Location: include/linux/namei.h:53
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812642d6)
Location: include/linux/namei.h:53
Inline: True
Inline callers:
  - fs/namei.c:SyS_link
```
```
In fs/xattr.c (ffffffff8127bd4b)
Location: include/linux/namei.h:53
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81289510)
Location: include/linux/namei.h:53
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8128a714)
Location: include/linux/namei.h:53
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8129b65d)
Location: include/linux/namei.h:53
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129c89f)
Location: include/linux/namei.h:53
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff812bd8fe)
Location: include/linux/namei.h:53
Inline: True
Inline callers:
  - fs/fhandle.c:SyS_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff812c5423)
Location: include/linux/namei.h:53
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
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
In fs/open.c (ffffffff81270bd1)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_chmod
  - fs/open.c:SyS_chroot
  - fs/open.c:SyS_chdir
  - fs/open.c:SyS_access
```
```
In fs/stat.c (ffffffff81278a92)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff81286b66)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/namei.c:SyS_link
```
```
In fs/xattr.c (ffffffff8129e7eb)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff812ac030)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff812ad434)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812bea6d)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812bfd0f)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff812e14be)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fhandle.c:SyS_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff812e92c3)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/quota/quota.c:SyS_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81296739)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff8129f3e2)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812adec5)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/xattr.c (ffffffff812c52b4)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff812d2cdf)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff812d5074)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e6f85)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e891f)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff8130d90e)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff81315f5c)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ab529)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812b43c2)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812c2fd5)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/xattr.c (ffffffff812da4b4)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff812e80bf)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff812ea444)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fbb75)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fdd10)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff81322e6e)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff8132ceeb)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c7d29)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812d1138)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812df717)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (ffffffff812f4028)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
```
In fs/xattr.c (ffffffff812f8a8b)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff813069c3)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81308ea4)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff8130bede)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131c4d5)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e8fe)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff8134a88e)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff81354fa4)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d9739)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812e2cc8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812f1227)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (ffffffff81306f98)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff8130a6bb)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81319a23)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8131bf14)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff8131eeee)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132f2a5)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8133170d)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff81362b3e)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff8136d2e8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81213c1a)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_do_get
```
```
In fs/open.c (ffffffff8130f4f9)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff8131a7ec)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff81329527)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (ffffffff81340771)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff813436bb)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff813539c9)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81355c14)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff81358d65)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81369425)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136af77)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff813a8cfe)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff813b50dc)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812154ba)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_do_get
```
```
In fs/open.c (ffffffff8131b729)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff81325e75)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff813337a7)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (ffffffff8134c801)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff8134f84b)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff813602c9)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81362554)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff813656e5)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81376705)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81378807)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff813ba05e)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff813c6a2f)
Location: include/linux/namei.h:56
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81218d42)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff81321879)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff8132bf85)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff81339868)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (ffffffff8134f498)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff8135636b)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81366d69)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81368ff4)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff8136c125)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137cff5)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137f7b7)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff813c11bd)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff813cd7ad)
Location: include/linux/namei.h:57
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl_path
  - fs/quota/quota.c:__x64_sys_quotactl_path
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
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
In kernel/bpf/inode.c (ffffffff8124f452)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff8136ed59)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff813796f5)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namespace.c (ffffffff8139d778)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff813a489b)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff813b58b9)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff813b7cf4)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff813badf5)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813c9ea5)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cc774)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff81410c2d)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff8141e9a6)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
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
In kernel/bpf/inode.c (ffffffff812965b5)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff813ed639)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
```
```
In fs/namespace.c (ffffffff81420734)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff814288ec)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff8143ac24)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff8143d4c4)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff81440bd0)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451f45)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81454f47)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff814865cd)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff81496715)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
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
In kernel/bpf/inode.c (ffffffff812f14c5)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff81475cd9)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
```
```
In fs/namespace.c (ffffffff814acccf)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff814b5efc)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff814c90e4)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff814cbd04)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff814cfad0)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0cd5)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e3e97)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff81519f0d)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff8152a685)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
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
In kernel/bpf/inode.c (ffffffff8131e0c6)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff814aa5f9)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_truncate
```
```
In fs/namespace.c (ffffffff814e19d1)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff814ea72c)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff814ff327)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81501f44)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff81505d90)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81517585)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a887)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff8155184a)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff81562a65)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
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
In kernel/bpf/inode.c (ffffffff813404e6)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff814dba99)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
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
```
```
In fs/namespace.c (ffffffff81515aa1)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff8151e5cc)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81533f30)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81536b94)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff8153ab90)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b965)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154ee87)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/fhandle.c (ffffffff8158778a)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff81599155)
Location: include/linux/namei.h:54
Inline: True
Inline callers:
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037eab8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffff80001038a6c8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffff80001039a97c)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (ffff8000103ba758)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_move_mount
  - fs/namespace.c:__arm64_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__arm64_sys_open_tree
```
```
In fs/xattr.c (ffff8000103be128)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffff8000103d0a08)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffff8000103d38b4)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffff8000103d6ff4)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fsopen.c:__arm64_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ecdf8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103eeab8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffff8000104297f4)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffff800010437220)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (c0569420)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (c0572870)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (c0580e08)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (c0598528)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
```
```
In fs/xattr.c (c059b960)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (c05abd48)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (c05ade20)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (c05b09d8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (c05c3790)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (c05c5b24)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/fhandle.c (c05f20a4)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_name_to_handle_at
```
```
In fs/quota/quota.c (c05feea8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474744)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (c000000000481970)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (c0000000004957b0)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (c0000000004b7f90)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
```
```
In fs/xattr.c (c0000000004bcc30)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (c0000000004d3374)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (c0000000004d62b8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (c0000000004db63c)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f3db4)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f73b8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (c000000000539648)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_name_to_handle_at
```
```
In fs/quota/quota.c (c0000000005495e0)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe00025471c)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffe00025c5ce)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffe00026800e)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (ffffffe00027cc34)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
```
```
In fs/xattr.c (ffffffe00027f514)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffe00028cbb8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffe00028e296)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffe000290916)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fsopen.c:__se_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a09b8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a29da)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/fhandle.c (ffffffe0002c72bc)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffe0002d1518)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d1d19)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812db2a8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812e9807)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (ffffffff812ff578)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff81302c9b)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81312003)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff813144f4)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff813174ce)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81327885)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81329ced)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff8135b11e)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff813658c8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c2999)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812cbf28)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812da447)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (ffffffff812f0198)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff812f38bb)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81302c13)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81305104)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff813080be)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81318425)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a88d)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff8134bdbe)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff81356568)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cfb29)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812d90b8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812e7617)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (ffffffff812fd368)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff81300a8b)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff8130fdf3)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff813122e4)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff81314f9e)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81325355)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813277bd)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff81358bee)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff81363398)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e0939)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/open.c:do_fchownat
  - fs/open.c:do_fchmodat
  - fs/open.c:ksys_chroot
  - fs/open.c:ksys_chdir
  - fs/open.c:do_faccessat
```
```
In fs/stat.c (ffffffff812e9fc8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/stat.c:vfs_statx
```
```
In fs/namei.c (ffffffff812f8597)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
```
```
In fs/namespace.c (ffffffff8130e6c8)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
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
```
```
In fs/xattr.c (ffffffff81311dcb)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:path_listxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff813215f3)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/utimes.c:do_utimes
```
```
In fs/statfs.c (ffffffff81323b24)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/statfs.c:user_statfs
```
```
In fs/fsopen.c (ffffffff81326b0e)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813376f5)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81339bdd)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/fhandle.c (ffffffff8136c2ee)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/fhandle.c:__ia32_sys_name_to_handle_at
  - fs/fhandle.c:__x64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffffffff81376a48)
Location: include/linux/namei.h:46
Inline: True
Inline callers:
  - fs/quota/quota.c:kernel_quotactl
```
</details>
</li>
</ul>

## Differences
