# Function: <code>cdev_device_add</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81255c90)
Location: fs/char_dev.c:512
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:__rtc_register_device
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff81255c90-ffffffff81255d06: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81277e20)
Location: fs/char_dev.c:537
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:__rtc_register_device
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff81277e20-ffffffff81277e96: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8129e6e0)
Location: fs/char_dev.c:537
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:__rtc_register_device
  - drivers/rtc/class.c:rtc_device_register
```
**Symbols:**

```
ffffffff8129e6e0-ffffffff8129e74c: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812b39c0)
Location: fs/char_dev.c:537
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:__rtc_register_device
```
**Symbols:**

```
ffffffff812b39c0-ffffffff812b3a2c: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d06d0)
Location: fs/char_dev.c:534
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
```
**Symbols:**

```
ffffffff812d06d0-ffffffff812d073d: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e2270)
Location: fs/char_dev.c:534
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff812e2270-ffffffff812e22e6: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81319820)
Location: fs/char_dev.c:537
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/char/tpm/tpm-chip.c:tpm_add_char_device
  - drivers/char/tpm/tpm-chip.c:tpm_add_char_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff81319820-ffffffff813198aa: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81324f00)
Location: fs/char_dev.c:537
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/char/tpm/tpm-chip.c:tpm_add_char_device
  - drivers/char/tpm/tpm-chip.c:tpm_add_char_device
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff81324f00-ffffffff81324f8a: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff8132aed0)
Location: fs/char_dev.c:537
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff8132aed0-ffffffff8132af5a: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813785e0)
Location: fs/char_dev.c:537
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_register_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff813785e0-ffffffff8137866a: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff813f7a00)
Location: fs/char_dev.c:537
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_register_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/vfio/vfio.c:vfio_create_group
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff813f7a00-ffffffff813f7a9c: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff81481010)
Location: fs/char_dev.c:544
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - block/bsg.c:bsg_register_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff81481010-ffffffff814810c1: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814b5c40)
Location: fs/char_dev.c:544
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff814b5c40-ffffffff814b5cf1: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff814e7f50)
Location: fs/char_dev.c:544
Inline: False
Direct callers:
  - block/bsg.c:bsg_register_queue
  - drivers/gpio/gpiolib-cdev.c:gpiolib_cdev_register
  - drivers/char/tpm/tpm2-space.c:tpm_devs_add
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff814e7f50-ffffffff814e8001: cdev_device_add (STB_GLOBAL)
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
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffff8000103899f0)
Location: fs/char_dev.c:534
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffff8000103899f0-ffff800010389a84: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c0571d68)
Location: fs/char_dev.c:534
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
c0571d68-c0571dfc: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (c000000000480470)
Location: fs/char_dev.c:534
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
c000000000480470-c000000000480528: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffe00025bba4)
Location: fs/char_dev.c:534
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffffffe00025bba4-ffffffe00025bc22: cdev_device_add (STB_GLOBAL)
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
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812da850)
Location: fs/char_dev.c:534
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff812da850-ffffffff812da8c6: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812cb4d0)
Location: fs/char_dev.c:534
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/nvme/host/core.c:nvme_init_ctrl
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff812cb4d0-ffffffff812cb546: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812d8660)
Location: fs/char_dev.c:534
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff812d8660-ffffffff812d86d6: cdev_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cdev_device_add(struct cdev *cdev, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/char_dev.c (ffffffff812e9550)
Location: fs/char_dev.c:534
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_register
  - drivers/gpio/gpiolib.c:gpiochip_setup_dev
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/evdev.c:evdev_connect
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
**Symbols:**

```
ffffffff812e9550-ffffffff812e95c6: cdev_device_add (STB_GLOBAL)
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
