# Function: <code>file_dentry</code>

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
In fs/inode.c (ffffffff81250162)
Location: include/linux/fs.h:1247
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/ext4/file.c (ffffffff812bef66)
Location: include/linux/fs.h:1247
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
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
In fs/inode.c (ffffffff81263232)
Location: include/linux/fs.h:1212
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/ext4/file.c (ffffffff812d4586)
Location: include/linux/fs.h:1212
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
```
```
In fs/fuse/file.c (ffffffff8135f60e)
Location: include/linux/fs.h:1212
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff813eb0cf)
Location: include/linux/fs.h:1212
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff813ef3ae)
Location: include/linux/fs.h:1212
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
In fs/inode.c (ffffffff81270a42)
Location: include/linux/fs.h:1234
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/ext4/file.c (ffffffff812f0f0b)
Location: include/linux/fs.h:1234
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
```
```
In fs/fuse/file.c (ffffffff813741ae)
Location: include/linux/fs.h:1234
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff813f73c3)
Location: include/linux/fs.h:1234
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff813fb97e)
Location: include/linux/fs.h:1234
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
In fs/inode.c (ffffffff81293372)
Location: include/linux/fs.h:1237
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff812d0a9b)
Location: include/linux/fs.h:1237
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff81398f2e)
Location: include/linux/fs.h:1237
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff8141f4d8)
Location: include/linux/fs.h:1237
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81423e4e)
Location: include/linux/fs.h:1237
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81775139)
Location: include/linux/fs.h:1237
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
In fs/inode.c (ffffffff812b8f89)
Location: include/linux/fs.h:1245
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff812fb6aa)
Location: include/linux/fs.h:1245
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff813c7ce1)
Location: include/linux/fs.h:1245
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff814514ac)
Location: include/linux/fs.h:1245
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81456565)
Location: include/linux/fs.h:1245
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b5755)
Location: include/linux/fs.h:1245
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
In fs/inode.c (ffffffff812ce0c9)
Location: include/linux/fs.h:1288
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff81310aba)
Location: include/linux/fs.h:1288
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff813e0f20)
Location: include/linux/fs.h:1288
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff8146e5f6)
Location: include/linux/fs.h:1288
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814739e5)
Location: include/linux/fs.h:1288
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dbc65)
Location: include/linux/fs.h:1288
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
In fs/inode.c (ffffffff812eaf39)
Location: include/linux/fs.h:1303
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff81337fea)
Location: include/linux/fs.h:1303
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff8140c960)
Location: include/linux/fs.h:1303
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff8149bec4)
Location: include/linux/fs.h:1303
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814a16e5)
Location: include/linux/fs.h:1303
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181c6b5)
Location: include/linux/fs.h:1303
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
In fs/inode.c (ffffffff812fca79)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8134c06b)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff81426470)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff814b5f9d)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814bc175)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184da75)
Location: include/linux/fs.h:1322
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
In fs/inode.c (ffffffff81335639)
Location: include/linux/fs.h:1342
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/io_uring.c (ffffffff8137f9db)
Location: include/linux/fs.h:1342
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/crypto/hooks.c (ffffffff813917c0)
Location: include/linux/fs.h:1342
Inline: True
```
```
In fs/fuse/file.c (ffffffff81475a4e)
Location: include/linux/fs.h:1342
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff81515886)
Location: include/linux/fs.h:1342
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8151c5f5)
Location: include/linux/fs.h:1342
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81921c45)
Location: include/linux/fs.h:1342
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
In fs/inode.c (ffffffff81340fb9)
Location: include/linux/fs.h:1302
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/io_uring.c (ffffffff8138deee)
Location: include/linux/fs.h:1302
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/crypto/hooks.c (ffffffff813a2d70)
Location: include/linux/fs.h:1302
Inline: True
```
```
In fs/fuse/file.c (ffffffff814914fe)
Location: include/linux/fs.h:1302
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In security/integrity/ima/ima_main.c (ffffffff815327da)
Location: include/linux/fs.h:1302
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81539465)
Location: include/linux/fs.h:1302
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81929295)
Location: include/linux/fs.h:1302
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
In fs/inode.c (ffffffff813473ae)
Location: include/linux/fs.h:1307
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/io_uring.c (ffffffff81397eaf)
Location: include/linux/fs.h:1307
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/crypto/hooks.c (ffffffff813a9fb0)
Location: include/linux/fs.h:1307
Inline: True
```
```
In fs/fuse/file.c (ffffffff8149665e)
Location: include/linux/fs.h:1307
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In security/integrity/ima/ima_main.c (ffffffff8153ab9c)
Location: include/linux/fs.h:1307
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81541b65)
Location: include/linux/fs.h:1307
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190c915)
Location: include/linux/fs.h:1307
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
In fs/inode.c (ffffffff81394e0e)
Location: include/linux/fs.h:1353
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/io_uring.c (ffffffff813e3a10)
Location: include/linux/fs.h:1353
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/crypto/hooks.c (ffffffff813f9800)
Location: include/linux/fs.h:1353
Inline: True
```
```
In fs/fuse/file.c (ffffffff814edefe)
Location: include/linux/fs.h:1353
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In security/integrity/ima/ima_main.c (ffffffff81599557)
Location: include/linux/fs.h:1353
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff815a0543)
Location: include/linux/fs.h:1353
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
```
```
In security/integrity/ima/ima_appraise.c (ffffffff815a1925)
Location: include/linux/fs.h:1353
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ad2e5)
Location: include/linux/fs.h:1353
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
In fs/inode.c (ffffffff814171be)
Location: include/linux/fs.h:1320
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8146c6bf)
Location: include/linux/fs.h:1320
Inline: True
```
```
In fs/fuse/file.c (ffffffff8157d4d0)
Location: include/linux/fs.h:1320
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
  - fs/fuse/file.c:fuse_cache_write_iter
```
```
In security/integrity/ima/ima_main.c (ffffffff8163e0fa)
Location: include/linux/fs.h:1320
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81646276)
Location: include/linux/fs.h:1320
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81647ce5)
Location: include/linux/fs.h:1320
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In io_uring/io_uring.c (ffffffff81e90113)
Location: include/linux/fs.h:1320
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_show_fdinfo
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0b925)
Location: include/linux/fs.h:1320
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
In fs/inode.c (ffffffff814a2b03)
Location: include/linux/fs.h:1358
Inline: True
Inline callers:
  - fs/inode.c:__file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff814fda8f)
Location: include/linux/fs.h:1358
Inline: True
```
```
In fs/fuse/file.c (ffffffff81622ac0)
Location: include/linux/fs.h:1358
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff816f5d24)
Location: include/linux/fs.h:1358
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff816fe836)
Location: include/linux/fs.h:1358
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
```
```
In security/integrity/ima/ima_appraise.c (ffffffff81700525)
Location: include/linux/fs.h:1358
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In io_uring/fdinfo.c (ffffffff8179b543)
Location: include/linux/fs.h:1358
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9b8b5)
Location: include/linux/fs.h:1358
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
In fs/inode.c (ffffffff814d7c49)
Location: include/linux/fs.h:1045
Inline: True
Inline callers:
  - fs/inode.c:__file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff81535072)
Location: include/linux/fs.h:1045
Inline: True
```
```
In fs/fuse/file.c (ffffffff8165af03)
Location: include/linux/fs.h:1045
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff8173008b)
Location: include/linux/fs.h:1045
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81738899)
Location: include/linux/fs.h:1045
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8173a5b5)
Location: include/linux/fs.h:1045
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In io_uring/fdinfo.c (ffffffff817dc665)
Location: include/linux/fs.h:1045
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d02ca5)
Location: include/linux/fs.h:1045
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
In kernel/trace/bpf_trace.c (ffffffff812e94c3)
Location: include/linux/fs.h:1083
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_get_file_xattr
```
```
In fs/inode.c (ffffffff8150a429)
Location: include/linux/fs.h:1083
Inline: True
Inline callers:
  - fs/inode.c:__file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8156a032)
Location: include/linux/fs.h:1083
Inline: True
```
```
In fs/fuse/file.c (ffffffff81694bd3)
Location: include/linux/fs.h:1083
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff81770971)
Location: include/linux/fs.h:1083
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_api.c (ffffffff8177432e)
Location: include/linux/fs.h:1083
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff817793b9)
Location: include/linux/fs.h:1083
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventinodexattrs_init_common
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8177b0f5)
Location: include/linux/fs.h:1083
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In io_uring/fdinfo.c (ffffffff81820be6)
Location: include/linux/fs.h:1083
Inline: True
Inline callers:
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db8805)
Location: include/linux/fs.h:1083
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
In fs/inode.c (ffff8000103ac4a0)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffff80001040ca60)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffff80001050a000)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffff8000105ae2f4)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffff8000105b4a40)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8e620)
Location: include/linux/fs.h:1322
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
In fs/inode.c (c058d958)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (c05d9be4)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (c06c71b0)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (c075da54)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (c0763df0)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (c0b60a30)
Location: include/linux/fs.h:1322
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
In fs/inode.c (c0000000004a81bc)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (c000000000519ebc)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (c000000000650200)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (c00000000072d018)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (c0000000007376e0)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b69ae4)
Location: include/linux/fs.h:1322
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
In fs/inode.c (ffffffe000271a92)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffe0002b6352)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffe000375732)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffe0003f6560)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffe0003fbbe6)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a1b8c)
Location: include/linux/fs.h:1322
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
In fs/inode.c (ffffffff812f5059)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8134464b)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff8141ea50)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff814ae57d)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814b4755)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81803845)
Location: include/linux/fs.h:1322
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
In fs/inode.c (ffffffff812e5c79)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8133532b)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff8140f4d0)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff8149ef9d)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814a5175)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cafc5)
Location: include/linux/fs.h:1322
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
In fs/inode.c (ffffffff812f2e69)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8134211b)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff8141abf0)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff814aa61d)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814b07e5)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff818428f5)
Location: include/linux/fs.h:1322
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
In fs/inode.c (ffffffff81304799)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/inode.c:file_remove_privs
```
```
In fs/crypto/hooks.c (ffffffff8135541b)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_file_open
```
```
In fs/fuse/file.c (ffffffff81431d80)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_truncate
```
```
In security/integrity/ima/ima_main.c (ffffffff814c305d)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
```
In security/integrity/ima/ima_appraise.c (ffffffff814c9265)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_update_xattr
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185ce55)
Location: include/linux/fs.h:1322
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
```
</details>
</li>
</ul>

## Differences
