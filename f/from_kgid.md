# Function: <code>from_kgid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8111e030)
Location: kernel/user_namespace.c:332
Inline: True
Inline callers:
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_exit
  - kernel/auditsc.c:audit_log_task
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/coredump.c:do_coredump
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
  - net/netlink/af_netlink.c:__netlink_sendskb
  - net/netlink/af_netlink.c:__netlink_sendskb
```
**Symbols:**

```
ffffffff8111e030-ffffffff8111e0a5: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8112643d)
Location: kernel/user_namespace.c:332
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/ptrace.c:ptrace_has_cap
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
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
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81125f00-ffffffff81125f75: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8112ff4a)
Location: kernel/user_namespace.c:378
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
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
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff8112f950-ffffffff8112f9c5: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113155a)
Location: kernel/user_namespace.c:379
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
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
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81130f60-ffffffff81130fd5: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113e3c8)
Location: kernel/user_namespace.c:485
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
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
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff8113e290-ffffffff8113e2a4: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8114cd5a)
Location: kernel/user_namespace.c:485
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff8114cc30-ffffffff8114cc44: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115997a)
Location: kernel/user_namespace.c:485
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_name
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_exit
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:do_coredump
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/condition.c:tomoyo_condition
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81159850-ffffffff81159864: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811660cb)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:__fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81165fa0-ffffffff81165fb4: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81171f8b)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81171e60-ffffffff81171e74: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81183c6b)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:format_corename
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81183b40-ffffffff81183b54: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811809cb)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:format_corename
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff811808a0-ffffffff811808b4: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81181a2b)
Location: kernel/user_namespace.c:480
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
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
  - fs/inode.c:inode_init_owner
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81181900-ffffffff81181914: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811a99cb)
Location: kernel/user_namespace.c:496
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
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
  - fs/inode.c:inode_init_owner
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/quota/kqid.c:from_kqid
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff811a98a0-ffffffff811a98b4: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811dae2a)
Location: kernel/user_namespace.c:501
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/stat.c:generic_fillattr
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
  - fs/inode.c:inode_init_owner
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_valid
  - fs/quota/kqid.c:from_kqid
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/fat/file.c:fat_setattr
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff811dace0-ffffffff811dacfc: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8122065a)
Location: kernel/user_namespace.c:501
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/open.c:chown_common
  - fs/stat.c:generic_fillattr
  - fs/exec.c:bprm_fill_uid
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_should_drop_suidgid
  - fs/xattr.c:may_write_xattr
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_valid
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/kqid.c:from_kqid
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
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff812204c0-ffffffff812204dc: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81236987)
Location: kernel/user_namespace.c:501
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/shmem.c:shmem_parse_one
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
  - fs/mnt_idmapping.c:from_vfsgid
  - fs/mnt_idmapping.c:make_vfsgid
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_valid
  - fs/quota/kqid.c:from_kqid
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff812367f0-ffffffff8123680c: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81251b97)
Location: kernel/user_namespace.c:504
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/audit.c:audit_log_task_info
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/auditsc.c:audit_log_uring
  - kernel/bpf/inode.c:bpf_parse_param
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - mm/shmem.c:shmem_parse_one
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
  - fs/mnt_idmapping.c:make_vfsgid
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_valid
  - fs/quota/kqid.c:from_kqid
  - fs/ext4/inode.c:ext4_fill_raw_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:iattr_to_fattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff812516b0-ffffffff812516cc: from_kgid (STB_GLOBAL)
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
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffff8000101e5d68)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffff8000101e5bc8-ffff8000101e5bfc: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0426690)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/coredump.c:format_corename
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
c0426548-c0426568: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c000000000256494)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
c0000000002562b0-c0000000002562cc: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffe00015b926)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffe00015b796-ffffffe00015b7ce: from_kgid (STB_GLOBAL)
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
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116a5ab)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff8116a480-ffffffff8116a494: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115d7ab)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff8115d680-ffffffff8115d694: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116837b)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff81168250-ffffffff81168264: from_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
gid_t from_kgid(struct user_namespace *targ, kgid_t kgid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81175a1b)
Location: kernel/user_namespace.c:479
Inline: True
Inline callers:
  - kernel/user_namespace.c:gid_m_show
  - kernel/user_namespace.c:from_kgid_munged
  - kernel/user_namespace.c:create_user_ns
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/auditsc.c:audit_log_task
  - kernel/auditsc.c:show_special
  - kernel/bpf/helpers.c:bpf_get_current_uid_gid
  - fs/exec.c:prepare_binprm
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/posix_acl.c:posix_acl_to_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_valid
  - fs/ext4/inode.c:ext4_do_update_inode
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/acl.c:__ext4_set_acl
  - fs/fuse/dev.c:fuse_get_req
  - fs/fuse/dir.c:fuse_do_setattr
  - security/keys/request_key.c:call_sbin_request_key
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
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - drivers/base/core.c:dev_uevent
  - net/core/dev.c:__dev_set_promiscuity
```
**Symbols:**

```
ffffffff811758f0-ffffffff81175904: from_kgid (STB_GLOBAL)
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
