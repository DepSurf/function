# Function: <code>misc_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81515990)
Location: drivers/char/misc.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/lightnvm/core.c:nvm_mod_init
  - drivers/block/loop.c:loop_init
  - drivers/net/tun.c:tun_init
  - drivers/input/misc/uinput.c:uinput_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
```
**Symbols:**

```
ffffffff81515990-ffffffff81515b07: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff815685f0)
Location: drivers/char/misc.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:nvm_mod_init
  - drivers/block/loop.c:loop_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/input/misc/uinput.c:uinput_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
```
**Symbols:**

```
ffffffff815685f0-ffffffff8156876f: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81594d50)
Location: drivers/char/misc.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
```
**Symbols:**

```
ffffffff81594d50-ffffffff81594ecf: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff815a8e20)
Location: drivers/char/misc.c:185
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
```
**Symbols:**

```
ffffffff815a8e20-ffffffff815a8f93: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff8160f720)
Location: drivers/char/misc.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
```
**Symbols:**

```
ffffffff8160f720-ffffffff8160f893: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81649560)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81649560-ffffffff816496cb: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81667860)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81667860-ffffffff816679cb: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff8169d520)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff8169d520-ffffffff8169d696: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff816c02c0)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816c02c0-ffffffff816c0436: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff817741d0)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:cpu_latency_qos_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff817741d0-ffffffff81774348: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff8178ef50)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - kernel/power/qos.c:cpu_latency_qos_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff8178ef50-ffffffff8178f0c8: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81771d40)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
  - kernel/power/qos.c:cpu_latency_qos_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81771d40-ffffffff81771eb6: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff817f7ae0)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
  - kernel/power/qos.c:cpu_latency_qos_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff817f7ae0-ffffffff817f7c56: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81935df0)
Location: drivers/char/misc.c:175
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_guest_init
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
  - kernel/power/qos.c:cpu_latency_qos_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81935df0-ffffffff81935f75: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81a95dd0)
Location: drivers/char/misc.c:197
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
  - kernel/power/qos.c:cpu_latency_qos_init
  - kernel/power/user.c:snapshot_device_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81a95dd0-ffffffff81a95f8f: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81ae15e0)
Location: drivers/char/misc.c:211
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
  - kernel/power/qos.c:cpu_latency_qos_init
  - kernel/power/user.c:snapshot_device_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81ae15e0-ffffffff81ae179f: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81b349d0)
Location: drivers/char/misc.c:211
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
  - kernel/power/qos.c:cpu_latency_qos_init
  - kernel/power/user.c:snapshot_device_init
  - fs/userfaultfd.c:userfaultfd_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/pci/vgaarb.c:vga_arb_device_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81b349d0-ffffffff81b34b8f: misc_register (STB_GLOBAL)
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
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffff8000108b2360)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_init
  - kernel/power/qos.c:pm_qos_power_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffff8000108b2360-ffff8000108b2560: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (c09acc44)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
c09acc44-c09acde0: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (c00000000094abf0)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_power_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/char/nvram.c:nvram_module_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
c00000000094abf0-c00000000094ae48: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffe00056451c)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - kernel/power/qos.c:pm_qos_power_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffe00056451c-ffffffe0005646b8: misc_register (STB_GLOBAL)
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
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff81685d10)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81685d10-ffffffff81685e86: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff816639b0)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816639b0-ffffffff81663b26: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff816b4100)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816b4100-ffffffff816b4276: misc_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int misc_register(struct miscdevice *misc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/misc.c (ffffffff816ce660)
Location: drivers/char/misc.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/power/qos.c:pm_qos_power_init
  - kernel/power/user.c:snapshot_device_init
  - fs/ecryptfs/miscdev.c:ecryptfs_init_ecryptfs_miscdev
  - fs/fuse/dev.c:fuse_dev_init
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_init
  - drivers/xen/xenbus/xenbus_dev_backend.c:xenbus_backend_init
  - drivers/xen/mcelog.c:xen_late_init_mcelog
  - drivers/char/hpet.c:hpet_init
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/agp/frontend.c:agp_frontend_initialize
  - drivers/lightnvm/core.c:_nvm_misc_init
  - drivers/block/loop.c:loop_init
  - drivers/dma-buf/udmabuf.c:udmabuf_dev_init
  - drivers/gpu/vga/vgaarb.c:vga_arb_device_init
  - drivers/net/tun.c:tun_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/misc/uinput.c:uinput_misc_init
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/md/dm-ioctl.c:dm_interface_init
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816ce660-ffffffff816ce7d6: misc_register (STB_GLOBAL)
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
