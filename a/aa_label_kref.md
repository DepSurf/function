# Function: <code>aa_label_kref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81389810)
Location: security/apparmor/label.c:365
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/policy_ns.c:aa_free_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
**Symbols:**

```
ffffffff81389810-ffffffff813898d5: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c4400)
Location: security/apparmor/label.c:365
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_abi_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:aa_free_ns
```
**Symbols:**

```
ffffffff813c4400-ffffffff813c44cb: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dba10)
Location: security/apparmor/label.c:372
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_abi_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:aa_free_ns
```
**Symbols:**

```
ffffffff813dba10-ffffffff813dbadb: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ecab0)
Location: security/apparmor/label.c:376
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_free_or_put_new
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:free_proxy
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffffffff813ecab0-ffffffff813ecae2: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81414480)
Location: security/apparmor/label.c:376
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffffffff81414480-ffffffff814144b2: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81446810)
Location: security/apparmor/label.c:376
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/audit.c:aa_audit_rule_free
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffffffff81446810-ffffffff81446842: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81463740)
Location: security/apparmor/label.c:376
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffffffff81463740-ffffffff81463772: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814909f0)
Location: security/apparmor/label.c:372
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffffffff814909f0-ffffffff81490a22: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814aa8b0)
Location: security/apparmor/label.c:366
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffffffff814aa8b0-ffffffff814aa8e2: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8150cc58)
Location: security/apparmor/label.c:367
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_proxy_kref
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
  - security/apparmor/audit.c:aa_audit_rule_free
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
**Symbols:**

```
ffffffff81509920-ffffffff81509956: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81529b18)
Location: security/apparmor/label.c:367
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
  - security/apparmor/audit.c:aa_audit_rule_free
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
**Symbols:**

```
ffffffff81526790-ffffffff815267c6: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152d0e4)
Location: security/apparmor/label.c:367
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
  - security/apparmor/audit.c:aa_audit_rule_free
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
**Symbols:**

```
ffffffff8152c120-ffffffff8152c156: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158b4d4)
Location: security/apparmor/label.c:367
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
  - security/apparmor/audit.c:aa_audit_rule_free
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
**Symbols:**

```
ffffffff8158a500-ffffffff8158a536: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162ca54)
Location: security/apparmor/label.c:370
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:aa_get_current_ns
Direct callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
  - security/apparmor/audit.c:aa_audit_rule_free
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid_obj
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/lsm.c:begin_current_label_crit_section
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
```
**Symbols:**

```
ffffffff8162b940-ffffffff8162b98a: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e1504)
Location: security/apparmor/label.c:370
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:aa_get_current_ns
Direct callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
  - security/apparmor/audit.c:aa_audit_rule_free
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid_obj
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_task_prctl
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/lsm.c:begin_current_label_crit_section
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:aa_free_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
**Symbols:**

```
ffffffff816e0210-ffffffff816e025a: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8171aafc)
Location: security/apparmor/label.c:370
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:aa_get_current_ns
Direct callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
  - security/apparmor/audit.c:aa_audit_rule_free
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getsecid_obj
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_task_prctl
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/lsm.c:begin_current_label_crit_section
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:aa_free_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
**Symbols:**

```
ffffffff81719840-ffffffff8171988a: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff817595ac)
Location: security/apparmor/label.c:376
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:aa_get_current_ns
Direct callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_learning_count_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:begin_current_label_crit_section
  - security/apparmor/capability.c:audit_caps
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_current_policy_admin_capable
  - security/apparmor/policy.c:aa_current_policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__aa_profile_list_release
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_task_getlsmblob_obj
  - security/apparmor/lsm.c:apparmor_current_getlsmblob_subj
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:do_setattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_uring_sqpoll
  - security/apparmor/lsm.c:apparmor_uring_override_creds
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_file_lock
  - security/apparmor/lsm.c:apparmor_file_permission
  - security/apparmor/lsm.c:apparmor_file_receive
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:aa_free_root_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:begin_current_label_crit_section
  - security/apparmor/af_inet.c:aa_inet_sock_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_msg_perm
  - security/apparmor/af_inet.c:aa_inet_accept_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_connect_perm
  - security/apparmor/af_inet.c:aa_inet_bind_perm
  - security/apparmor/af_inet.c:begin_current_label_crit_section
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:knotif_update_from_uresp_name
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:aa_free_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
**Symbols:**

```
ffffffff817582e0-ffffffff8175832a: aa_label_kref (STB_GLOBAL)
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
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a16c0)
Location: security/apparmor/label.c:366
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:free_proxy
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffff8000105a16c0-ffff8000105a171c: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0751ec8)
Location: security/apparmor/label.c:366
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:free_proxy
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
c0751ec8-c0751f10: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071c240)
Location: security/apparmor/label.c:366
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_free_or_put_new
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:free_proxy
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
c00000000071c240-c00000000071c2a4: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ec26a)
Location: security/apparmor/label.c:366
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:free_proxy
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffffffe0003ec26a-ffffffe0003ec2be: aa_label_kref (STB_GLOBAL)
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
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a2e90)
Location: security/apparmor/label.c:366
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffffffff814a2e90-ffffffff814a2ec2: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814938b0)
Location: security/apparmor/label.c:366
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffffffff814938b0-ffffffff814938e2: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149ef30)
Location: security/apparmor/label.c:366
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffffffff8149ef30-ffffffff8149ef62: aa_label_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aa_label_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b7560)
Location: security/apparmor/label.c:366
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
**Symbols:**

```
ffffffff814b7560-ffffffff814b7592: aa_label_kref (STB_GLOBAL)
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
