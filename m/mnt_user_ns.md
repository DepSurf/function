# Function: <code>mnt_user_ns</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810be5b7)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/bpf/inode.c (ffffffff81218db0)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In mm/mincore.c (ffffffff812a6816)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/madvise.c (ffffffff812c7c90)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
```
```
In mm/memcontrol.c (ffffffff8130b014)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8132168a)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/stat.c (ffffffff8132b628)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/stat.c:vfs_getattr_nosec
```
```
In fs/exec.c (ffffffff8132cf4d)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/exec.c:would_dump
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff8133ab32)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
```
```
In fs/fcntl.c (ffffffff8133b5a5)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (ffffffff8133d913)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/inode.c (ffffffff8134744f)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
  - fs/inode.c:atime_needs_update
```
```
In fs/namespace.c (ffffffff8134cfa1)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:free_vfsmnt
```
```
In fs/xattr.c (ffffffff81356aa5)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff81366bd4)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/init.c (ffffffff831f88cc)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - fs/init.c:path_permission
```
```
In fs/remap_range.c (ffffffff8136cace)
Location: include/linux/mount.h:78
Inline: True
```
```
In fs/proc_namespace.c (ffffffff8137908a)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mnt_opts
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d039)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137f7d2)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/verity/enable.c (ffffffff813af3ee)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/coredump.c (ffffffff813c047b)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ioctl.c (ffffffff8141a7c5)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fat/file.c (ffffffff8147a40b)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/main.c (ffffffff8148327b)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In security/commoncap.c (ffffffff814ca551)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/apparmor/domain.c (ffffffff8151b2c9)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81526cea)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff81529d42)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_main.c (ffffffff8153bde8)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In net/unix/af_unix.c (ffffffff81b22653)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
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
In kernel/sys.c (ffffffff810d0323)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/bpf/inode.c (ffffffff8124f4c0)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In mm/mincore.c (ffffffff812e7cec)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/madvise.c (ffffffff8130ca50)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
```
```
In mm/memcontrol.c (ffffffff81355894)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff8136eb6a)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/stat.c (ffffffff81378d98)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/stat.c:vfs_getattr_nosec
```
```
In fs/exec.c (ffffffff8137a64d)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/exec.c:would_dump
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff813888ca)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
```
```
In fs/fcntl.c (ffffffff8138920b)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (ffffffff8138b293)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/inode.c (ffffffff81394eaf)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
  - fs/inode.c:atime_needs_update
```
```
In fs/namespace.c (ffffffff8139af32)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:free_vfsmnt
```
```
In fs/xattr.c (ffffffff813a5485)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff813b5724)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/init.c (ffffffff832df844)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - fs/init.c:path_permission
```
```
In fs/remap_range.c (ffffffff813bb78e)
Location: include/linux/mount.h:78
Inline: True
```
```
In fs/proc_namespace.c (ffffffff813c5bea)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/proc_namespace.c:show_mnt_opts
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813c9ee9)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cc78f)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/verity/enable.c (ffffffff813fef9e)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/coredump.c (ffffffff814102a3)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ioctl.c (ffffffff8146d9a5)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fat/file.c (ffffffff814d1a6b)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/main.c (ffffffff814da9fb)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In security/commoncap.c (ffffffff81522ffd)
Location: include/linux/mount.h:78
Inline: True
```
```
In security/apparmor/domain.c (ffffffff81579349)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81584f7a)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff815880e2)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_main.c (ffffffff8159aa48)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In net/unix/af_unix.c (ffffffff81be6d52)
Location: include/linux/mount.h:78
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_find_other
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
In kernel/sys.c (ffffffff810e9265)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/bpf/inode.c (ffffffff8129661c)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In mm/mincore.c (ffffffff81348f5e)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/madvise.c (ffffffff81375679)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
```
```
In mm/memcontrol.c (ffffffff813ce251)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff813ebf6d)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/open.c:dentry_create
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
```
```
In fs/stat.c (ffffffff813f81d4)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/stat.c:vfs_getattr_nosec
```
```
In fs/exec.c (ffffffff813f9d91)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:would_dump
```
```
In fs/namei.c (ffffffff814098c3)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
```
```
In fs/fcntl.c (ffffffff8140a872)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffffffff8140c582)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/inode.c (ffffffff8141726e)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
  - fs/inode.c:atime_needs_update
```
```
In fs/namespace.c (ffffffff8141de57)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:free_vfsmnt
```
```
In fs/xattr.c (ffffffff81428ae3)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
```
In fs/utimes.c (ffffffff8143aa08)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/init.c (ffffffff8349552b)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - fs/init.c:path_permission
```
```
In fs/remap_range.c (ffffffff81441996)
Location: include/linux/mount.h:76
Inline: True
```
```
In fs/proc_namespace.c (ffffffff8144cada)
Location: include/linux/mount.h:76
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451f94)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81454f64)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/verity/enable.c (ffffffff81472b30)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/coredump.c (ffffffff81485cb3)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ioctl.c (ffffffff814ee256)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fat/file.c (ffffffff8155e6f1)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/main.c (ffffffff81568367)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff81571f13)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In security/commoncap.c (ffffffff815b6fed)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/apparmor/domain.c (ffffffff81617439)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff81624b1b)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff816287b4)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_main.c (ffffffff8163f800)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In io_uring/io_uring.c (ffffffff816d27ea)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_setxattr
  - io_uring/io_uring.c:io_fsetxattr
  - io_uring/io_uring.c:io_getxattr
  - io_uring/io_uring.c:io_fgetxattr
```
```
In net/unix/af_unix.c (ffffffff81d7dfdf)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_find_other
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct user_namespace *mnt_user_ns(const struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814a8ff0)
Location: fs/namespace.c:247
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm_exe_file
  - kernel/bpf/inode.c:bpf_obj_get_user
  - mm/mincore.c:do_mincore
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/memcontrol.c:memcg_write_event_control
  - fs/open.c:dentry_create
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_fchdir
  - fs/open.c:__x64_sys_fchdir
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
  - fs/open.c:do_faccessat
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/stat.c:vfs_getattr_nosec
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:would_dump
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:pick_link
  - fs/fcntl.c:setfl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/inode.c:__file_remove_privs
  - fs/inode.c:__file_remove_privs
  - fs/inode.c:atime_needs_update
  - fs/utimes.c:vfs_utimes
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/coredump.c:do_coredump
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/file.c:__file_path_perm
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff814a8ff0-ffffffff814a9036: mnt_user_ns (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
</ul>
