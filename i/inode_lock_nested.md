# Function: <code>inode_lock_nested</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8124401a)
Location: include/linux/fs.h:770
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff8124f805)
Location: include/linux/fs.h:770
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/ecryptfs/inode.c (ffffffff813366a6)
Location: include/linux/fs.h:770
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff813545b2)
Location: include/linux/fs.h:770
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff813621e8)
Location: include/linux/fs.h:770
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff813adad0)
Location: include/linux/fs.h:770
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
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
In fs/namei.c (ffffffff81256f68)
Location: include/linux/fs.h:723
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff81262835)
Location: include/linux/fs.h:723
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/ecryptfs/inode.c (ffffffff8134c366)
Location: include/linux/fs.h:723
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff8136a872)
Location: include/linux/fs.h:723
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff813789e8)
Location: include/linux/fs.h:723
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff813c48e0)
Location: include/linux/fs.h:723
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_rmdir_op
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
In fs/namei.c (ffffffff8126307a)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff812700a5)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff812dec2b)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff812dfcb6)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff81360ec7)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff8137ed52)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff8138d36a)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff813da35b)
Location: include/linux/fs.h:742
Inline: True
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
In fs/namei.c (ffffffff81286417)
Location: include/linux/fs.h:746
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff812929e5)
Location: include/linux/fs.h:746
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff8130359b)
Location: include/linux/fs.h:746
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff81304636)
Location: include/linux/fs.h:746
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff81385b97)
Location: include/linux/fs.h:746
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff813a3d98)
Location: include/linux/fs.h:746
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff813b272e)
Location: include/linux/fs.h:746
Inline: True
Inline callers:
  - ipc/mqueue.c:SyS_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff814006b3)
Location: include/linux/fs.h:746
Inline: True
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
In fs/namei.c (ffffffff812ad9eb)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff812b87e8)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff81331526)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8133210d)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff813b48f6)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff813d317e)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff813e0c6a)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff814323e4)
Location: include/linux/fs.h:748
Inline: True
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
In fs/namei.c (ffffffff812c2b1e)
Location: include/linux/fs.h:796
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff812cd938)
Location: include/linux/fs.h:796
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff81348916)
Location: include/linux/fs.h:796
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff813494fd)
Location: include/linux/fs.h:796
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff813cde16)
Location: include/linux/fs.h:796
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff813ed86e)
Location: include/linux/fs.h:796
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff813fb45a)
Location: include/linux/fs.h:796
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff8144e59f)
Location: include/linux/fs.h:796
Inline: True
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
In fs/namei.c (ffffffff812df261)
Location: include/linux/fs.h:811
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff812ea6e8)
Location: include/linux/fs.h:811
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff81370e64)
Location: include/linux/fs.h:811
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8137210f)
Location: include/linux/fs.h:811
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff813f8956)
Location: include/linux/fs.h:811
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff81419aae)
Location: include/linux/fs.h:811
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff814277d1)
Location: include/linux/fs.h:811
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff8147bff1)
Location: include/linux/fs.h:811
Inline: True
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
In fs/namei.c (ffffffff812f0d71)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff812fc118)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff81389344)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8138a71f)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff814127b6)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff814338fe)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff81441501)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff81495cc1)
Location: include/linux/fs.h:825
Inline: True
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
In fs/namei.c (ffffffff81328fd1)
Location: include/linux/fs.h:843
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff81334c58)
Location: include/linux/fs.h:843
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff813d40b4)
Location: include/linux/fs.h:843
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff813d5abf)
Location: include/linux/fs.h:843
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff81460425)
Location: include/linux/fs.h:843
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff814839be)
Location: include/linux/fs.h:843
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff814923a9)
Location: include/linux/fs.h:843
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff814ecf88)
Location: include/linux/fs.h:843
Inline: True
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
In fs/namei.c (ffffffff81334341)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff813405c8)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff813e5df4)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff813e77af)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff8147c045)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff814a102e)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff814afbf9)
Location: include/linux/fs.h:806
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff8150aa28)
Location: include/linux/fs.h:806
Inline: True
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
In fs/namei.c (ffffffff8133a411)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff81346af8)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff813ec9f4)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff813ee17f)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff81481aee)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff814a715e)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff814b5a39)
Location: include/linux/fs.h:807
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff81511f94)
Location: include/linux/fs.h:807
Inline: True
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
In fs/namei.c (ffffffff813879b2)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff81394558)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff8143e924)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8143f98f)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff814d98ae)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/fuse/dir.c (ffffffff814ec8c2)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/tracefs/inode.c (ffffffff814ff1ee)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff8150e129)
Location: include/linux/fs.h:819
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff8156fb94)
Location: include/linux/fs.h:819
Inline: True
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
In fs/namei.c (ffffffff814088d7)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff814164d5)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff814ba264)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff814bbefc)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff815670ef)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/fuse/dir.c (ffffffff8157b612)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/tracefs/inode.c (ffffffff815904ae)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff815a0f63)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff8160c8af)
Location: include/linux/fs.h:774
Inline: True
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
In fs/namei.c (ffffffff81492e7b)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:lock_rename
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff814a18c5)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff81551aa4)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff81553a27)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff8160a70f)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/fuse/dir.c (ffffffff81620f3a)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/tracefs/inode.c (ffffffff8163791e)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff8164a953)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff816be1a6)
Location: include/linux/fs.h:789
Inline: True
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
In fs/namei.c (ffffffff814c8f83)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lock_rename_child
  - fs/namei.c:lock_rename_child
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff814d9fe7)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/inode.c:lock_two_inodes
  - fs/inode.c:lock_two_inodes
```
```
In fs/configfs/file.c (ffffffff815897d4)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8158b7b7)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff816425ef)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/fuse/dir.c (ffffffff8165938a)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/tracefs/inode.c (ffffffff8166fd1e)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff81682c93)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff816f6c56)
Location: include/linux/fs.h:804
Inline: True
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
In fs/namei.c (ffffffff814fb841)
Location: include/linux/fs.h:837
Inline: True
Inline callers:
  - fs/namei.c:do_renameat2
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:lock_rename_child
  - fs/namei.c:lock_rename_child
  - fs/namei.c:lock_two_directories
  - fs/namei.c:lock_two_directories
  - fs/namei.c:lock_two_directories
  - fs/namei.c:lock_two_directories
  - fs/namei.c:lock_two_directories
  - fs/namei.c:lock_two_directories
  - fs/namei.c:__kern_path_locked
```
```
In fs/inode.c (ffffffff81508eba)
Location: include/linux/fs.h:837
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff815c23e7)
Location: include/linux/fs.h:837
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff815c44ea)
Location: include/linux/fs.h:837
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff8167bc22)
Location: include/linux/fs.h:837
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/fuse/dir.c (ffffffff8169307a)
Location: include/linux/fs.h:837
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
```
In fs/tracefs/inode.c (ffffffff816aa6fe)
Location: include/linux/fs.h:837
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff816bf093)
Location: include/linux/fs.h:837
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff817339c9)
Location: include/linux/fs.h:837
Inline: True
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
In fs/namei.c (ffff80001039a53c)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffff8000103abb14)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffff8000104598cc)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffff80001045ad10)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffff8000104f3bb0)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffff800010519338)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffff800010529778)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - ipc/mqueue.c:__arm64_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffff80001058bce4)
Location: include/linux/fs.h:825
Inline: True
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
In fs/namei.c (c0580a1c)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (c058cba0)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (c061b474)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (c061c8dc)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (c06b15ac)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (c06d3a5c)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (c06e4ac8)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (c073c870)
Location: include/linux/fs.h:825
Inline: True
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
In fs/namei.c (c000000000495200)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (c0000000004a6c7c)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (c00000000057489c)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (c000000000576748)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (c000000000633f78)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (c000000000662808)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (c0000000006763e0)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (c0000000006fcf54)
Location: include/linux/fs.h:825
Inline: True
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
In fs/namei.c (ffffffe000267c1e)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffe00027109e)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffe0002ea530)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffe0002eb604)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffe000362fec)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffe0003826e8)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffe00038dbb6)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffe0003da03c)
Location: include/linux/fs.h:825
Inline: True
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
In fs/namei.c (ffffffff812e9351)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff812f46f8)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff81381924)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff81382cff)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff8140ad96)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff8142bede)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff81439ae1)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff8148e2a1)
Location: include/linux/fs.h:825
Inline: True
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
In fs/namei.c (ffffffff812d9f91)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff812e5318)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff813723b4)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8137378f)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff813fb816)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff8141c95e)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff8142a551)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff8147ecc1)
Location: include/linux/fs.h:825
Inline: True
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
In fs/namei.c (ffffffff812e7161)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff812f2508)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff8137f3f4)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff813807cf)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff81408116)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff8142807e)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff81435c81)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff8148a341)
Location: include/linux/fs.h:825
Inline: True
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
In fs/namei.c (ffffffff812f80e1)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/namei.c:do_unlinkat
  - fs/namei.c:do_rmdir
  - fs/namei.c:filename_create
  - fs/namei.c:kern_path_locked
```
```
In fs/inode.c (ffffffff81303b38)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/inode.c:lock_two_nondirectories
```
```
In fs/configfs/file.c (ffffffff81392ef4)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
```
```
In fs/configfs/dir.c (ffffffff8139428f)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
  - fs/configfs/dir.c:configfs_register_group
```
```
In fs/ecryptfs/inode.c (ffffffff8141ddd6)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
```
In fs/tracefs/inode.c (ffffffff8143ef3e)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_syscall_rmdir
```
```
In ipc/mqueue.c (ffffffff8144de21)
Location: include/linux/fs.h:825
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
```
In security/apparmor/apparmorfs.c (ffffffff814a200c)
Location: include/linux/fs.h:825
Inline: True
```
</details>
</li>
</ul>

## Differences
