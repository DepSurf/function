# Function: <code>put_cred_many</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
```
```
In kernel/fork.c (ffffffff810fe9f7)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
```
```
In kernel/ptrace.c (ffffffff811118bc)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/nsproxy.c (ffffffff8113c84a)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - kernel/nsproxy.c:put_nsset
```
```
In kernel/cred.c (ffffffff8113f133)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
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
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812400f5)
Location: include/linux/cred.h:261
Inline: True
```
```
In kernel/user_namespace.c (ffffffff81251af5)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/trace/trace_events_user.c (ffffffff812e14aa)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
```
```
In kernel/watch_queue.c (ffffffff813b2aab)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
```
```
In fs/open.c (ffffffff814d8d40)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/file_table.c (ffffffff814e29b5)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - fs/file_table.c:__fput
  - fs/file_table.c:init_file
```
```
In fs/fs_context.c (ffffffff81538c28)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
```
```
In fs/aio.c (ffffffff815602ed)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - fs/aio.c:aio_fsync_work
```
```
In fs/coredump.c (ffffffff8158670d)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/array.c (ffffffff815abbad)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In security/keys/keyctl.c (ffffffff816c953e)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff816cb5c2)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816cbee6)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816cccb8)
Location: include/linux/cred.h:261
Inline: True
```
```
In security/apparmor/audit.c (ffffffff81736e4a)
Location: include/linux/cred.h:261
Inline: True
```
```
In security/apparmor/domain.c (ffffffff81742029)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/lsm.c (ffffffff81752a71)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In io_uring/io_uring.c (ffffffff818112c1)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_clean_op
```
```
In io_uring/register.c (ffffffff8182bdb8)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
  - io_uring/register.c:io_unregister_personality
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb3c9c)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/usb/core/devio.c (ffffffff81d4df51)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff81ec668a)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff8207c115)
Location: include/linux/cred.h:261
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/dns_resolver/dns_key.c (ffffffff83d52127)
Location: include/linux/cred.h:261
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
