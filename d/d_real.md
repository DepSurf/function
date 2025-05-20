# Function: <code>d_real</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812310bd)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - fs/open.c:vfs_open
```
```
In fs/namei.c (ffffffff812413ed)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
```
```
In fs/inode.c (ffffffff81250179)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/ext4/file.c (ffffffff812bef6b)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
```
```
In net/unix/af_unix.c (ffffffff8182d9a2)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:unix_find_other
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
In fs/open.c (ffffffff8124366d)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - fs/open.c:vfs_open
  - fs/open.c:vfs_truncate
```
```
In fs/inode.c (ffffffff81263249)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
  - fs/inode.c:__atime_needs_update
```
```
In fs/locks.c (ffffffff812a0423)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/file.c (ffffffff812d458b)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
```
```
In fs/fuse/file.c (ffffffff8135f621)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff813eb0d3)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff813ef3b8)
Location: include/linux/dcache.h:570
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
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
In fs/open.c (ffffffff8124edbf)
Location: include/linux/dcache.h:576
Inline: True
Inline callers:
  - fs/open.c:vfs_open
  - fs/open.c:vfs_truncate
```
```
In fs/inode.c (ffffffff81270a59)
Location: include/linux/dcache.h:576
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
  - fs/inode.c:__atime_needs_update
```
```
In fs/locks.c (ffffffff812af253)
Location: include/linux/dcache.h:576
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/file.c (ffffffff812f0f10)
Location: include/linux/dcache.h:576
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
```
```
In fs/fuse/file.c (ffffffff813741c1)
Location: include/linux/dcache.h:576
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff813f73c7)
Location: include/linux/dcache.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff813fb988)
Location: include/linux/dcache.h:576
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
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
In fs/open.c (ffffffff81270d3d)
Location: include/linux/dcache.h:581
Inline: True
Inline callers:
  - fs/open.c:vfs_open
  - fs/open.c:vfs_truncate
```
```
In fs/inode.c (ffffffff81293389)
Location: include/linux/dcache.h:581
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
  - fs/inode.c:__atime_needs_update
```
```
In fs/namespace.c (ffffffff812993e4)
Location: include/linux/dcache.h:581
Inline: True
```
```
In fs/crypto/hooks.c (ffffffff812d0a9f)
Location: include/linux/dcache.h:581
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/locks.c (ffffffff812d2c23)
Location: include/linux/dcache.h:581
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/fuse/file.c (ffffffff81398f41)
Location: include/linux/dcache.h:581
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff8141f4dc)
Location: include/linux/dcache.h:581
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81423e58)
Location: include/linux/dcache.h:581
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81775141)
Location: include/linux/dcache.h:581
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff811ae71c)
Location: include/linux/dcache.h:582
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In fs/open.c (ffffffff812969f8)
Location: include/linux/dcache.h:582
Inline: True
Inline callers:
  - fs/open.c:vfs_open
  - fs/open.c:vfs_truncate
```
```
In fs/inode.c (ffffffff812b8f89)
Location: include/linux/dcache.h:582
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
  - fs/inode.c:__atime_needs_update
```
```
In fs/namespace.c (ffffffff812bf264)
Location: include/linux/dcache.h:582
Inline: True
```
```
In fs/crypto/hooks.c (ffffffff812fb6af)
Location: include/linux/dcache.h:582
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/locks.c (ffffffff812fcc2d)
Location: include/linux/dcache.h:582
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/fuse/file.c (ffffffff813c7ce1)
Location: include/linux/dcache.h:582
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff814514b0)
Location: include/linux/dcache.h:582
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81456575)
Location: include/linux/dcache.h:582
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b576d)
Location: include/linux/dcache.h:582
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff811bcd90)
Location: include/linux/dcache.h:574
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In fs/inode.c (ffffffff812ce0c9)
Location: include/linux/dcache.h:574
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff81310abf)
Location: include/linux/dcache.h:574
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff813e0f20)
Location: include/linux/dcache.h:574
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff8146e5fa)
Location: include/linux/dcache.h:574
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814739f5)
Location: include/linux/dcache.h:574
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dbc7d)
Location: include/linux/dcache.h:574
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff811cc493)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In fs/inode.c (ffffffff812eaf39)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff81337fef)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff8140c960)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff8149bec8)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814a16f5)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181c6cc)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff811d89f0)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In fs/inode.c (ffffffff812fca79)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8134c06f)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff81426470)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff814b5fa1)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814bc185)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184da8c)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff811f57c5)
Location: include/linux/dcache.h:579
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_has_same_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_has_same_uprobe
```
```
In fs/inode.c (ffffffff81335639)
Location: include/linux/dcache.h:579
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/io_uring.c (ffffffff8137f9df)
Location: include/linux/dcache.h:579
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/crypto/hooks.c (ffffffff813917c0)
Location: include/linux/dcache.h:579
Inline: True
```
```
In fs/fuse/file.c (ffffffff81475a4e)
Location: include/linux/dcache.h:579
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff8151588a)
Location: include/linux/dcache.h:579
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8151c605)
Location: include/linux/dcache.h:579
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81921c5c)
Location: include/linux/dcache.h:579
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff811f4155)
Location: include/linux/dcache.h:580
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_has_same_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_has_same_uprobe
```
```
In fs/inode.c (ffffffff81340fb9)
Location: include/linux/dcache.h:580
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/io_uring.c (ffffffff8138def2)
Location: include/linux/dcache.h:580
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/crypto/hooks.c (ffffffff813a2d70)
Location: include/linux/dcache.h:580
Inline: True
```
```
In fs/fuse/file.c (ffffffff814914fe)
Location: include/linux/dcache.h:580
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In security/integrity/ima/ima_main.c (ffffffff815327de)
Location: include/linux/dcache.h:580
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81539475)
Location: include/linux/dcache.h:580
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819292ac)
Location: include/linux/dcache.h:580
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff811f4d00)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
```
In fs/inode.c (ffffffff813473ae)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/io_uring.c (ffffffff81397eb3)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/crypto/hooks.c (ffffffff813a9fb0)
Location: include/linux/dcache.h:583
Inline: True
```
```
In fs/fuse/file.c (ffffffff8149665e)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In security/integrity/ima/ima_main.c (ffffffff8153aba0)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81541b75)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190c92c)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff81226f10)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
```
In fs/inode.c (ffffffff81394e0e)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/io_uring.c (ffffffff813e3a14)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/crypto/hooks.c (ffffffff813f9800)
Location: include/linux/dcache.h:583
Inline: True
```
```
In fs/fuse/file.c (ffffffff814edefe)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In security/integrity/ima/ima_main.c (ffffffff8159955b)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff815a0543)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
```
```
In security/integrity/ima/ima_appraise.c (ffffffff815a1935)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ad2fc)
Location: include/linux/dcache.h:583
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff81266a4d)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
```
In fs/inode.c (ffffffff814171be)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8146c6bf)
Location: include/linux/dcache.h:573
Inline: True
```
```
In fs/fuse/file.c (ffffffff8157d4d0)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In security/integrity/ima/ima_main.c (ffffffff8163e0fe)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81646276)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81647cf5)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In io_uring/io_uring.c (ffffffff81e90117)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_show_fdinfo
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0b93c)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff812b8ca2)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
```
In fs/inode.c (ffffffff814a2b03)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - fs/inode.c:__file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff814fda8f)
Location: include/linux/dcache.h:573
Inline: True
```
```
In fs/fuse/file.c (ffffffff81622ac0)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff816f5d28)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff816fe836)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81700535)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In io_uring/fdinfo.c (ffffffff8179b547)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9b8cc)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff812dc302)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
```
In fs/inode.c (ffffffff814d7c49)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - fs/inode.c:__file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff81535072)
Location: include/linux/dcache.h:573
Inline: True
```
```
In fs/fuse/file.c (ffffffff8165af03)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff81730092)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81738899)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8173a5c8)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In io_uring/fdinfo.c (ffffffff817dc66c)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d02cbf)
Location: include/linux/dcache.h:573
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/bpf_trace.c (ffffffff812ea55a)
Location: include/linux/dcache.h:557
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_uprobe_unregister
  - kernel/trace/bpf_trace.c:bpf_uprobe_unregister
  - kernel/trace/bpf_trace.c:bpf_get_file_xattr
  - kernel/trace/bpf_trace.c:bpf_get_file_xattr
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fa3e2)
Location: include/linux/dcache.h:557
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
```
In fs/inode.c (ffffffff8150a429)
Location: include/linux/dcache.h:557
Inline: True
Inline callers:
  - fs/inode.c:__file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8156a032)
Location: include/linux/dcache.h:557
Inline: True
```
```
In fs/fuse/file.c (ffffffff81694bd3)
Location: include/linux/dcache.h:557
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff81770978)
Location: include/linux/dcache.h:557
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_api.c (ffffffff8177432e)
Location: include/linux/dcache.h:557
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff817793b9)
Location: include/linux/dcache.h:557
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8177b108)
Location: include/linux/dcache.h:557
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In io_uring/fdinfo.c (ffffffff81820bed)
Location: include/linux/dcache.h:557
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db881f)
Location: include/linux/dcache.h:557
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffff800010259a70)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In fs/inode.c (ffff8000103ac4a0)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffff80001040ca64)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffff80001050a000)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffff8000105ae2f8)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffff8000105b4a44)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8e624)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (c048ba14)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In fs/inode.c (c058d958)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (c05d9be8)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (c06c71b0)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (c075da58)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (c0763df4)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (c0b60a34)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (c0000000002fd284)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In fs/inode.c (c0000000004a81c4)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (c000000000519ec4)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (c000000000650200)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (c00000000072d01c)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (c0000000007376f0)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b69af4)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In fs/inode.c (ffffffe000271a9a)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffe0002b6356)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffe000375744)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffe0003f6562)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffe0003fbbea)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a1b90)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff811d1010)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In fs/inode.c (ffffffff812f5059)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8134464f)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff8141ea50)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff814ae581)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814b4765)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8180385c)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff811c3de0)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In fs/inode.c (ffffffff812e5c79)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8133532f)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff8140f4d0)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff8149efa1)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814a5185)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cafdc)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff811cede0)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In fs/inode.c (ffffffff812f2e69)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8134211f)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff8141abf0)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff814aa621)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814b07f5)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184290c)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
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
In kernel/trace/trace_uprobe.c (ffffffff811dd070)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In fs/inode.c (ffffffff81304799)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8135541f)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff81431d80)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff814c3061)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814c9275)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185ce6c)
Location: include/linux/dcache.h:572
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
```
</details>
</li>
</ul>

## Differences
