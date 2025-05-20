# Function: <code>get_new_cred</code>

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
In kernel/cred.c (ffffffff810a1eb9)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff8120e116)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff81334013)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81334776)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81335400)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8137d991)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff81619d23)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/unix/af_unix.c (ffffffff817be980)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:unix_stream_connect
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
In kernel/cred.c (ffffffff810a5d2f)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff81234b46)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff81368f17)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8136970a)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8136a37e)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff813b7127)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff8167c78e)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff8182e774)
Location: include/linux/cred.h:231
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff81093481)
Location: include/linux/cred.h:222
Inline: True
```
```
In kernel/cred.c (ffffffff810ab98f)
Location: include/linux/cred.h:222
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812476f6)
Location: include/linux/cred.h:222
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff8137f727)
Location: include/linux/cred.h:222
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8137ff1a)
Location: include/linux/cred.h:222
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81380b8e)
Location: include/linux/cred.h:222
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff813ce427)
Location: include/linux/cred.h:222
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff816aa4b2)
Location: include/linux/cred.h:222
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff818601fb)
Location: include/linux/cred.h:222
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8109056a)
Location: include/linux/cred.h:223
Inline: True
```
```
In kernel/cred.c (ffffffff810a8543)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff81252eff)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff8139362c)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81393d9a)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813949e8)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff813e261d)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff816bf38f)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81884924)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810973da)
Location: include/linux/cred.h:224
Inline: True
```
```
In kernel/cred.c (ffffffff810aece3)
Location: include/linux/cred.h:224
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff81274fff)
Location: include/linux/cred.h:224
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff813b8cb6)
Location: include/linux/cred.h:224
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813b93ea)
Location: include/linux/cred.h:224
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813ba18e)
Location: include/linux/cred.h:224
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8140930d)
Location: include/linux/cred.h:224
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff8172ad74)
Location: include/linux/cred.h:224
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81905b02)
Location: include/linux/cred.h:224
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8109a8aa)
Location: include/linux/cred.h:223
Inline: True
```
```
In kernel/cred.c (ffffffff810b5b0a)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff8129b8bf)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff813e9a46)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813ea160)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813eae7b)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8143a8f1)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817699ac)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff8195d1b7)
Location: include/linux/cred.h:223
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a2adf)
Location: include/linux/cred.h:228
Inline: True
```
```
In kernel/cred.c (ffffffff810bed15)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812b07d1)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In security/keys/process_keys.c (ffffffff8140446e)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81404b99)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814058b2)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8145771d)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff8178e03c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81991597)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810a7789)
Location: include/linux/cred.h:228
Inline: True
```
```
In kernel/cred.c (ffffffff810c4daa)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812cd114)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff8130a6a3)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In security/keys/process_keys.c (ffffffff81431281)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81431c1d)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81432992)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff81484edb)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817cc8da)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff819fd47b)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810adda9)
Location: include/linux/cred.h:228
Inline: True
```
```
In kernel/cred.c (ffffffff810cdeba)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812deb34)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff8131d663)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff81344cab)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffff8144afe1)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8144b97d)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8144c702)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8149edfb)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817fd576)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81a3410b)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810b5889)
Location: include/linux/cred.h:229
Inline: True
```
```
In kernel/cred.c (ffffffff810d7c51)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff8124c809)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff81315984)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff81357731)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff81381529)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_queue_async_work
```
```
In security/keys/process_keys.c (ffffffff8149cbd5)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8149d9f8)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8149e762)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff814f83c2)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff818ccd9e)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81b24462)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810b0a79)
Location: include/linux/cred.h:229
Inline: True
```
```
In kernel/cred.c (ffffffff810d2aa5)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff81256c49)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff81320ee4)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff8136413b)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8138bcec)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - fs/io_uring.c:io_register_personality
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_grab_identity
```
```
In security/keys/process_keys.c (ffffffff814ba675)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814bb4d8)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814bc252)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff81515512)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff818d7f96)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81b32c82)
Location: include/linux/cred.h:229
Inline: True
Inline callers:
  - net/unix/af_unix.c:copy_peercred
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810b2019)
Location: include/linux/cred.h:230
Inline: True
```
```
In kernel/cred.c (ffffffff810d46c6)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff8125b0e9)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff81326fe4)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff8136abaf)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8139ec41)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_prep_async_work
```
```
In security/keys/process_keys.c (ffffffff814c04f5)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814c1398)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814c211f)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8151be93)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff818bae85)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81b253ad)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810c3d1f)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/cred.c (ffffffff810e78a6)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff81296ee9)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff813745a4)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff813b986f)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff813ee625)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_prep_async_work
```
```
In security/keys/process_keys.c (ffffffff81518f15)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81519e08)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8151ab0f)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff81579f53)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff81951611)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81a7ce88)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81bea40a)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810db4b4)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/cred.c (ffffffff81101b30)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff812ed55c)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff813f3595)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff8143f2d7)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In security/keys/process_keys.c (ffffffff815abb23)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff815acb70)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff815ad9f8)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8161802f)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In io_uring/io_uring.c (ffffffff816d84cd)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_prep_async_work
```
```
In drivers/usb/core/devio.c (ffffffff81aaa28e)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81bf2d48)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81d81dbe)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810fb344)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/cred.c (ffffffff81126156)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff8135792c)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff8147c345)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff814ce119)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In security/keys/process_keys.c (ffffffff81655fa3)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81657090)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81658058)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/audit.c (ffffffff816c1bb1)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/domain.c (ffffffff816cb5da)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
```
```
In io_uring/io_uring.c (ffffffff8178c3ca)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_prep_async_work
```
```
In io_uring/sqpoll.c (ffffffff8179adb0)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In drivers/usb/core/devio.c (ffffffff81c3160e)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81da0277)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81f4f2fe)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff81107604)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/cred.c (ffffffff81133606)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff8138918e)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff814b0ee3)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/fs_context.c (ffffffff81504319)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In security/keys/process_keys.c (ffffffff8168e7d3)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8168f929)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816908d6)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/audit.c (ffffffff816fa734)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/domain.c (ffffffff817040e0)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
```
```
In io_uring/io_uring.c (ffffffff817cd5d2)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_prep_async_work
```
```
In io_uring/sqpoll.c (ffffffff817dbe5f)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In drivers/usb/core/devio.c (ffffffff81c9889c)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81e0f277)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81faebca)
Location: include/linux/cred.h:230
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/cred.c (ffffffff8113e566)
Location: include/linux/cred.h:196
Inline: True
Inline callers:
  - kernel/cred.c:override_creds
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
In kernel/ptrace.c (ffff800010107e38)
Location: include/linux/cred.h:228
Inline: True
```
```
In kernel/cred.c (ffff80001012d128)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffff800010385258)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffff8000103d5a8c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffff800010403020)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffff800010534d34)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffff80001053570c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffff80001053667c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffff800010594cd0)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffff800010a2e9b0)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffff800010cf409c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (c0361e84)
Location: include/linux/cred.h:228
Inline: True
```
```
In kernel/cred.c (c037d668)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (c056e12c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (c05af460)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (c05d64b8)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (c06ec3c4)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c06ed184)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c06edb58)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (c0745c2c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (c0b046a4)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (c0dfb390)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (c00000000014f1ec)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_link
```
```
In kernel/cred.c (c00000000017645c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (c00000000047b1fc)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (c0000000004d835c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (c00000000050f98c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (c00000000068313c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c000000000684378)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c000000000685048)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (c000000000709eb4)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (c000000000aedb9c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (c000000000e1a53c)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffe0000cba08)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_link
```
```
In kernel/cred.c (ffffffe0000e1868)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffe000258048)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffe00028f4f8)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffe0002b0858)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffe000394dc2)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffe00039588e)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffe00039611a)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffe0003e1e50)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffe00064ecaa)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffe00083fd06)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810a8119)
Location: include/linux/cred.h:228
Inline: True
```
```
In kernel/cred.c (ffffffff810c823a)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812d7114)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff81315c43)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8133d28b)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffff814435c1)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81443f5d)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81444ce2)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff814973db)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817b5956)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff819d379b)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff81096ad9)
Location: include/linux/cred.h:228
Inline: True
```
```
In kernel/cred.c (ffffffff810b6a5a)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812c7d94)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff81306833)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8132df4b)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffff81434011)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814349ad)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81435732)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff81487dfb)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817a7386)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff8199055b)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810a7679)
Location: include/linux/cred.h:228
Inline: True
```
```
In kernel/cred.c (ffffffff810c778a)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812d4f24)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff81313a33)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8133ad5b)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffff8143f761)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8144001d)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81440d82)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8149347b)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817f23f6)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81a3e21b)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff810af7a9)
Location: include/linux/cred.h:228
Inline: True
```
```
In kernel/cred.c (ffffffff810cfc5a)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:override_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812e5d84)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff81325283)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8134df0b)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffff81456901)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8145729d)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81458072)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff814ab4f2)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff8180c636)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81a49cce)
Location: include/linux/cred.h:228
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
</details>
</li>
</ul>

## Differences
