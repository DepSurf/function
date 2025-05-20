# Function: <code>compat_alloc_user_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81110090)
Location: kernel/compat.c:1161
Inline: False
Direct callers:
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/compat.c:compat_convert_timespec
  - kernel/compat.c:compat_SyS_timer_create
  - kernel/compat.c:compat_SyS_move_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - mm/mempolicy.c:compat_SyS_get_mempolicy
  - mm/mempolicy.c:compat_SyS_set_mempolicy
  - mm/mempolicy.c:compat_SyS_mbind
  - fs/splice.c:compat_SyS_vmsplice
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/compat.c:compat_SyS_io_getevents
  - fs/compat.c:compat_SyS_io_submit
  - fs/compat.c:compat_SyS_io_submit
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat_mq.c:compat_SyS_mq_open
  - ipc/compat_mq.c:compat_SyS_mq_notify
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/compat.c:compat_sock_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
```
**Symbols:**

```
ffffffff81110090-ffffffff81110113: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811178f0)
Location: kernel/compat.c:1161
Inline: False
Direct callers:
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_move_pages
  - kernel/compat.c:compat_SyS_timer_create
  - kernel/compat.c:compat_convert_timespec
  - mm/mempolicy.c:compat_SyS_mbind
  - mm/mempolicy.c:compat_SyS_set_mempolicy
  - mm/mempolicy.c:compat_SyS_get_mempolicy
  - fs/splice.c:compat_SyS_vmsplice
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/compat.c:compat_SyS_io_submit
  - fs/compat.c:compat_SyS_io_submit
  - fs/compat.c:compat_SyS_io_getevents
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_notify
  - ipc/compat_mq.c:compat_SyS_mq_open
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_ifr_data_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff811178f0-ffffffff81117973: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111f030)
Location: kernel/compat.c:1169
Inline: False
Direct callers:
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:compat_SyS_move_pages
  - kernel/compat.c:compat_SyS_timer_create
  - kernel/compat.c:compat_convert_timespec
  - mm/mempolicy.c:C_SYSC_mbind
  - mm/mempolicy.c:C_SYSC_set_mempolicy
  - mm/mempolicy.c:C_SYSC_get_mempolicy
  - fs/splice.c:compat_SyS_vmsplice
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/aio.c:compat_SyS_io_getevents
  - fs/aio.c:compat_SyS_io_submit
  - fs/aio.c:compat_SyS_io_submit
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_notify
  - ipc/compat_mq.c:compat_SyS_mq_open
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_ifr_data_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff8111f030-ffffffff8111f097: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120750)
Location: kernel/compat.c:609
Inline: False
Direct callers:
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:compat_SyS_move_pages
  - kernel/compat.c:compat_convert_timespec
  - mm/mempolicy.c:C_SYSC_mbind
  - mm/mempolicy.c:C_SYSC_set_mempolicy
  - mm/mempolicy.c:C_SYSC_get_mempolicy
  - fs/splice.c:compat_SyS_vmsplice
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/aio.c:compat_SyS_io_getevents
  - fs/aio.c:compat_SyS_io_submit
  - fs/aio.c:compat_SyS_io_submit
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff81120750-ffffffff811207b7: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112bef0)
Location: kernel/compat.c:569
Inline: False
Direct callers:
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:compat_SyS_move_pages
  - mm/mempolicy.c:C_SYSC_mbind
  - mm/mempolicy.c:C_SYSC_set_mempolicy
  - mm/mempolicy.c:C_SYSC_get_mempolicy
  - fs/splice.c:compat_SyS_vmsplice
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/aio.c:compat_SyS_io_submit
  - fs/aio.c:compat_SyS_io_submit
  - fs/compat_ioctl.c:compat_SyS_ioctl
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - fs/quota/compat.c:sys32_quotactl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff8112bef0-ffffffff8112bf5d: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113a6b0)
Location: kernel/compat.c:460
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff8113a6b0-ffffffff8113a71d: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81145f20)
Location: kernel/compat.c:429
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff81145f20-ffffffff81145f8d: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811512f0)
Location: kernel/compat.c:365
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff811512f0-ffffffff8115135a: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115cf40)
Location: kernel/compat.c:365
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff8115cf40-ffffffff8115cfaa: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116da70)
Location: kernel/compat.c:277
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - fs/quota/compat.c:__do_compat_sys_quotactl32
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk_compat
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:ethtool_ioctl
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff8116da70-ffffffff8116dada: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116a050)
Location: kernel/compat.c:277
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - net/socket.c:compat_ifreq_ioctl
  - net/socket.c:ethtool_ioctl
```
**Symbols:**

```
ffffffff8116a050-ffffffff8116a0be: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116ad30)
Location: kernel/compat.c:277
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:ethtool_ioctl
```
**Symbols:**

```
ffffffff8116ad30-ffffffff8116ad81: compat_alloc_user_space (STB_GLOBAL)
```
</details>
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
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cb7a8)
Location: kernel/compat.c:365
Inline: False
Direct callers:
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_mbind
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/migrate.c:__arm64_compat_sys_move_pages
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:__arm64_compat_sys_ioctl
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:ppp_sock_fprog_ioctl_trans
  - fs/compat_ioctl.c:sg_grt_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk_compat
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffff8000101cb7a8-ffff8000101cb858: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000236560)
Location: kernel/compat.c:365
Inline: False
Direct callers:
  - kernel/kexec.c:__se_compat_sys_kexec_load
  - mm/mempolicy.c:__se_compat_sys_migrate_pages
  - mm/mempolicy.c:__se_compat_sys_migrate_pages
  - mm/mempolicy.c:__se_compat_sys_migrate_pages
  - mm/mempolicy.c:__se_compat_sys_mbind
  - mm/mempolicy.c:__se_compat_sys_set_mempolicy
  - mm/mempolicy.c:__se_compat_sys_get_mempolicy
  - mm/migrate.c:__se_compat_sys_move_pages
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:__se_compat_sys_ioctl
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:mt_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - fs/compat_ioctl.c:sg_ioctl_trans
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkdev_driver_ioctl
  - block/compat_ioctl.c:compat_blkpg_ioctl
  - block/compat_ioctl.c:compat_cdrom_generic_command
  - drivers/video/fbdev/core/fbmem.c:fb_getput_cmap
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk_compat
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
c000000000236560-c0000000002365c8: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81155560)
Location: kernel/compat.c:365
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff81155560-ffffffff811555ca: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148880)
Location: kernel/compat.c:365
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff81148880-ffffffff811488ea: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81153330)
Location: kernel/compat.c:365
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff81153330-ffffffff8115339a: compat_alloc_user_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *compat_alloc_user_space(long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81160230)
Location: kernel/compat.c:365
Inline: False
Direct callers:
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/compat_ioctl.c:compat_ioctl_preallocate
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__x32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - fs/quota/compat.c:__ia32_compat_sys_quotactl32
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:ethtool_ioctl
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:compat_mc_setsockopt
  - net/compat.c:get_compat_bpf_fprog
```
**Symbols:**

```
ffffffff81160230-ffffffff8116029a: compat_alloc_user_space (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
