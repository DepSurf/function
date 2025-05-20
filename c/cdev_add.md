# Function: <code>cdev_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210ac0)
Location: fs/char_dev.c:452
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/rtc-dev.c:rtc_dev_add_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81210ac0-ffffffff81210b17: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81237560)
Location: fs/char_dev.c:456
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/rtc-dev.c:rtc_dev_add_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81237560-ffffffff812375b7: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a210)
Location: fs/char_dev.c:457
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/rtc-dev.c:rtc_dev_add_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8124a210-ffffffff8124a267: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81255b30)
Location: fs/char_dev.c:457
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81255b30-ffffffff81255b81: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81277cc0)
Location: fs/char_dev.c:482
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81277cc0-ffffffff81277d11: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129e620)
Location: fs/char_dev.c:482
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8129e620-ffffffff8129e671: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3900)
Location: fs/char_dev.c:482
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff812b3900-ffffffff812b3951: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d0600)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff812d0600-ffffffff812d0651: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e21a0)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff812e21a0-ffffffff812e21f1: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81319070)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff81319070-ffffffff813190e6: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81324520)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff81324520-ffffffff81324596: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132a5f0)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff8132a5f0-ffffffff8132a666: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81377ca0)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff81377ca0-ffffffff81377d16: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f7050)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff813f7050-ffffffff813f70fc: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81480310)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff81480310-ffffffff814803af: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b5070)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff814b5070-ffffffff814b510f: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e7330)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add
```
**Symbols:**

```
ffffffff814e7330-ffffffff814e73cf: cdev_add (STB_GLOBAL)
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
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff8000103898d8)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffff8000103898d8-ffff800010389950: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571c30)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_cdev_add
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
c0571c30-c0571ca0: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000480320)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
c000000000480320-c0000000004803a8: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025baa0)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffe00025baa0-ffffffe00025bb10: cdev_add (STB_GLOBAL)
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
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da780)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff812da780-ffffffff812da7d1: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb400)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/dax/device.c:dev_dax_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff812cb400-ffffffff812cb451: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d8590)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff812d8590-ffffffff812d85e1: cdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cdev_add(struct cdev *p, dev_t dev, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e9480)
Location: fs/char_dev.c:479
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__register_chrdev
  - block/bsg.c:bsg_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/tty_io.c:tty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_init
  - drivers/usb/core/devio.c:usb_devio_init
  - drivers/pps/pps.c:pps_register_cdev
```
**Symbols:**

```
ffffffff812e9480-ffffffff812e94d1: cdev_add (STB_GLOBAL)
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
