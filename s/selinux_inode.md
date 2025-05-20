# Function: <code>selinux_inode</code>

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
In security/selinux/hooks.c (ffffffff813a397c)
Location: security/selinux/include/objsec.h:174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (ffffffff813ad0e7)
Location: security/selinux/include/objsec.h:174
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
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
In security/selinux/hooks.c (ffffffff813c977c)
Location: security/selinux/include/objsec.h:178
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_read_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (ffffffff813d31a7)
Location: security/selinux/include/objsec.h:178
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81419490)
Location: security/selinux/include/objsec.h:171
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (ffffffff81420796)
Location: security/selinux/include/objsec.h:171
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/hooks.c (ffffffff81447080)
Location: security/selinux/include/objsec.h:168
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (ffffffff8144e398)
Location: security/selinux/include/objsec.h:168
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/hooks.c (ffffffff81460c10)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (ffffffff814681b8)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/hooks.c (ffffffff814b4455)
Location: security/selinux/include/objsec.h:162
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/selinuxfs.c (ffffffff814bc52e)
Location: security/selinux/include/objsec.h:162
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_bools
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
In security/selinux/hooks.c (ffffffff814d1ce5)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/selinuxfs.c (ffffffff814da010)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_bools
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
In security/selinux/hooks.c (ffffffff814d9a45)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_path_notify
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_getattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_move_mount
  - security/selinux/hooks.c:selinux_mount
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/selinuxfs.c (ffffffff814e1780)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_bools
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
In security/selinux/hooks.c (ffffffff81532945)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/selinuxfs.c (ffffffff8153a700)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_bools
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
In security/selinux/hooks.c (ffffffff815c1d7f)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/selinuxfs.c (ffffffff815d1e36)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_bools
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
In security/selinux/hooks.c (ffffffff8166e46f)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/selinuxfs.c (ffffffff8167fcc4)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_bools
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
In security/selinux/hooks.c (ffffffff816a6b3f)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/selinuxfs.c (ffffffff816b7d9c)
Location: security/selinux/include/objsec.h:161
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_bools
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
In security/selinux/hooks.c (ffffffff816e365f)
Location: security/selinux/include/objsec.h:163
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_uring_cmd
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_listxattr
  - security/selinux/hooks.c:selinux_inode_getxattr
  - security/selinux/hooks.c:selinux_inode_remove_acl
  - security/selinux/hooks.c:selinux_inode_get_acl
  - security/selinux/hooks.c:selinux_inode_set_acl
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setattr
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_readlink
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security_anon
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_quota_on
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:backing_inode_security
  - security/selinux/hooks.c:inode_security
  - security/selinux/hooks.c:inode_security
```
```
In security/selinux/selinuxfs.c (ffffffff816f387f)
Location: security/selinux/include/objsec.h:163
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
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
In security/selinux/hooks.c (ffff80001054e6d4)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (ffff8000105565c0)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/hooks.c (c06fe1d4)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (c070abf4)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/hooks.c (c0000000006ae760)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (c0000000006b53d0)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/hooks.c (ffffffe0003a8200)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (ffffffe0003adcd0)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/hooks.c (ffffffff814591f0)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (ffffffff81460798)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/hooks.c (ffffffff81449c20)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (ffffffff814511c8)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/hooks.c (ffffffff81455290)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (ffffffff8145c838)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/hooks.c (ffffffff81467820)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_invalidate_secctx
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernel_module_from_file
  - security/selinux/hooks.c:selinux_kernel_create_files_as
  - security/selinux/hooks.c:selinux_file_open
  - security/selinux/hooks.c:selinux_file_ioctl
  - security/selinux/hooks.c:selinux_file_permission
  - security/selinux/hooks.c:selinux_inode_copy_up
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_rename
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_free_security
  - security/selinux/hooks.c:selinux_inode_alloc_security
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_bprm_set_creds
  - security/selinux/hooks.c:selinux_binder_transfer_file
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_link
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:inode_has_perm
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_sb_clone_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:__inode_security_revalidate
```
```
In security/selinux/selinuxfs.c (ffffffff81473fd8)
Location: security/selinux/include/objsec.h:158
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
</details>
</li>
</ul>

## Differences
