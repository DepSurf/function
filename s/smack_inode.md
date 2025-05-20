# Function: <code>smack_inode</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c2c2a)
Location: security/smack/smack.h:378
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e779c)
Location: security/smack/smack.h:378
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81434c96)
Location: security/smack/smack.h:372
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814626e8)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147c498)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814d1e98)
Location: security/smack/smack.h:353
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814ef33a)
Location: security/smack/smack.h:346
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f63ca)
Location: security/smack/smack.h:346
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81550f1a)
Location: security/smack/smack.h:346
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815edacd)
Location: security/smack/smack.h:346
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169dc8d)
Location: security/smack/smack.h:337
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d68f5)
Location: security/smack/smack.h:338
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_fs_context_submount
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81713278)
Location: security/smack/smack.h:337
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_uring_cmd
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getlsmblob
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_fs_context_submount
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056d200)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c07209b0)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d1750)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c1ab6)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81474a78)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81465498)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81470b18)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814882fb)
Location: security/smack/smack.h:360
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_inode_copy_up
  - security/smack/smack_lsm.c:smack_inode_getsecctx
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_kernel_create_files_as
  - security/smack/smack_lsm.c:smack_file_open
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getsecid
  - security/smack/smack_lsm.c:smack_inode_getsecurity
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_post_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_set_mnt_opts
```
</details>
</li>
</ul>

## Differences
