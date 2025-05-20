# Function: <code>misc_deregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81515b10)
Location: drivers/char/misc.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_exit
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_exit
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/lightnvm/core.c:nvm_mod_exit
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/net/tun.c:tun_cleanup
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff81515b10-ffffffff81515bb8: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81568770)
Location: drivers/char/misc.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/lightnvm/core.c:nvm_mod_exit
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/net/tun.c:tun_cleanup
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff81568770-ffffffff8156881b: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81594ed0)
Location: drivers/char/misc.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/net/tun.c:tun_cleanup
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff81594ed0-ffffffff81594f7b: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff815a8fa0)
Location: drivers/char/misc.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff815a8fa0-ffffffff815a9038: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff8160f8a0)
Location: drivers/char/misc.c:251
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff8160f8a0-ffffffff8160f938: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff816496d0)
Location: drivers/char/misc.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816496d0-ffffffff81649765: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff816679d0)
Location: drivers/char/misc.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816679d0-ffffffff81667a65: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/misc.c (0)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff8169d733-ffffffff8169d746: misc_deregister.cold (STB_LOCAL)
ffffffff8169d6a0-ffffffff8169d733: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff816c0440)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816c0440-ffffffff816c04d6: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81774350)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81774350-ffffffff817743e6: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff8178f0d0)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff8178f0d0-ffffffff8178f166: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81771ec0)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81771ec0-ffffffff81771f56: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff817f7c60)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff817f7c60-ffffffff817f7cf6: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81935f80)
Location: drivers/char/misc.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81935f80-ffffffff8193602e: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81a95fa0)
Location: drivers/char/misc.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modexit
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81a95fa0-ffffffff81a96064: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81ae17b0)
Location: drivers/char/misc.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modexit
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81ae17b0-ffffffff81ae1874: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81b34ba0)
Location: drivers/char/misc.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modexit
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81b34ba0-ffffffff81b34c64: misc_deregister (STB_GLOBAL)
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
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffff8000108b2560)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffff8000108b2560-ffff8000108b2644: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (c09acde0)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
c09acde0-c09ace94: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (c00000000094ae50)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/char/nvram.c:nvram_module_exit
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
c00000000094ae50-c00000000094af80: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffe0005646b8)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffe0005646b8-ffffffe00056476c: misc_deregister (STB_GLOBAL)
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
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81685e90)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81685e90-ffffffff81685f26: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81663b30)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81663b30-ffffffff81663bc6: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff816b4280)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816b4280-ffffffff816b4316: misc_deregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void misc_deregister(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff816ce7e0)
Location: drivers/char/misc.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_dev_exit
  - fs/ecryptfs/miscdev.c:ecryptfs_destroy_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_cleanup
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:unregister_miscdev
  - drivers/char/agp/frontend.c:agp_frontend_cleanup
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_exit
  - drivers/net/tun.c:tun_cleanup
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_psaux_unregister
  - drivers/input/misc/uinput.c:uinput_misc_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816ce7e0-ffffffff816ce876: misc_deregister (STB_GLOBAL)
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
