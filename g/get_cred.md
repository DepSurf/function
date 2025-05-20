# Function: <code>get_cred</code>

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
Location: include/linux/cred.h:250
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
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff81334013)
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81334776)
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81335400)
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8137d991)
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff81619d23)
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In net/unix/af_unix.c (ffffffff817be980)
Location: include/linux/cred.h:250
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
Location: include/linux/cred.h:250
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
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff81368f17)
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8136970a)
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8136a37e)
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff813b7127)
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff8167c78e)
Location: include/linux/cred.h:250
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff8182e774)
Location: include/linux/cred.h:250
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
Location: include/linux/cred.h:241
Inline: True
```
```
In kernel/cred.c (ffffffff810ab98f)
Location: include/linux/cred.h:241
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
Location: include/linux/cred.h:241
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff8137f727)
Location: include/linux/cred.h:241
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8137ff1a)
Location: include/linux/cred.h:241
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81380b8e)
Location: include/linux/cred.h:241
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff813ce427)
Location: include/linux/cred.h:241
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff816aa4b2)
Location: include/linux/cred.h:241
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff818601fb)
Location: include/linux/cred.h:241
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
Location: include/linux/cred.h:242
Inline: True
```
```
In kernel/cred.c (ffffffff810a8543)
Location: include/linux/cred.h:242
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
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff8139362c)
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81393d9a)
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813949e8)
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff813e261d)
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff816bf38f)
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81884924)
Location: include/linux/cred.h:242
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
Location: include/linux/cred.h:243
Inline: True
```
```
In kernel/cred.c (ffffffff810aece3)
Location: include/linux/cred.h:243
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
Location: include/linux/cred.h:243
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff813b8cb6)
Location: include/linux/cred.h:243
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813b93ea)
Location: include/linux/cred.h:243
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813ba18e)
Location: include/linux/cred.h:243
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8140930d)
Location: include/linux/cred.h:243
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff8172ad74)
Location: include/linux/cred.h:243
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81905b02)
Location: include/linux/cred.h:243
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
Location: include/linux/cred.h:242
Inline: True
```
```
In kernel/cred.c (ffffffff810b5b0a)
Location: include/linux/cred.h:242
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
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - fs/file_table.c:get_empty_filp
```
```
In security/keys/process_keys.c (ffffffff813e9a46)
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813ea160)
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813eae7b)
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8143a8f1)
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817699ac)
Location: include/linux/cred.h:242
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff8195d1b7)
Location: include/linux/cred.h:242
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
In kernel/ptrace.c (ffffffff810a2ada)
Location: include/linux/cred.h:247
Inline: True
```
```
In kernel/cred.c (ffffffff810bed15)
Location: include/linux/cred.h:247
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
In fs/file_table.c (ffffffff812b07cc)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In security/keys/process_keys.c (ffffffff81404469)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81404b90)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814058ad)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff81457718)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff8178e037)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81991592)
Location: include/linux/cred.h:247
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
In kernel/ptrace.c (ffffffff810a777a)
Location: include/linux/cred.h:247
Inline: True
```
```
In kernel/cred.c (ffffffff810c4da0)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812cd104)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff8130a694)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In security/keys/process_keys.c (ffffffff81431272)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81431c0a)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81432983)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff81484ecb)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817cc8cb)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff819fd46c)
Location: include/linux/cred.h:247
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
In kernel/ptrace.c (ffffffff810add9a)
Location: include/linux/cred.h:247
Inline: True
```
```
In kernel/cred.c (ffffffff810cdeb0)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812deb24)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff8131d654)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff81344c98)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffff8144afd2)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8144b96a)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8144c6f3)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8149edeb)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817fd567)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81a340fc)
Location: include/linux/cred.h:247
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
In kernel/ptrace.c (ffffffff810b587a)
Location: include/linux/cred.h:248
Inline: True
```
```
In kernel/cred.c (ffffffff810d7c47)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff8124c7fa)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff81315974)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff81357722)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8138150d)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_queue_async_work
```
```
In security/keys/process_keys.c (ffffffff8149cbc6)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8149d9e5)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8149e753)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff814f83b3)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff818ccd8f)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81b24453)
Location: include/linux/cred.h:248
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
In kernel/ptrace.c (ffffffff810b0a6a)
Location: include/linux/cred.h:248
Inline: True
```
```
In kernel/cred.c (ffffffff810d2a9b)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff81256c3a)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff81320ed4)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff8136412c)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8138bcdd)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - fs/io_uring.c:io_register_personality
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_grab_identity
```
```
In security/keys/process_keys.c (ffffffff814ba666)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814bb4c5)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814bc243)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff81515503)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff818d7f87)
Location: include/linux/cred.h:248
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81b32c73)
Location: include/linux/cred.h:248
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
In kernel/ptrace.c (ffffffff810b200a)
Location: include/linux/cred.h:249
Inline: True
```
```
In kernel/cred.c (ffffffff810d46bc)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff8125b0da)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff81326fd4)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff8136aba0)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8139ec31)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_prep_async_work
```
```
In security/keys/process_keys.c (ffffffff814c04e6)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff814c1385)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814c2110)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8151be84)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff818bae76)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81b2539e)
Location: include/linux/cred.h:249
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
In kernel/ptrace.c (ffffffff810c3d10)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/cred.c (ffffffff810e789c)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff81296eda)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff81374594)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff813b9860)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff813ee615)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_prep_async_work
```
```
In security/keys/process_keys.c (ffffffff81518f06)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81519df5)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8151ab00)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff81579f44)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff81951602)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81a7ce78)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81bea3fb)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cred *get_cred(const struct cred *cred);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810db4a5)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/cred.c (ffffffff81101b26)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff812ed54d)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff813f3585)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff8143f2c8)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In security/keys/process_keys.c (ffffffff815abb14)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff815acb5c)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff815ad9e9)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff81618020)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In io_uring/io_uring.c (ffffffff816d84b8)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_prep_async_work
Direct callers:
  - io_uring/io_uring.c:io_sq_offload_create
```
```
In drivers/usb/core/devio.c (ffffffff81aaa27f)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81bf2d35)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81d81daf)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
**Symbols:**

```
ffffffff816c4580-ffffffff816c459c: get_cred (STB_LOCAL)
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
In kernel/ptrace.c (ffffffff810fb335)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/cred.c (ffffffff81126918)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff8135791d)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff8147c335)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff814ce10a)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In security/keys/process_keys.c (ffffffff81655f94)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8165707c)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81658049)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/audit.c (ffffffff816c1ba7)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/domain.c (ffffffff816cb5ca)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
```
```
In io_uring/io_uring.c (ffffffff8178c3af)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_prep_async_work
```
```
In io_uring/sqpoll.c (ffffffff8179ada1)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In drivers/usb/core/devio.c (ffffffff81c315ff)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81da0261)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81f4f2ef)
Location: include/linux/cred.h:249
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
In kernel/ptrace.c (ffffffff811075f5)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/cred.c (ffffffff81133dc8)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff8138917f)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff814b0ec5)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/fs_context.c (ffffffff8150430a)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In security/keys/process_keys.c (ffffffff8168e7c4)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8168f915)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816908c7)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/audit.c (ffffffff816fa72a)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/domain.c (ffffffff817040d1)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
```
```
In io_uring/io_uring.c (ffffffff817cd5bd)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_prep_async_work
```
```
In io_uring/sqpoll.c (ffffffff817dbe50)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In drivers/usb/core/devio.c (ffffffff81c9888d)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81e0f263)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff81faebbb)
Location: include/linux/cred.h:249
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (ffffffff81110f45)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_traceme
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/cred.c (ffffffff8113eaba)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
```
```
In kernel/watch_queue.c (ffffffff813b2bcf)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - kernel/watch_queue.c:add_watch_to_object
```
```
In fs/file_table.c (ffffffff814e2685)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - fs/file_table.c:init_file
```
```
In fs/fs_context.c (ffffffff81538fca)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In security/keys/process_keys.c (ffffffff816cad14)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816cbea5)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff816cce83)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/audit.c (ffffffff8173733a)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/domain.c (ffffffff8174197e)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
```
```
In io_uring/io_uring.c (ffffffff8180e6cd)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_init_req
  - io_uring/io_uring.c:io_prep_async_work
```
```
In io_uring/sqpoll.c (ffffffff818201d0)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In io_uring/register.c (ffffffff8182bb89)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - io_uring/register.c:__io_uring_register
```
```
In drivers/usb/core/devio.c (ffffffff81d4d3cc)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/sock.c (ffffffff81ecbcb4)
Location: include/linux/cred.h:233
Inline: True
Inline callers:
  - net/core/sock.c:sk_getsockopt
```
```
In net/unix/af_unix.c (ffffffff8207c0d7)
Location: include/linux/cred.h:233
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff800010107e30)
Location: include/linux/cred.h:247
Inline: True
```
```
In kernel/cred.c (ffff80001012d11c)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffff800010385250)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffff8000103d5a84)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffff800010403018)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffff800010534d2c)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffff800010535704)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffff800010536674)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffff800010594cc8)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffff800010a2e9a8)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffff800010cf4094)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
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
In kernel/ptrace.c (c0361e78)
Location: include/linux/cred.h:247
Inline: True
```
```
In kernel/cred.c (c037d65c)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (c056e11c)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (c05af450)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (c05d64ac)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (c06ec3b4)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c06ed174)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c06edb4c)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (c0745c20)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (c0b04694)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (c0dfb380)
Location: include/linux/cred.h:247
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
In kernel/ptrace.c (c00000000014f1e0)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_link
```
```
In kernel/cred.c (c000000000176450)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (c00000000047b1ec)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (c0000000004d834c)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (c00000000050f980)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (c000000000683130)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c000000000684368)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c00000000068503c)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (c000000000709eac)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (c000000000aedb8c)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (c000000000e1a52c)
Location: include/linux/cred.h:247
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
In kernel/ptrace.c (ffffffe0000cba02)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_link
```
```
In kernel/cred.c (ffffffe0000e1860)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffe000258040)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffe00028f4f2)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffe0002b0850)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffe000394dc2)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffe000395886)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffe000396114)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffe0003e1e48)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffe00064eca4)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffe00083fd00)
Location: include/linux/cred.h:247
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
In kernel/ptrace.c (ffffffff810a810a)
Location: include/linux/cred.h:247
Inline: True
```
```
In kernel/cred.c (ffffffff810c8230)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812d7104)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff81315c34)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8133d278)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffff814435b2)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81443f4a)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81444cd3)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff814973cb)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817b5947)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff819d378c)
Location: include/linux/cred.h:247
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
In kernel/ptrace.c (ffffffff81096aca)
Location: include/linux/cred.h:247
Inline: True
```
```
In kernel/cred.c (ffffffff810b6a50)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812c7d84)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff81306824)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8132df38)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffff81434002)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8143499a)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81435723)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff81487deb)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817a7377)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff8199054c)
Location: include/linux/cred.h:247
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
In kernel/ptrace.c (ffffffff810a766a)
Location: include/linux/cred.h:247
Inline: True
```
```
In kernel/cred.c (ffffffff810c7780)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812d4f14)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff81313a24)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8133ad48)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffff8143f752)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8144000a)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81440d73)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff8149346b)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff817f23e7)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81a3e20c)
Location: include/linux/cred.h:247
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
In kernel/ptrace.c (ffffffff810af79a)
Location: include/linux/cred.h:247
Inline: True
```
```
In kernel/cred.c (ffffffff810cfc50)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
```
```
In fs/file_table.c (ffffffff812e5d74)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/file_table.c:__alloc_file
```
```
In fs/fs_context.c (ffffffff81325274)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
```
```
In fs/io_uring.c (ffffffff8134def8)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In security/keys/process_keys.c (ffffffff814568f2)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff8145728a)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81458063)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/apparmor/domain.c (ffffffff814ab4e3)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In drivers/usb/core/devio.c (ffffffff8180c627)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:async_completed
```
```
In net/unix/af_unix.c (ffffffff81a49cbf)
Location: include/linux/cred.h:247
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
