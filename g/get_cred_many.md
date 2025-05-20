# Function: <code>get_cred_many</code>

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
In kernel/ptrace.c (ffffffff81110f45)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/cred.c (ffffffff8113eaba)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff813b2bcf)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff814e2685)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/fs_context.c (ffffffff81538fca)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In security/keys/process_keys.c (ffffffff816cad14)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816cbea5)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816cce83)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/audit.c (ffffffff8173733a)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/domain.c (ffffffff8174197e)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
```
```
In io_uring/io_uring.c (ffffffff8180e6cd)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_prep_async_work
```
```
In io_uring/sqpoll.c (ffffffff818201d0)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In io_uring/register.c (ffffffff8182bb89)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
```
```
In drivers/usb/core/devio.c (ffffffff81d4d3cc)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81ecbcb4)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff8207c0d7)
Location: include/linux/cred.h:215
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
