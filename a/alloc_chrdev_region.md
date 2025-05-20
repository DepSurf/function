# Function: <code>alloc_chrdev_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210e20)
Location: fs/char_dev.c:210
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/rtc/rtc-dev.c:rtc_dev_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff81210e20-ffffffff81210e4c: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81237940)
Location: fs/char_dev.c:214
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/rtc/rtc-dev.c:rtc_dev_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff81237940-ffffffff8123796c: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a5f0)
Location: fs/char_dev.c:214
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/rtc/rtc-dev.c:rtc_dev_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff8124a5f0-ffffffff8124a61c: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812561a0)
Location: fs/char_dev.c:214
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/rtc/rtc-dev.c:rtc_dev_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff812561a0-ffffffff812561cc: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812783b0)
Location: fs/char_dev.c:239
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/rtc/rtc-dev.c:rtc_dev_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff812783b0-ffffffff812783dc: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129eb30)
Location: fs/char_dev.c:239
Inline: False
Direct callers:
  - mm/hmm.c:hmm_init
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_fs_init
  - drivers/rtc/rtc-dev.c:rtc_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff8129eb30-ffffffff8129eb5c: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3840)
Location: fs/char_dev.c:239
Inline: False
Direct callers:
  - mm/hmm.c:hmm_init
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_fs_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff812b3840-ffffffff812b386c: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d0540)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff812d0540-ffffffff812d056c: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e20e0)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff812e20e0-ffffffff812e210c: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813194d0)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff813194d0-ffffffff813194ff: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81324bb0)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev
```
**Symbols:**

```
ffffffff81324bb0-ffffffff81324bdf: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132acd0)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev
```
**Symbols:**

```
ffffffff8132acd0-ffffffff8132acff: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813783e0)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev
```
**Symbols:**

```
ffffffff813783e0-ffffffff8137840f: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f7730)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev
```
**Symbols:**

```
ffffffff813f7730-ffffffff813f776b: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81480a90)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev
```
**Symbols:**

```
ffffffff81480a90-ffffffff81480acb: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b56b0)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev
```
**Symbols:**

```
ffffffff814b56b0-ffffffff814b56eb: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e79c0)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/remoteproc/remoteproc_cdev.c:rproc_init_cdev
```
**Symbols:**

```
ffffffff814e79c0-ffffffff814e79fb: alloc_chrdev_region (STB_GLOBAL)
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
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff800010389770)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
ffff800010389770-ffff8000103897d8: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571b0c)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
c0571b0c-c0571b4c: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000481080)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
c000000000481080-c000000000481108: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025b950)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/block.c:mmc_blk_init
```
**Symbols:**

```
ffffffe00025b950-ffffffe00025b9ba: alloc_chrdev_region (STB_GLOBAL)
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
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da6c0)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff812da6c0-ffffffff812da6ec: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb340)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff812cb340-ffffffff812cb36c: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d84d0)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff812d84d0-ffffffff812d84fc: alloc_chrdev_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int alloc_chrdev_region(dev_t *dev, unsigned int baseminor, unsigned int count, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e9370)
Location: fs/char_dev.c:236
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiolib_dev_init
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/dax/super.c:dax_core_init
  - drivers/vfio/vfio.c:vfio_init
  - drivers/rtc/dev.c:rtc_dev_init
  - drivers/media/cec/cec-core.c:cec_devnode_init
  - drivers/pps/pps.c:pps_init
  - drivers/ptp/ptp_clock.c:ptp_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff812e9370-ffffffff812e939c: alloc_chrdev_region (STB_GLOBAL)
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
