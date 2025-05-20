# Function: <code>cdev_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210b80)
Location: fs/char_dev.c:538
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/rtc-dev.c:rtc_dev_prepare
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81210b80-ffffffff81210bde: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81237620)
Location: fs/char_dev.c:542
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/rtc-dev.c:rtc_dev_prepare
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81237620-ffffffff8123767e: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a2d0)
Location: fs/char_dev.c:543
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/rtc-dev.c:rtc_dev_prepare
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8124a2d0-ffffffff8124a32e: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81255c30)
Location: fs/char_dev.c:626
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/rtc-dev.c:rtc_dev_prepare
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81255c30-ffffffff81255c8e: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81277dc0)
Location: fs/char_dev.c:651
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/rtc-dev.c:rtc_dev_prepare
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81277dc0-ffffffff81277e1e: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129e790)
Location: fs/char_dev.c:651
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/rtc-dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8129e790-ffffffff8129e7ef: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3ba0)
Location: fs/char_dev.c:651
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff812b3ba0-ffffffff812b3bff: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d08b0)
Location: fs/char_dev.c:648
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff812d08b0-ffffffff812d090f: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e2460)
Location: fs/char_dev.c:648
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff812e2460-ffffffff812e24bf: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81319120)
Location: fs/char_dev.c:651
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff81319120-ffffffff8131917f: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813245d0)
Location: fs/char_dev.c:651
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff813245d0-ffffffff8132462f: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132a6a0)
Location: fs/char_dev.c:651
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff8132a6a0-ffffffff8132a6ff: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81377d50)
Location: fs/char_dev.c:651
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_register_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff81377d50-ffffffff81377daf: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f7140)
Location: fs/char_dev.c:651
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_register_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff813f7140-ffffffff813f71ab: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81480410)
Location: fs/char_dev.c:658
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_register_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff81480410-ffffffff8148047b: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b5170)
Location: fs/char_dev.c:658
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff814b5170-ffffffff814b51db: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e7430)
Location: fs/char_dev.c:658
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff814e7430-ffffffff814e749b: cdev_init (STB_GLOBAL)
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
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff800010389c58)
Location: fs/char_dev.c:648
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffff800010389c58-ffff800010389cb8: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571f4c)
Location: fs/char_dev.c:648
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
c0571f4c-c0571f98: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0000000004805b0)
Location: fs/char_dev.c:648
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
c0000000004805b0-c000000000480628: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025bda6)
Location: fs/char_dev.c:648
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffffffe00025bda6-ffffffe00025bdfa: cdev_init (STB_GLOBAL)
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
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812daa40)
Location: fs/char_dev.c:648
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff812daa40-ffffffff812daa9f: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb6c0)
Location: fs/char_dev.c:648
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/dax/device.c:dev_dax_probe
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff812cb6c0-ffffffff812cb71f: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d8850)
Location: fs/char_dev.c:648
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff812d8850-ffffffff812d88af: cdev_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cdev_init(struct cdev *cdev, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e9740)
Location: fs/char_dev.c:648
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/dev.c:rtc_dev_prepare
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff812e9740-ffffffff812e979f: cdev_init (STB_GLOBAL)
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
