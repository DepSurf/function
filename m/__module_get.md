# Function: <code>__module_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81106a60)
Location: kernel/module.c:1066
Inline: False
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:visual_init
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/base/firmware_class.c:request_firmware
  - drivers/base/firmware_class.c:request_firmware_direct
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - net/socket.c:SYSC_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff81106a60-ffffffff81106ad1: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110e3a0)
Location: kernel/module.c:1071
Inline: False
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_class.c:request_firmware_into_buf
  - drivers/base/firmware_class.c:request_firmware_direct
  - drivers/base/firmware_class.c:request_firmware
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - net/socket.c:SYSC_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff8110e3a0-ffffffff8110e40a: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115d80)
Location: kernel/module.c:1074
Inline: False
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_class.c:request_firmware_into_buf
  - drivers/base/firmware_class.c:request_firmware_direct
  - drivers/base/firmware_class.c:request_firmware
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - net/socket.c:SYSC_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff81115d80-ffffffff81115dea: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81116c30)
Location: kernel/module.c:1096
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_class.c:request_firmware_into_buf
  - drivers/base/firmware_class.c:request_firmware_direct
  - drivers/base/firmware_class.c:request_firmware
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - net/socket.c:kernel_accept
  - net/socket.c:SYSC_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff81116c30-ffffffff81116ca3: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81122230)
Location: kernel/module.c:1104
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_class.c:request_firmware_into_buf
  - drivers/base/firmware_class.c:request_firmware_direct
  - drivers/base/firmware_class.c:request_firmware
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - net/socket.c:kernel_accept
  - net/socket.c:SYSC_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff81122230-ffffffff811222a6: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112fcb0)
Location: kernel/module.c:1103
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff8112fcb0-ffffffff8112fd22: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113b5f0)
Location: kernel/module.c:1104
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:lo_ioctl
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff8113b5f0-ffffffff8113b662: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81146c30)
Location: kernel/module.c:1100
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff81146c30-ffffffff81146ca5: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81152810)
Location: kernel/module.c:1114
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff81152810-ffffffff81152885: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811640b0)
Location: kernel/module.c:1117
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:cache_firmware
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4_file
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff811640b0-ffffffff81164125: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115f8c0)
Location: kernel/module.c:1150
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:cache_firmware
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4_file
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff8115f8c0-ffffffff8115f911: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81160d90)
Location: kernel/module.c:1058
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - lib/once.c:__do_once_done
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4_file
  - net/sched/act_api.c:tcf_idr_create
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff81160d90-ffffffff81160dde: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81185f60)
Location: kernel/module.c:1058
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - lib/once.c:__do_once_done
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/socket.c:kernel_accept
  - net/socket.c:do_accept
  - net/sched/act_api.c:tcf_idr_create
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff81185f60-ffffffff81185fab: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118c2b0)
Location: kernel/module/main.c:812
Inline: True
Direct callers:
  - fs/filesystems.c:get_filesystem
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - lib/once.c:__do_once_done
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/socket.c:kernel_accept
  - net/socket.c:do_accept
  - net/sched/act_api.c:tcf_idr_create
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff8118c2b0-ffffffff8118c34e: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811c87c0)
Location: kernel/module/main.c:815
Inline: True
Direct callers:
  - fs/filesystems.c:get_filesystem
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/elevator.c:elevator_alloc
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - lib/once.c:once_disable_jump
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/socket.c:kernel_accept
  - net/socket.c:do_accept
  - net/sched/act_api.c:tcf_idr_create
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff811c87c0-ffffffff811c885e: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811db590)
Location: kernel/module/main.c:820
Inline: True
Direct callers:
  - fs/filesystems.c:get_filesystem
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/elevator.c:elevator_alloc
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - lib/once.c:once_disable_jump
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/socket.c:kernel_accept
  - net/socket.c:do_accept
  - net/sched/act_api.c:tcf_idr_create
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff811db590-ffffffff811db617: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f13e0)
Location: kernel/module/main.c:820
Inline: True
Direct callers:
  - fs/filesystems.c:get_filesystem
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_test_lock
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/elevator.c:elevator_alloc
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - lib/once.c:once_disable_jump
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_platform
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - net/socket.c:kernel_accept
  - net/socket.c:do_accept
  - net/sched/act_api.c:tcf_idr_create
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff811f13e0-ffffffff811f1467: __module_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c21e8)
Location: kernel/module.c:1114
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffff8000101c21e8-ffff8000101c22ac: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0408f3c)
Location: kernel/module.c:1114
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sg.c:sg_open
  - drivers/mtd/mtdcore.c:register_mtd_user
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/mtd/mtd_blkdevs.c:blktrans_open
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
c0408f3c-c0408ffc: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000227f40)
Location: kernel/module.c:1114
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
c000000000227f40-c00000000022801c: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000143664)
Location: kernel/module.c:1114
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sg.c:sg_open
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffe000143664-ffffffe0001436f2: __module_get (STB_GLOBAL)
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
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114ae30)
Location: kernel/module.c:1114
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff8114ae30-ffffffff8114aea5: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113e0e0)
Location: kernel/module.c:1114
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff8113e0e0-ffffffff8113e155: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81148ce0)
Location: kernel/module.c:1114
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff81148ce0-ffffffff81148d55: __module_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __module_get(struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81155ad0)
Location: kernel/module.c:1114
Inline: True
Direct callers:
  - fs/exec.c:set_binfmt
  - fs/filesystems.c:get_filesystem
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/dma/dmaengine.c:dma_chan_get
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:visual_init
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/base/firmware_loader/main.c:request_firmware_direct
  - drivers/base/firmware_loader/main.c:firmware_request_nowarn
  - drivers/base/firmware_loader/main.c:request_firmware
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sg.c:sg_open
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/input/serio/serio.c:__serio_register_port
  - drivers/input/input.c:input_allocate_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - net/socket.c:kernel_accept
  - net/socket.c:__sys_accept4
  - net/netlink/af_netlink.c:netlink_add_tap
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
```
**Symbols:**

```
ffffffff81155ad0-ffffffff81155b70: __module_get (STB_GLOBAL)
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
