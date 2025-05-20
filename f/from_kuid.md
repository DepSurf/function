# Function: <code>from_kuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8111deb0)
Location: kernel/user_namespace.c:264
Inline: True
Inline callers:
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_receive_msg
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - mm/oom_kill.c:dump_header
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8111deb0-ffffffff8111df24: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8112636d)
Location: kernel/user_namespace.c:264
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81125d80-ffffffff81125df4: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8112fe8a)
Location: kernel/user_namespace.c:310
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:SyS_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_disable
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8112f7d0-ffffffff8112f844: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113149a)
Location: kernel/user_namespace.c:311
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:dump_header
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81130de0-ffffffff81130e54: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113e358)
Location: kernel/user_namespace.c:417
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8113e260-ffffffff8113e270: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8114ccea)
Location: kernel/user_namespace.c:417
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/audit_fsnotify.c:audit_mark_handle_event
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8114cc00-ffffffff8114cc10: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115990a)
Location: kernel/user_namespace.c:417
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_name
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_set_loginuid
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81159820-ffffffff81159830: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116605b)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81165f70-ffffffff81165f80: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81171f1b)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81171e30-ffffffff81171e40: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81183bfb)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:format_corename
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/persistent.c:key_get_persistent
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81183b10-ffffffff81183b20: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8118095b)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:format_corename
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/persistent.c:key_get_persistent
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81180870-ffffffff81180880: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811819bb)
Location: kernel/user_namespace.c:412
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/open.c:chown_common
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:key_get_persistent
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811818d0-ffffffff811818e0: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811a995b)
Location: kernel/user_namespace.c:428
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/open.c:chown_common
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/quota/kqid.c:from_kqid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:key_get_persistent
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811a9870-ffffffff811a9880: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811dadaa)
Location: kernel/user_namespace.c:433
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/open.c:chown_common
  - fs/stat.c:generic_fillattr
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
  - fs/quota/kqid.c:from_kqid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:key_get_persistent
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811dac90-ffffffff811daca8: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812205ca)
Location: kernel/user_namespace.c:433
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/stat.c:generic_fillattr
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:may_write_xattr
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/kqid.c:from_kqid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:key_get_persistent
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/notify.c:build_unotif
  - security/apparmor/notify.c:build_unotif
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81220450-ffffffff81220468: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812368f7)
Location: kernel/user_namespace.c:433
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/shmem.c:shmem_parse_one
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/inode.c:inode_owner_or_capable
  - fs/mnt_idmapping.c:from_vfsuid
  - fs/mnt_idmapping.c:make_vfsuid
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_valid
  - fs/quota/kqid.c:from_kqid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:key_get_persistent
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/notify.c:build_v3_unotif
  - security/apparmor/notify.c:build_v3_unotif
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81236780-ffffffff81236798: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81251647)
Location: kernel/user_namespace.c:436
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:show_fault_oops
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_log_multicast
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/inode.c:bpf_parse_param
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_parse_one
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/inode.c:inode_owner_or_capable
  - fs/mnt_idmapping.c:make_vfsuid
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_valid
  - fs/quota/kqid.c:from_kqid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:proc_key_users_next
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_key_users_start
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:key_get_persistent
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/ipc.c:audit_mqueue_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/notify.c:build_v3_unotif
  - security/apparmor/notify.c:build_v3_unotif
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/integrity_audit.c:integrity_audit_message
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff812515b0-ffffffff812515c8: from_kuid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffff8000101e5cf0)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffff8000101e5b48-ffff8000101e5b7c: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0426618)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/inode.c:inode_owner_or_capable
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:format_corename
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
c0426500-c042651c: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0000000002563e4)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
c000000000256240-c000000000256258: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffe00015b8c0)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:__se_sys_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffe00015b71c-ffffffe00015b752: from_kuid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116a53b)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8116a450-ffffffff8116a460: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115d73b)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff8115d650-ffffffff8115d660: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116830b)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff81168220-ffffffff81168230: from_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
uid_t from_kuid(struct user_namespace *targ, kuid_t kuid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811759ab)
Location: kernel/user_namespace.c:411
Inline: True
Inline callers:
  - kernel/user_namespace.c:uid_m_show
  - kernel/user_namespace.c:from_kuid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:no_context
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_set_loginuid
  - kernel/audit.c:audit_log_session_info
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:show_special
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/auditsc.c:audit_log_pid_context
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/proc/base.c:proc_loginuid_read
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/keyring.c:find_keyring_by_name
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/proc.c:__key_user_next
  - security/keys/proc.c:proc_keys_next
  - security/keys/proc.c:proc_keys_start
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:rootid_owns_currentns
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_enforce
  - security/selinux/ss/services.c:security_set_bools
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/integrity_audit.c:integrity_audit_msg
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/tty/tty_audit.c:tty_audit_log
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/core/dev.c:__dev_set_promiscuity
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/netlabel/netlabel_user.c:netlbl_audit_start_common
```
**Symbols:**

```
ffffffff811758c0-ffffffff811758d0: from_kuid (STB_GLOBAL)
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
