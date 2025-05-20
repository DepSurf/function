# Function: <code>put_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810808ba)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - kernel/fork.c:SyS_unshare
```
```
In kernel/cred.c (ffffffff810a213b)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
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
```
```
In kernel/cgroup.c (ffffffff8111705a)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - kernel/cgroup.c:__cgroup_procs_write
```
```
In kernel/user_namespace.c (ffffffff8111f166)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff8120a8b0)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - fs/open.c:SyS_access
```
```
In fs/file_table.c (ffffffff8120e324)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/coredump.c (ffffffff8126f2d5)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81280d90)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/keys/keyctl.c (ffffffff813334d5)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81334036)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff813347a5)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813352ba)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
```
```
In security/apparmor/domain.c (ffffffff8137dac1)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff813845b8)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff8161b4ed)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:usbdev_release
```
```
In net/core/sock.c (ffffffff8170398e)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - net/core/sock.c:sk_destruct
```
```
In net/unix/af_unix.c (ffffffff817be945)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:unix_stream_connect
```
```
In net/dns_resolver/dns_key.c (ffffffff818173e0)
Location: include/linux/cred.h:268
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff818173e0-ffffffff818173f1: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810826fc)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - kernel/fork.c:SyS_unshare
```
```
In kernel/cred.c (ffffffff810a5d13)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
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
```
```
In kernel/cgroup.c (ffffffff8111e422)
Location: include/linux/cred.h:268
Inline: True
```
```
In kernel/user_namespace.c (ffffffff811270b3)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff812307bb)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - fs/open.c:SyS_access
```
```
In fs/file_table.c (ffffffff81234d54)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/coredump.c (ffffffff8129a979)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff812ade2b)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/keys/keyctl.c (ffffffff81368379)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81369515)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81369742)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8136a23a)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
```
```
In security/apparmor/domain.c (ffffffff813b7319)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff813befcf)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff8167becf)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff8176884e)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff8182e74d)
Location: include/linux/cred.h:268
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff81890bf8)
Location: include/linux/cred.h:268
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81890bf8-ffffffff81890c08: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104418e)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff8108715c)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - kernel/fork.c:SyS_unshare
```
```
In kernel/ptrace.c (ffffffff810937d6)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffff810ab973)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
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
```
```
In kernel/cgroup.c (ffffffff811267b2)
Location: include/linux/cred.h:259
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81130c53)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff81242d6b)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - fs/open.c:SyS_access
```
```
In fs/file_table.c (ffffffff81247904)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/coredump.c (ffffffff812af509)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff812c379d)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/keys/keyctl.c (ffffffff8137eb89)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8137fd25)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8137ff52)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81380a4a)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
```
```
In security/apparmor/domain.c (ffffffff813ce619)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff813d644f)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff816a9b8f)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff81796c7f)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff818601d4)
Location: include/linux/cred.h:259
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff818c5217)
Location: include/linux/cred.h:259
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff818c5217-ffffffff818c5227: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104307a)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff81083fcb)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - kernel/fork.c:SyS_unshare
```
```
In kernel/ptrace.c (ffffffff810908c6)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffff810a8559)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup.c (ffffffff8112745f)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
```
In kernel/user_namespace.c (ffffffff81132294)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff8124e4a0)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - fs/open.c:SyS_access
```
```
In fs/file_table.c (ffffffff81253047)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/coredump.c (ffffffff812bc94f)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff812d0a2f)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/keys/keyctl.c (ffffffff81392a19)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81393ba5)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81393dc5)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813948aa)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_revoke
```
```
In security/apparmor/domain.c (ffffffff813e272a)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff813ea0bd)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff816bebcf)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff817b5066)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff818848fe)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff818e4bb8)
Location: include/linux/cred.h:260
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff818e4bb8-ffffffff818e4bc9: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104665e)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff8108a8bb)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - kernel/fork.c:SyS_unshare
```
```
In kernel/ptrace.c (ffffffff81097736)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffff810aecf9)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81136787)
Location: include/linux/cred.h:261
Inline: True
```
```
In kernel/user_namespace.c (ffffffff8113eff4)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff81270420)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - fs/open.c:SyS_access
```
```
In fs/file_table.c (ffffffff81275147)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/coredump.c (ffffffff812e023c)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff812f5268)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/keys/keyctl.c (ffffffff813b8079)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff813b9241)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813b9415)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813ba07a)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_revoke
```
```
In security/apparmor/domain.c (ffffffff8140948b)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff814116c4)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff8172a59f)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff8182d4a2)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff81905adc)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff8196a9e7)
Location: include/linux/cred.h:261
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8196a9e7-ffffffff8196a9f7: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048c0e)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff8108e0ce)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff8109b046)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffff810b5afb)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81144d0a)
Location: include/linux/cred.h:260
Inline: True
```
```
In kernel/user_namespace.c (ffffffff8114d934)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff812960fd)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff8129b9d4)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/coredump.c (ffffffff8130c444)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813225f1)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/keys/keyctl.c (ffffffff813e8c5f)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff813e9fd1)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813ea18b)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813ead8a)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_revoke
```
```
In security/apparmor/domain.c (ffffffff8143aa65)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81443e74)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff81769fef)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff81875e51)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff8195d18f)
Location: include/linux/cred.h:260
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff819c447c)
Location: include/linux/cred.h:260
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff819c447c-ffffffff819c448c: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058ba0)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff8109635e)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810a3276)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffff810bed01)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115091f)
Location: include/linux/cred.h:278
Inline: True
```
```
In kernel/user_namespace.c (ffffffff8115a5f3)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff812aaeed)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff812b0757)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/coredump.c (ffffffff81321ca4)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81339701)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
```
In security/keys/keyctl.c (ffffffff8140345d)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81404a17)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81404bc5)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814057aa)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_revoke
```
```
In security/apparmor/domain.c (ffffffff8145789c)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8145f5ae)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff8178d6ff)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff81897c31)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff8199156a)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff819fb925)
Location: include/linux/cred.h:278
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff819fb925-ffffffff819fb93b: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c14a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff8109a8a0)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810a7f4a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffff810c4d7a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c355)
Location: include/linux/cred.h:280
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81166cd3)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff812c76e6)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff812cd097)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff8130a544)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/coredump.c (ffffffff81349aea)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813606e8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff8143006c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff814318c9)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81431c45)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8143286b)
Location: include/linux/cred.h:280
Inline: True
```
```
In security/apparmor/domain.c (ffffffff8148512b)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8148c9c1)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff817cafbf)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff818e216b)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff819fd43f)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff81a6aff8)
Location: include/linux/cred.h:280
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81a6aff8-ffffffff81a6b00e: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ca5a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810a0e60)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810ae56a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffff810cde8a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811682f5)
Location: include/linux/cred.h:280
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81172b93)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff812d90f6)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff812deab7)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff8131d514)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/io_uring.c (ffffffff81344997)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/coredump.c (ffffffff81361d8a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81378948)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff81449dcc)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8144b629)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8144b9a5)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8144c5db)
Location: include/linux/cred.h:280
Inline: True
```
```
In security/apparmor/domain.c (ffffffff8149f04b)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff814a6881)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff817fbbad)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff8191432e)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff81a340cf)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff81aa19e8)
Location: include/linux/cred.h:280
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81aa19e8-ffffffff81aa19fe: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061bc0)
Location: include/linux/cred.h:281
Inline: True
```
```
In kernel/fork.c (ffffffff810a7cc1)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810b610a)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/nsproxy.c (ffffffff810d62f4)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/cred.c (ffffffff810d7c21)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81179899)
Location: include/linux/cred.h:281
Inline: True
```
```
In kernel/user_namespace.c (ffffffff811849f3)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/watch_queue.c (ffffffff8124c94b)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In fs/open.c (ffffffff8130d75c)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/open.c:access_override_creds
```
```
In fs/file_table.c (ffffffff81315907)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff8135758e)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/aio.c (ffffffff813772aa)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
```
```
In fs/io_uring.c (ffffffff8138138b)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_remove_personalities
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:__io_req_aux_free
```
```
In fs/io-wq.c (ffffffff8138a620)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
```
In fs/coredump.c (ffffffff813a81cd)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813c1a29)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff8149b7cc)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8149d3b2)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8149da20)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8149e63b)
Location: include/linux/cred.h:281
Inline: True
```
```
In security/apparmor/domain.c (ffffffff814f85d6)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81503fcb)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff818cd7f7)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff819e633b)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff81b2441c)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff81b9d369)
Location: include/linux/cred.h:281
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81b9d369-ffffffff81b9d37f: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ffd5)
Location: include/linux/cred.h:281
Inline: True
```
```
In kernel/fork.c (ffffffff810a3a39)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810b12fc)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/nsproxy.c (ffffffff810d0e94)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/cred.c (ffffffff810d2a75)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81176609)
Location: include/linux/cred.h:281
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81181a43)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/watch_queue.c (ffffffff81256d8b)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In fs/open.c (ffffffff813196bc)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/open.c:access_override_creds
```
```
In fs/file_table.c (ffffffff81320e67)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff81363f60)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/aio.c (ffffffff8138559a)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
```
```
In fs/io_uring.c (ffffffff8138f5eb)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_personality
  - fs/io_uring.c:io_remove_personalities
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_req_clean_work
```
```
In fs/io-wq.c (ffffffff8139bdc7)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/io-wq.c:io_impersonate_work
```
```
In fs/coredump.c (ffffffff813b923e)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813d3924)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff814b9261)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff814bae96)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814bb500)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814bc12b)
Location: include/linux/cred.h:281
Inline: True
```
```
In security/apparmor/domain.c (ffffffff81515719)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff815213d0)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff818d88b7)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff819e5b4b)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff81b32c3c)
Location: include/linux/cred.h:281
Inline: True
Inline callers:
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff81c336e4)
Location: include/linux/cred.h:281
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81c336e4-ffffffff81c336fa: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061150)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810a467f)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810b28bc)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/nsproxy.c (ffffffff810d2a74)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/cred.c (ffffffff810d46a7)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177169)
Location: include/linux/cred.h:282
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81182b93)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/watch_queue.c (ffffffff8125b227)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In fs/open.c (ffffffff8131f957)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff81326f67)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff8136a9e0)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/aio.c (ffffffff8138c80a)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
```
```
In fs/io_uring.c (ffffffff8139eb26)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_dismantle_req
```
```
In fs/coredump.c (ffffffff813c021e)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813da754)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff814bf0b1)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff814c0d64)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814c13c0)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814c1ffb)
Location: include/linux/cred.h:282
Inline: True
```
```
In security/apparmor/domain.c (ffffffff8151c09c)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff815277d6)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff818bb967)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff819cbc5b)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff81b2535e)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff81c25a07)
Location: include/linux/cred.h:282
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81c25a07-ffffffff81c25a1d: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106ae10)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810b5e9f)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810c4a5c)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/nsproxy.c (ffffffff810e5bb4)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/cred.c (ffffffff810e7887)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119e894)
Location: include/linux/cred.h:282
Inline: True
```
```
In kernel/user_namespace.c (ffffffff811aac23)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/watch_queue.c (ffffffff81297027)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:free_watch
```
```
In fs/open.c (ffffffff8136cef7)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff81374527)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff813b96a0)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/aio.c (ffffffff813d9e4d)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
```
```
In fs/io_uring.c (ffffffff813eeff9)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_clean_op
```
```
In fs/coredump.c (ffffffff8141004e)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff8142be8e)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff81517ad1)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff815197ac)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81519e30)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8151a9eb)
Location: include/linux/cred.h:282
Inline: True
```
```
In security/apparmor/domain.c (ffffffff8157a15c)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81585a66)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff81951f73)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff81a7b2b6)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81bea43a)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff81d421d6)
Location: include/linux/cred.h:282
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81d421d6-ffffffff81d421ec: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810780fe)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810cc3a6)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810dbd6c)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/nsproxy.c (ffffffff810ff9fa)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/cred.c (ffffffff81101b06)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811cf004)
Location: include/linux/cred.h:282
Inline: True
```
```
In kernel/user_namespace.c (ffffffff811dc2b5)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/watch_queue.c (ffffffff812ed42b)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
```
```
In fs/open.c (ffffffff813eb1ba)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff813f3507)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff8143f0f8)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/aio.c (ffffffff8146431d)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
```
```
In fs/coredump.c (ffffffff814859db)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff814a5ace)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff815aa503)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff815ac388)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff815acb9b)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff815ad868)
Location: include/linux/cred.h:282
Inline: True
```
```
In security/apparmor/domain.c (ffffffff81618244)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8162656f)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In io_uring/io_uring.c (ffffffff816d88bf)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_clean_op
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
```
In drivers/base/firmware_loader/main.c (ffffffff819a03df)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/usb/core/devio.c (ffffffff81aaaf4d)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff81bef26d)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81d81dea)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff81f0eb33)
Location: include/linux/cred.h:282
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff816c8790-ffffffff816c87b2: put_cred (STB_LOCAL)
ffffffff81f0eb33-ffffffff81f0eb55: put_cred (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81088d0e)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810e9a56)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810fbe7c)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/nsproxy.c (ffffffff8112473a)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/cred.c (ffffffff81126cd6)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81212944)
Location: include/linux/cred.h:282
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81221b45)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/watch_queue.c (ffffffff813577eb)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
```
```
In fs/open.c (ffffffff8147340c)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff8147c2a7)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff814cdd78)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/aio.c (ffffffff814f464d)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
```
```
In fs/coredump.c (ffffffff81518f7d)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff8153b0de)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff81654803)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81656818)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816570bb)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81657ea8)
Location: include/linux/cred.h:282
Inline: True
```
```
In security/apparmor/audit.c (ffffffff816c148a)
Location: include/linux/cred.h:282
Inline: True
```
```
In security/apparmor/domain.c (ffffffff816cbadd)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/lsm.c (ffffffff816da8d9)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In io_uring/io_uring.c (ffffffff8178c552)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_clean_op
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b11f6a)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/usb/core/devio.c (ffffffff81c323ad)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff81d9babd)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81f4f32a)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff842b36e7)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108bc0e)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810f5667)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff81107f1c)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/nsproxy.c (ffffffff81131a3a)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/cred.c (ffffffff81134176)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812282f5)
Location: include/linux/cred.h:282
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81237ff5)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/trace/trace_events_user.c (ffffffff812c337a)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
```
```
In kernel/watch_queue.c (ffffffff8138905b)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
```
```
In fs/open.c (ffffffff814a7a81)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff814b0f58)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/file_table.c:init_file
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff81503f68)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/aio.c (ffffffff8152b41d)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
```
```
In fs/coredump.c (ffffffff8155087d)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff815733eb)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff8168d043)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8168f058)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8168f955)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81690728)
Location: include/linux/cred.h:282
Inline: True
```
```
In security/apparmor/audit.c (ffffffff816fa0aa)
Location: include/linux/cred.h:282
Inline: True
```
```
In security/apparmor/domain.c (ffffffff81704771)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/lsm.c (ffffffff8171406c)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In io_uring/io_uring.c (ffffffff817cd716)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_clean_op
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b6025d)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/usb/core/devio.c (ffffffff81c99691)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff81e09c9a)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81faebf5)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff83af63e7)
Location: include/linux/cred.h:282
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810938f5)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810fe9f7)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff811118bc)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/nsproxy.c (ffffffff8113c84a)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/cred.c (ffffffff8113f133)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812400f5)
Location: include/linux/cred.h:278
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81251af5)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/trace/trace_events_user.c (ffffffff812e14aa)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
```
```
In kernel/watch_queue.c (ffffffff813b2aab)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
```
```
In fs/open.c (ffffffff814d8d40)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff814e29b5)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:init_file
```
```
In fs/fs_context.c (ffffffff81538c28)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/aio.c (ffffffff815602ed)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
```
```
In fs/coredump.c (ffffffff8158670d)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff815abbad)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff816c953e)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff816cb5c2)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816cbee6)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816cccb8)
Location: include/linux/cred.h:278
Inline: True
```
```
In security/apparmor/audit.c (ffffffff81736e4a)
Location: include/linux/cred.h:278
Inline: True
```
```
In security/apparmor/domain.c (ffffffff81742029)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/lsm.c (ffffffff81752a71)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In io_uring/io_uring.c (ffffffff818112c1)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/register.c (ffffffff8182bdb8)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
  - io_uring/register.c:io_unregister_personality
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb3c9c)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/usb/core/devio.c (ffffffff81d4df51)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff81ec668a)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff8207c115)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff83d52127)
Location: include/linux/cred.h:278
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffff8000100f5804)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffff80001010854c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffff80001012d0d8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101db510)
Location: include/linux/cred.h:280
Inline: True
```
```
In kernel/user_namespace.c (ffff8000101e6aa8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffff80001037e450)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffff8000103851ac)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffff8000103d5904)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/io_uring.c (ffff800010402d3c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/coredump.c (ffff800010428444)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffff800010444fcc)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffff800010533b4c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffff8000105352ac)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffff800010535744)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffff800010536358)
Location: include/linux/cred.h:280
Inline: True
```
```
In security/apparmor/domain.c (ffff800010594e64)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffff80001059d96c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffff800010a2d300)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffff800010baca40)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffff800010cf4050)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffff8000114bb6a8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffff800010d72ed4-ffff800010d72f24: put_cred.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0353fac)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (c0361f0c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (c037d5bc)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (c041d71c)
Location: include/linux/cred.h:280
Inline: True
```
```
In kernel/user_namespace.c (c0427158)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (c0568de0)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (c056e094)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (c05af038)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/io_uring.c (c05d627c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/coredump.c (c05f10d8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (c0609c08)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (c06eb38c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (c06ec99c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c06ed1cc)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c06eda10)
Location: include/linux/cred.h:280
Inline: True
```
```
In security/apparmor/domain.c (c0745eb4)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (c074e3d8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (c0b02b24)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (c0ccaa50)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (c0dfb334)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (c0e6fdc8)
Location: include/linux/cred.h:280
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
c0e6fdc8-c0e6fe0c: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013b98c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (c00000000014fb30)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (c0000000001763d4)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024802c)
Location: include/linux/cred.h:280
Inline: True
```
```
In kernel/user_namespace.c (c0000000002572e0)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (c000000000473f20)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (c00000000047b124)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (c0000000004d814c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/io_uring.c (c00000000050f644)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/coredump.c (c000000000538638)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (c00000000055a4c0)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (c0000000006819f8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (c000000000683880)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c0000000006843b4)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c000000000684e98)
Location: include/linux/cred.h:280
Inline: True
```
```
In security/apparmor/domain.c (c00000000070a0c8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (c000000000715fc0)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (c000000000aeb5bc)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (c000000000c80714)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (c000000000e1a4e4)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (c000000000eb20f8)
Location: include/linux/cred.h:280
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
c000000000eb20f8-c000000000eb2150: put_cred (STB_LOCAL)
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
In kernel/fork.c (ffffffe0000c1b94)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffe0000cbedc)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffe0000e1840)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe0001532f0)
Location: include/linux/cred.h:280
Inline: True
```
```
In kernel/user_namespace.c (ffffffe00015c336)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffe000254112)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffe000257fd4)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffe00028f3da)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/io_uring.c (ffffffe0002b0584)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/coredump.c (ffffffe0002c66a8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffe0002dafec)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffe000393f5e)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffe000395216)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffe0003958b6)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffe000396018)
Location: include/linux/cred.h:280
Inline: True
```
```
In security/apparmor/domain.c (ffffffe0003e1f68)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffe0003e9c86)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffe00064d81c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffe00073e964)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffe00083fcde)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffe0000a2d06)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c5da)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff8109a780)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810a88da)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffff810c820a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81160915)
Location: include/linux/cred.h:280
Inline: True
```
```
In kernel/user_namespace.c (ffffffff8116b1b3)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff812d16d6)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff812d7097)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff81315af4)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/io_uring.c (ffffffff8133cf77)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/coredump.c (ffffffff8135a36a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81370f28)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff814423ac)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81443c09)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81443f85)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81444bbb)
Location: include/linux/cred.h:280
Inline: True
```
```
In security/apparmor/domain.c (ffffffff8149762b)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8149ee61)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff817b3f8d)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff818b432e)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff819d375f)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff81a40d78)
Location: include/linux/cred.h:280
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81a40d78-ffffffff81a40d8e: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104c7aa)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810891c0)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810972aa)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffff810b6a2a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81153b85)
Location: include/linux/cred.h:280
Inline: True
```
```
In kernel/user_namespace.c (ffffffff8115e3b3)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff812c2356)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff812c7d17)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff813066e4)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/io_uring.c (ffffffff8132dc3b)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/coredump.c (ffffffff8134b01a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff813619b8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff81432e08)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81434659)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814349d5)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8143560b)
Location: include/linux/cred.h:280
Inline: True
```
```
In security/apparmor/domain.c (ffffffff8148804b)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8148f881)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff817a59bd)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff8186e27e)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff8199051f)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff819fd968)
Location: include/linux/cred.h:280
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff819fd968-ffffffff819fd97e: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ca0a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff8109a730)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810a7e3a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffff810c775a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e6e5)
Location: include/linux/cred.h:280
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81168f83)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff812cf4e6)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff812d4ea7)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff813138e4)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/io_uring.c (ffffffff8133aa47)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/coredump.c (ffffffff81357e3a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff8136e9f8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff8143e54c)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff8143fda9)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81440045)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81440c5b)
Location: include/linux/cred.h:280
Inline: True
```
```
In security/apparmor/domain.c (ffffffff814936cb)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8149af01)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff817f0a2d)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff8190532e)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff81a3e1df)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff81aacc28)
Location: include/linux/cred.h:280
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81aacc28-ffffffff81aacc3e: put_cred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void put_cred(const struct cred *_cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105df24)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810a23ac)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff810aff6a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/cred.c (ffffffff810cfc2a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116bb15)
Location: include/linux/cred.h:280
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81176673)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In fs/open.c (ffffffff812e02f6)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff812e5d07)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/fs_context.c (ffffffff81325134)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/io_uring.c (ffffffff8134dbf8)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/coredump.c (ffffffff8136b51a)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff81382358)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff814556c6)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81456f59)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814572c5)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81457f4b)
Location: include/linux/cred.h:280
Inline: True
```
```
In security/apparmor/domain.c (ffffffff814ab6bc)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff814b3270)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In drivers/usb/core/devio.c (ffffffff8180ac6d)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff8192641e)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
```
```
In net/unix/af_unix.c (ffffffff81a49c92)
Location: include/linux/cred.h:280
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff81ab8f98)
Location: include/linux/cred.h:280
Inline: False
Direct callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81ab8f98-ffffffff81ab8fae: put_cred (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
