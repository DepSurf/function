# Function: <code>mnt_idmap</code>

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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814aa1dd)
Location: include/linux/mount.h:79
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:free_vfsmnt
  - fs/namespace.c:mnt_user_ns
```
```
In fs/xattr.c (ffffffff814b6143)
Location: include/linux/mount.h:79
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
In fs/proc_namespace.c (ffffffff814db03a)
Location: include/linux/mount.h:79
Inline: True
```
```
In fs/ecryptfs/main.c (ffffffff8160bc71)
Location: include/linux/mount.h:79
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In io_uring/xattr.c (ffffffff81792fe3)
Location: include/linux/mount.h:79
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
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
In kernel/sys.c (ffffffff811163f1)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/bpf/inode.c (ffffffff8131e12d)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In mm/shmem.c (ffffffff813bc825)
Location: include/linux/mount.h:77
Inline: True
```
```
In mm/mincore.c (ffffffff813f6064)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - mm/mincore.c:do_mincore
```
```
In mm/madvise.c (ffffffff81426fef)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff81489592)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814a8ded)
Location: include/linux/mount.h:77
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
In fs/stat.c (ffffffff814b626d)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/stat.c:vfs_getattr_nosec
```
```
In fs/exec.c (ffffffff814b8703)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/exec.c:would_dump
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814c8fe9)
Location: include/linux/mount.h:77
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
In fs/fcntl.c (ffffffff814c9994)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (ffffffff814cbdf4)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/inode.c (ffffffff814d7ca6)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/inode.c:__file_remove_privs
  - fs/inode.c:__file_remove_privs
  - fs/inode.c:atime_needs_update
```
```
In fs/namespace.c (ffffffff814df293)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
```
In fs/xattr.c (ffffffff814ea979)
Location: include/linux/mount.h:77
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
In fs/utimes.c (ffffffff814ff0f9)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/init.c (ffffffff836ef048)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
```
```
In fs/remap_range.c (ffffffff81507798)
Location: include/linux/mount.h:77
Inline: True
```
```
In fs/proc_namespace.c (ffffffff8150f5ea)
Location: include/linux/mount.h:77
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff815175d4)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a8a4)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/verity/enable.c (ffffffff8153bfb1)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/locks.c (ffffffff81543e2f)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
```
```
In fs/coredump.c (ffffffff81550d72)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ioctl.c (ffffffff815beb50)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fat/file.c (ffffffff816387af)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/main.c (ffffffff81643b51)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff8164f436)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In security/commoncap.c (ffffffff8169a63b)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/apparmor/domain.c (ffffffff81702f5f)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff8171174f)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff8171655a)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_main.c (ffffffff81731826)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In io_uring/xattr.c (ffffffff817d3d43)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
```
```
In net/unix/af_unix.c (ffffffff81fac322)
Location: include/linux/mount.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_find_other
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
In kernel/sys.c (ffffffff8111fde1)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm_exe_file
```
```
In kernel/bpf/inode.c (ffffffff8134054d)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In mm/shmem.c (ffffffff813e8b25)
Location: include/linux/mount.h:76
Inline: True
```
```
In mm/mincore.c (ffffffff81421d14)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - mm/mincore.c:do_mincore
```
```
In mm/madvise.c (ffffffff814602d4)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/memcontrol.c (ffffffff814b89f1)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_write_event_control
```
```
In fs/open.c (ffffffff814d9e4d)
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
In fs/stat.c (ffffffff814e859d)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/stat.c:vfs_getattr_nosec
```
```
In fs/exec.c (ffffffff814eac13)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/exec.c:would_dump
  - fs/exec.c:begin_new_exec
```
```
In fs/namei.c (ffffffff814fb8a6)
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
In fs/fcntl.c (ffffffff814fc245)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/fcntl.c:setfl
```
```
In fs/ioctl.c (ffffffff814fe6a9)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/inode.c (ffffffff8150a486)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/inode.c:__file_remove_privs
  - fs/inode.c:__file_remove_privs
  - fs/inode.c:atime_needs_update
```
```
In fs/namespace.c (ffffffff81511a18)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/namespace.c:statmount_mnt_basic
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
```
In fs/xattr.c (ffffffff8151e819)
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
In fs/utimes.c (ffffffff81533d29)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/utimes.c:vfs_utimes
```
```
In fs/init.c (ffffffff8392209e)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/init.c:init_mkdir
  - fs/init.c:init_symlink
  - fs/init.c:init_link
  - fs/init.c:init_mknod
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
```
```
In fs/remap_range.c (ffffffff8153bf30)
Location: include/linux/mount.h:76
Inline: True
```
```
In fs/proc_namespace.c (ffffffff81543aea)
Location: include/linux/mount.h:76
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b9b4)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154eea4)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In fs/verity/enable.c (ffffffff81571291)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
```
In fs/locks.c (ffffffff8157930e)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/locks.c:generic_setlease
```
```
In fs/coredump.c (ffffffff81586c03)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/ioctl.c (ffffffff815f78fe)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
```
In fs/fat/file.c (ffffffff81671c9f)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/fat/file.c:fat_ioctl_set_attributes
  - fs/fat/file.c:fat_ioctl_set_attributes
```
```
In fs/ecryptfs/main.c (ffffffff8167d0e1)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In fs/exportfs/expfs.c (ffffffff816889d5)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
```
In security/commoncap.c (ffffffff816d6d7b)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
```
In security/apparmor/domain.c (ffffffff8174074f)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (ffffffff8174fab6)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
```
In security/apparmor/file.c (ffffffff8175502a)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - security/apparmor/file.c:__file_path_perm
```
```
In security/integrity/ima/ima_main.c (ffffffff81772246)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_kexec_cmdline
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:ima_file_mprotect
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In io_uring/xattr.c (ffffffff81817bb7)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
```
```
In net/unix/af_unix.c (ffffffff82079742)
Location: include/linux/mount.h:76
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_find_other
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
