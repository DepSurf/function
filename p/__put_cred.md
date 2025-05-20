# Function: <code>__put_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a2030)
Location: kernel/cred.c:134
Inline: True
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/cred.c:clone_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:copy_creds
  - kernel/cgroup.c:__cgroup_procs_write
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:SyS_access
  - fs/file_table.c:file_free_rcu
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:proc_pid_status
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_release
  - net/core/sock.c:sk_destruct
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:unix_stream_connect
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810a2030-ffffffff810a2075: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a57e0)
Location: kernel/cred.c:134
Inline: True
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:clone_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:SyS_access
  - fs/file_table.c:file_free_rcu
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:proc_pid_status
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810a57e0-ffffffff810a5825: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ab440)
Location: kernel/cred.c:134
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:SyS_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:clone_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:SyS_access
  - fs/file_table.c:file_free_rcu
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:proc_pid_status
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810ab440-ffffffff810ab485: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a8000)
Location: kernel/cred.c:135
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:SyS_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:clone_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:SyS_access
  - fs/file_table.c:file_free_rcu
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:proc_pid_status
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810a8000-ffffffff810a8045: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ae620)
Location: kernel/cred.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:SyS_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:clone_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:SyS_access
  - fs/file_table.c:file_free_rcu
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:proc_pid_status
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810ae620-ffffffff810ae665: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b5490)
Location: kernel/cred.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:proc_pid_status
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810b5490-ffffffff810b54d5: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810be5f0)
Location: kernel/cred.c:136
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:proc_pid_status
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key_auth.c:request_key_auth_revoke
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810be5f0-ffffffff810be635: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c46a0)
Location: kernel/cred.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810c46a0-ffffffff810c46fc: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cd950)
Location: kernel/cred.c:132
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810cd950-ffffffff810cd9ac: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d7450)
Location: kernel/cred.c:132
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/nsproxy.c:put_nsset
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
  - fs/open.c:access_override_creds
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_remove_personalities
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:__io_req_aux_free
  - fs/io-wq.c:io_worker_handle_work
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810d7450-ffffffff810d74ac: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d2350)
Location: kernel/cred.c:132
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/nsproxy.c:put_nsset
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
  - fs/open.c:access_override_creds
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_personality
  - fs/io_uring.c:io_remove_personalities
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_req_clean_work
  - fs/io-wq.c:io_impersonate_work
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810d2350-ffffffff810d23ac: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d3f30)
Location: kernel/cred.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/nsproxy.c:put_nsset
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_dismantle_req
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810d3f30-ffffffff810d3f8c: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810e70b0)
Location: kernel/cred.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/nsproxy.c:put_nsset
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_clean_op
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810e70b0-ffffffff810e710c: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff811013a0)
Location: kernel/cred.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/nsproxy.c:put_nsset
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - kernel/watch_queue.c:free_watch
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/aio.c:aio_fsync_work
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_clean_op
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff811013a0-ffffffff81101414: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81126520)
Location: kernel/cred.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/nsproxy.c:put_nsset
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - kernel/watch_queue.c:free_watch
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/aio.c:aio_fsync_work
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_clean_op
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81126520-ffffffff81126594: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff811339d0)
Location: kernel/cred.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/nsproxy.c:put_nsset
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
  - kernel/watch_queue.c:free_watch
  - fs/open.c:do_faccessat
  - fs/file_table.c:init_file
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/aio.c:aio_fsync_work
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_clean_op
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff811339d0-ffffffff81133a41: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113e940)
Location: kernel/cred.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/nsproxy.c:put_nsset
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
  - kernel/watch_queue.c:free_watch
  - fs/open.c:do_faccessat
  - fs/file_table.c:__fput
  - fs/file_table.c:init_file
  - fs/fs_context.c:put_fs_context
  - fs/aio.c:aio_fsync_work
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_clean_op
  - io_uring/register.c:__io_uring_register
  - io_uring/register.c:io_unregister_personality
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8113e940-ffffffff8113e9b3: __put_cred (STB_GLOBAL)
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
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffff80001012cd40)
Location: kernel/cred.c:132
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
**Symbols:**

```
ffff80001012cd40-ffff80001012cdbc: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c037ccd0)
Location: kernel/cred.c:132
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
c037ccd0-c037cd4c: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c0000000001759b0)
Location: kernel/cred.c:132
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:abort_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
c0000000001759b0-c000000000175a4c: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffe0000e12ec)
Location: kernel/cred.c:132
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffe0000e12ec-ffffffe0000e1354: __put_cred (STB_GLOBAL)
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
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c7cd0)
Location: kernel/cred.c:132
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810c7cd0-ffffffff810c7d2c: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b64f0)
Location: kernel/cred.c:132
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810b64f0-ffffffff810b654c: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c7220)
Location: kernel/cred.c:132
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810c7220-ffffffff810c727c: __put_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __put_cred(struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cf690)
Location: kernel/cred.c:132
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/fork.c:ksys_unshare
  - kernel/ptrace.c:__ptrace_unlink
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/user_namespace.c:unshare_userns
  - fs/open.c:do_faccessat
  - fs/file_table.c:file_free_rcu
  - fs/fs_context.c:put_fs_context
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/coredump.c:do_coredump
  - fs/proc/array.c:task_state
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/lsm.c:apparmor_getprocattr
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - net/core/sock.c:__sk_destruct
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/dns_resolver/dns_key.c:put_cred
```
**Symbols:**

```
ffffffff810cf690-ffffffff810cf6ec: __put_cred (STB_GLOBAL)
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
