# Function: <code>kref_get_not0</code>

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
In security/apparmor/apparmorfs.c (ffffffff813751aa)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:profile_remove
```
```
In security/apparmor/context.c (ffffffff81377378)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_get_task_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_restore_previous_label
```
```
In security/apparmor/domain.c (ffffffff8137a6ca)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/policy.c (ffffffff8137fc5a)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_find_child
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
```
```
In security/apparmor/procattr.c (ffffffff81382dc0)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff81383adc)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/resource.c (ffffffff8138754e)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81388bb0)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff81389267)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
```
In security/apparmor/net.c (ffffffff81390ab0)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81392aff)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
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
In security/apparmor/apparmorfs.c (ffffffff813accfb)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_abi_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/context.c (ffffffff813b0593)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff813b7d42)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff813bad33)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff813bd064)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813be382)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/resource.c (ffffffff813c1fef)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813c3715)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813c8b4f)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff813ca285)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813cc047)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813ceaec)
Location: security/apparmor/include/lib.h:79
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
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
In security/apparmor/apparmorfs.c (ffffffff813c3b08)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_abi_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/context.c (ffffffff813c7713)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff813cf15e)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff813d20fb)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_find_child
```
```
In security/apparmor/procattr.c (ffffffff813d4494)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813d5802)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/resource.c (ffffffff813d948f)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813daca5)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813e0167)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:__vec_find
  - security/apparmor/label.c:__label_insert
```
```
In security/apparmor/mount.c (ffffffff813e1905)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813e36c7)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813e616c)
Location: security/apparmor/include/lib.h:80
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
</details>
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
In <code>6.2</code>: Absent ⚠️
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
