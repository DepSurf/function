# Function: <code>cdev_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81210b20)
Location: fs/char_dev.c:481
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/rtc/rtc-dev.c:rtc_dev_del_device
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_unregister
```
**Symbols:**

```
ffffffff81210b20-ffffffff81210b4a: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812375c0)
Location: fs/char_dev.c:485
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - fs/char_dev.c:__unregister_chrdev
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/rtc/rtc-dev.c:rtc_dev_del_device
```
**Symbols:**

```
ffffffff812375c0-ffffffff812375ea: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8124a270)
Location: fs/char_dev.c:486
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - fs/char_dev.c:__unregister_chrdev
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/rtc/rtc-dev.c:rtc_dev_del_device
```
**Symbols:**

```
ffffffff8124a270-ffffffff8124a29a: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81255b90)
Location: fs/char_dev.c:569
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:tty_driver_kref_put
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff81255b90-ffffffff81255bba: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81277d20)
Location: fs/char_dev.c:594
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff81277d20-ffffffff81277d4a: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129e680)
Location: fs/char_dev.c:594
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff8129e680-ffffffff8129e6aa: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3960)
Location: fs/char_dev.c:594
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff812b3960-ffffffff812b398a: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d0660)
Location: fs/char_dev.c:591
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff812d0660-ffffffff812d068c: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e2200)
Location: fs/char_dev.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
```
**Symbols:**

```
ffffffff812e2200-ffffffff812e222c: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81319729)
Location: fs/char_dev.c:594
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
Direct callers:
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
```
**Symbols:**

```
ffffffff813190f0-ffffffff8131911e: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81324e09)
Location: fs/char_dev.c:594
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
Direct callers:
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
```
**Symbols:**

```
ffffffff813245a0-ffffffff813245ce: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132ae59)
Location: fs/char_dev.c:594
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
Direct callers:
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove
```
**Symbols:**

```
ffffffff8132a670-ffffffff8132a69e: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81378569)
Location: fs/char_dev.c:594
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
Direct callers:
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove
```
**Symbols:**

```
ffffffff81377d20-ffffffff81377d4e: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f7965)
Location: fs/char_dev.c:594
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
Direct callers:
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove
```
**Symbols:**

```
ffffffff813f7100-ffffffff813f7137: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81480d05)
Location: fs/char_dev.c:601
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
Direct callers:
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove
```
**Symbols:**

```
ffffffff814803c0-ffffffff814803f7: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b5925)
Location: fs/char_dev.c:601
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
Direct callers:
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove
```
**Symbols:**

```
ffffffff814b5120-ffffffff814b5157: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e7c35)
Location: fs/char_dev.c:601
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
Direct callers:
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/dma-buf/dma-heap.c:dma_heap_add
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
  - drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_remove
```
**Symbols:**

```
ffffffff814e73e0-ffffffff814e7417: cdev_del (STB_GLOBAL)
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
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff800010389950)
Location: fs/char_dev.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:tty_driver_kref_put
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
```
**Symbols:**

```
ffff800010389950-ffff80001038998c: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571cf0)
Location: fs/char_dev.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:tty_driver_kref_put
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
```
**Symbols:**

```
c0571cf0-c0571d2c: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0000000004803b0)
Location: fs/char_dev.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:tty_driver_kref_put
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
```
**Symbols:**

```
c0000000004803b0-c00000000048040c: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025bb10)
Location: fs/char_dev.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
```
**Symbols:**

```
ffffffe00025bb10-ffffffe00025bb50: cdev_del (STB_GLOBAL)
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
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da7e0)
Location: fs/char_dev.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
```
**Symbols:**

```
ffffffff812da7e0-ffffffff812da80c: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb460)
Location: fs/char_dev.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/dax/device.c:dev_dax_probe
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
```
**Symbols:**

```
ffffffff812cb460-ffffffff812cb48c: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d85f0)
Location: fs/char_dev.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
```
**Symbols:**

```
ffffffff812d85f0-ffffffff812d861c: cdev_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cdev_del(struct cdev *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e94e0)
Location: fs/char_dev.c:591
Inline: False
Direct callers:
  - fs/char_dev.c:cdev_device_del
  - fs/char_dev.c:cdev_device_add
  - fs/char_dev.c:__unregister_chrdev
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:add_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/vfio/vfio.c:vfio_cleanup
  - drivers/usb/core/devio.c:usb_devio_cleanup
  - drivers/pps/pps.c:pps_register_cdev
  - drivers/pps/pps.c:pps_device_destruct
```
**Symbols:**

```
ffffffff812e94e0-ffffffff812e950c: cdev_del (STB_GLOBAL)
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
