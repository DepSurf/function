# Function: <code>memdup_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811abd60)
Location: mm/util.c:128
Inline: False
Direct callers:
  - mm/util.c:strndup_user
  - fs/efivarfs/file.c:efivarfs_file_write
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_write
```
**Symbols:**

```
ffffffff811abd60-ffffffff811abdca: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4a40)
Location: mm/util.c:128
Inline: False
Direct callers:
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/efivarfs/file.c:efivarfs_file_write
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_write
```
**Symbols:**

```
ffffffff811c4a40-ffffffff811c4aad: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4b50)
Location: mm/util.c:128
Inline: False
Direct callers:
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/smack/smackfs.c:smk_write_revoke_subj
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_write
```
**Symbols:**

```
ffffffff811d4b50-ffffffff811d4bbd: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd970)
Location: mm/util.c:155
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/smack/smackfs.c:smk_write_revoke_subj
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff811dd970-ffffffff811dd9e7: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f33f0)
Location: mm/util.c:155
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/smack/smackfs.c:smk_write_revoke_subj
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff811f33f0-ffffffff811f3467: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214620)
Location: mm/util.c:156
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/smack/smackfs.c:smk_write_revoke_subj
  - block/bsg-lib.c:bsg_transport_fill_hdr
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff81214620-ffffffff81214697: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227500)
Location: mm/util.c:149
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/apparmor/apparmorfs.c:attr_write
  - block/bsg-lib.c:bsg_transport_fill_hdr
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_set_unimap
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff81227500-ffffffff81227577: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81237280)
Location: mm/util.c:161
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/apparmor/apparmorfs.c:attr_write
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff81237280-ffffffff81237305: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812454f0)
Location: mm/util.c:168
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/apparmor/apparmorfs.c:attr_write
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff812454f0-ffffffff81245580: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81273150)
Location: mm/util.c:168
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/util.c:strndup_user
  - fs/ioctl.c:ioctl_file_dedupe_range
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:update_filter
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_set_tunable
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff81273150-ffffffff812731e0: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d8b0)
Location: mm/util.c:169
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/util.c:strndup_user
  - fs/ioctl.c:ioctl_file_dedupe_range
  - fs/io_uring.c:__io_uring_register
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:update_filter
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ethtool/ioctl.c:set_phy_tunable
  - net/ethtool/ioctl.c:ethtool_set_tunable
```
**Symbols:**

```
ffffffff8127d8b0-ffffffff8127d940: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282a80)
Location: mm/util.c:169
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/io_uring.c:__io_uring_register
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:update_filter
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81282a80-ffffffff81282b10: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0a90)
Location: mm/util.c:169
Inline: False
Direct callers:
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/io_uring.c:__io_uring_register
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:update_filter
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff812c0a90-ffffffff812c0b20: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131cfa0)
Location: mm/util.c:170
Inline: False
Direct callers:
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/sed-opal.c:sed_ioctl
  - io_uring/io_uring.c:io_register_restrictions
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:update_filter
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff8131cfa0-ffffffff8131d04a: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813908b0)
Location: mm/util.c:170
Inline: False
Direct callers:
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/sed-opal.c:sed_ioctl
  - io_uring/io_uring.c:io_register_restrictions
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:update_filter
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff813908b0-ffffffff81390951: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c31b0)
Location: mm/util.c:193
Inline: False
Direct callers:
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/sed-opal.c:sed_ioctl
  - io_uring/io_uring.c:io_register_restrictions
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:update_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff813c31b0-ffffffff813c3251: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813edcd0)
Location: mm/util.c:193
Inline: False
Direct callers:
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_prepare_segments
  - kernel/watch_queue.c:watch_queue_set_filter
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/security.c:security_setselfattr
  - security/smack/smackfs.c:smk_write_revoke_subj
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/sed-opal.c:sed_ioctl
  - io_uring/register.c:io_register_restrictions
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
  - drivers/gpu/drm/drm_debugfs.c:edid_write
  - drivers/net/tun.c:update_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_setup_device_legacy
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff813edcd0-ffffffff813edd71: memdup_user (STB_GLOBAL)
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
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d8798)
Location: mm/util.c:168
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/apparmor/apparmorfs.c:attr_write
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffff8000102d8798-ffff8000102d8854: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff954)
Location: mm/util.c:168
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/apparmor/apparmorfs.c:attr_write
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_writeoob
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/compress_offload.c:snd_compr_set_params
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
c04ff954-c04ffa68: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c0000000003982b0)
Location: mm/util.c:168
Inline: False
Direct callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/apparmor/apparmorfs.c:attr_write
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/char/nvram.c:nvram_misc_write
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
c0000000003982b0-c0000000003983c4: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f2d1a)
Location: mm/util.c:168
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/apparmor/apparmorfs.c:attr_write
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffe0001f2d1a-ffffffe0001f2db8: memdup_user (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123db40)
Location: mm/util.c:168
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/apparmor/apparmorfs.c:attr_write
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff8123db40-ffffffff8123dbd0: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230b40)
Location: mm/util.c:168
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/apparmor/apparmorfs.c:attr_write
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff81230b40-ffffffff81230bd0: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b8e0)
Location: mm/util.c:168
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/apparmor/apparmorfs.c:attr_write
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff8123b8e0-ffffffff8123b970: memdup_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *memdup_user(const void *src, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124aff0)
Location: mm/util.c:168
Inline: False
Direct callers:
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_lookup_elem
  - mm/util.c:strndup_user
  - fs/ioctl.c:do_vfs_ioctl
  - fs/proc/base.c:proc_pid_attr_write
  - fs/pstore/platform.c:pstore_write_user_compat
  - fs/efivarfs/file.c:efivarfs_file_write
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/smack/smackfs.c:smk_write_revoke_subj
  - security/apparmor/apparmorfs.c:attr_write
  - block/sed-opal.c:sed_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/xfrm/xfrm_state.c:xfrm_user_policy
```
**Symbols:**

```
ffffffff8124aff0-ffffffff8124b080: memdup_user (STB_GLOBAL)
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
