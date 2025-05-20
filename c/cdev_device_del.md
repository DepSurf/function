# Function: <code>cdev_device_del</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81255bf0)
Location: fs/char_dev.c:546
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:rtc_device_unregister
```
**Symbols:**

```
ffffffff81255bf0-ffffffff81255c21: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81277d80)
Location: fs/char_dev.c:571
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:rtc_device_unregister
```
**Symbols:**

```
ffffffff81277d80-ffffffff81277db1: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129e750)
Location: fs/char_dev.c:571
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:rtc_device_unregister
```
**Symbols:**

```
ffffffff8129e750-ffffffff8129e786: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b3a30)
Location: fs/char_dev.c:571
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
```
**Symbols:**

```
ffffffff812b3a30-ffffffff812b3a66: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d0740)
Location: fs/char_dev.c:568
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
```
**Symbols:**

```
ffffffff812d0740-ffffffff812d0776: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e22f0)
Location: fs/char_dev.c:568
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff812e22f0-ffffffff812e2326: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81319700)
Location: fs/char_dev.c:571
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff81319700-ffffffff8131974c: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81324de0)
Location: fs/char_dev.c:571
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_unregister_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff81324de0-ffffffff81324e2c: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132ae30)
Location: fs/char_dev.c:571
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_unregister_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff8132ae30-ffffffff8132ae7c: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81378540)
Location: fs/char_dev.c:571
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - block/bsg.c:bsg_register_queue
  - block/bsg.c:bsg_unregister_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_unregister_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff81378540-ffffffff8137858c: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f7930)
Location: fs/char_dev.c:571
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - block/bsg.c:bsg_register_queue
  - block/bsg.c:bsg_unregister_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm2-space.c:tpm_devs_remove
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_unregister_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff813f7930-ffffffff813f7994: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81480cd0)
Location: fs/char_dev.c:578
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - block/bsg.c:bsg_register_queue
  - block/bsg.c:bsg_unregister_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm2-space.c:tpm_devs_remove
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_unregister_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff81480cd0-ffffffff81480d34: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b58f0)
Location: fs/char_dev.c:578
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - block/bsg.c:bsg_register_queue
  - block/bsg.c:bsg_unregister_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm2-space.c:tpm_devs_remove
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_unregister_device
  - drivers/i2c/i2c-dev.c:i2cdev_detach_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff814b58f0-ffffffff814b5954: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e7c00)
Location: fs/char_dev.c:578
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - block/bsg.c:bsg_register_queue
  - block/bsg.c:bsg_unregister_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm2-space.c:tpm_devs_remove
  - drivers/input/mousedev.c:mousedev_exit
  - drivers/input/mousedev.c:mousedev_init
  - drivers/input/mousedev.c:mousedev_disconnect
  - drivers/input/mousedev.c:mousedev_connect
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_unregister_device
  - drivers/i2c/i2c-dev.c:i2cdev_detach_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff814e7c00-ffffffff814e7c64: cdev_device_del (STB_GLOBAL)
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
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff800010389a88)
Location: fs/char_dev.c:568
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffff800010389a88-ffff800010389ad4: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571dfc)
Location: fs/char_dev.c:568
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
c0571dfc-c0571e38: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000480530)
Location: fs/char_dev.c:568
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
c000000000480530-c0000000004805ac: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025bc22)
Location: fs/char_dev.c:568
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffe00025bc22-ffffffe00025bc6e: cdev_device_del (STB_GLOBAL)
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
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da8d0)
Location: fs/char_dev.c:568
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/nvme/host/core.c:nvme_do_delete_ctrl
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff812da8d0-ffffffff812da906: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb550)
Location: fs/char_dev.c:568
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/nvme/host/core.c:nvme_do_delete_ctrl
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff812cb550-ffffffff812cb586: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d86e0)
Location: fs/char_dev.c:568
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff812d86e0-ffffffff812d8716: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cdev_device_del(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e95d0)
Location: fs/char_dev.c:568
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/input/mousedev.c:mousedev_destroy
  - drivers/input/evdev.c:evdev_disconnect
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff812e95d0-ffffffff812e9606: cdev_device_del (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
