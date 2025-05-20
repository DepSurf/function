# Function: <code>unregister_chrdev_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812109b0)
Location: fs/char_dev.c:285
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/input/input.c:input_exit
  - drivers/rtc/rtc-dev.c:rtc_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff812109b0-ffffffff812109fd: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81237440)
Location: fs/char_dev.c:289
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/rtc-dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff81237440-ffffffff8123748d: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a0f0)
Location: fs/char_dev.c:289
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/rtc-dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff8124a0f0-ffffffff8124a13d: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812559f0)
Location: fs/char_dev.c:289
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/rtc-dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff812559f0-ffffffff81255a3d: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81277b80)
Location: fs/char_dev.c:314
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/rtc-dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff81277b80-ffffffff81277bcd: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129e540)
Location: fs/char_dev.c:314
Inline: False
Direct callers:
  - mm/hmm.c:hmm_init
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/rtc-dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff8129e540-ffffffff8129e58d: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3520)
Location: fs/char_dev.c:314
Inline: False
Direct callers:
  - mm/hmm.c:hmm_init
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff812b3520-ffffffff812b356d: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d0180)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff812d0180-ffffffff812d01ce: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e1d30)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff812e1d30-ffffffff812e1d7e: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81319000)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff81319000-ffffffff8131904e: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813244b0)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff813244b0-ffffffff813244fe: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132a580)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff8132a580-ffffffff8132a5cc: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81377c30)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff81377c30-ffffffff81377c7c: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f6f30)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff813f6f30-ffffffff813f6f88: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814801c0)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff814801c0-ffffffff81480218: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b4f20)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff814b4f20-ffffffff814b4f78: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e71e0)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff814e71e0-ffffffff814e7238: unregister_chrdev_region (STB_GLOBAL)
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
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff800010389388)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/mmc/core/block.c:mmc_blk_exit
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
ffff800010389388-ffff8000103893ec: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571734)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/mmc/core/block.c:mmc_blk_exit
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
c0571734-c057178c: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000480130)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
c000000000480130-c0000000004801e4: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025b5ba)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/mmc/core/block.c:mmc_blk_exit
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
ffffffe00025b5ba-ffffffe00025b630: unregister_chrdev_region (STB_GLOBAL)
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
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da310)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff812da310-ffffffff812da35e: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812caf90)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff812caf90-ffffffff812cafde: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d8120)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff812d8120-ffffffff812d816e: unregister_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unregister_chrdev_region(dev_t from, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e8fc0)
Location: fs/char_dev.c:311
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_unregister_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/sg.c:exit_sg
  - drivers/scsi/sg.c:init_sg
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/input.c:input_exit
  - drivers/rtc/dev.c:rtc_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_exit
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_exit
  - drivers/ptp/ptp_clock.c:ptp_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
```
**Symbols:**

```
ffffffff812e8fc0-ffffffff812e900e: unregister_chrdev_region (STB_GLOBAL)
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
