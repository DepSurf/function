# Function: <code>pm_suspend_ignore_children</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81557e2e)
Location: include/linux/device.h:943
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/usb/core/hub.c (ffffffff8160850d)
Location: include/linux/device.h:943
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/driver.c (ffffffff81613ab8)
Location: include/linux/device.h:943
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9ec7)
Location: include/linux/pm_runtime.h:59
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/spi/spi.c (ffffffff81647b2c)
Location: include/linux/pm_runtime.h:59
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_alloc_master
```
```
In drivers/usb/core/hub.c (ffffffff8166ba77)
Location: include/linux/pm_runtime.h:59
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81673a7f)
Location: include/linux/pm_runtime.h:59
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core.c (ffffffff816ddbfa)
Location: include/linux/pm_runtime.h:59
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d88d7)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_init
```
```
In drivers/spi/spi.c (ffffffff81678c1c)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_alloc_master
```
```
In drivers/usb/core/hub.c (ffffffff816997ae)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff816a170f)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core.c (ffffffff8170df6f)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:64
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8168d4e1)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff816aeaa4)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff816b6809)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8172120d)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:64
Inline: True
```
```
In drivers/spi/spi.c (ffffffff816f7061)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff8171a08b)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81722099)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81792593)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:64
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81732503)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff81758e65)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81760db8)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d4fa6)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816616e5)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:64
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81754ef3)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff8177d3d5)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81785378)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fc0f6)
Location: include/linux/pm_runtime.h:64
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81697115)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:63
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8179079b)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff817bb970)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817c390f)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183d062)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816b9cb5)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:63
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817b437b)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff817ec17e)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817f428f)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186ea61)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8176e1d5)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:68
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8187a65b)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff818bb795)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff818c3def)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81942a81)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81788ba5)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:83
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8188921b)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff81c1c2be)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff818cfcdf)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81948dec)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8176c395)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:83
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8186b7ab)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff81c0e1a4)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff818b330f)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192c77c)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff817f1ae5)
Location: include/linux/pm_runtime.h:86
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:86
Inline: True
```
```
In drivers/spi/spi.c (ffffffff818fb454)
Location: include/linux/pm_runtime.h:86
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff81d1527e)
Location: include/linux/pm_runtime.h:86
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff8194875f)
Location: include/linux/pm_runtime.h:86
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cf94b)
Location: include/linux/pm_runtime.h:86
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8193221f)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:116
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81a4cee3)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff81edfe17)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81aa125f)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b317a4)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81a90cc0)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:120
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81bd5153)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff81c1cc62)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81c268df)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc62f4)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81adc4d0)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:120
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81c2bfc3)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff81c83b66)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81c8d89f)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2df84)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81b2f7c0)
Location: include/linux/pm_runtime.h:118
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:118
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81cde8e3)
Location: include/linux/pm_runtime.h:118
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff81d38545)
Location: include/linux/pm_runtime.h:118
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81d423cf)
Location: include/linux/pm_runtime.h:118
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de3f12)
Location: include/linux/pm_runtime.h:118
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffff8000108a9ef0)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:63
Inline: True
```
```
In drivers/spi/spi.c (ffff8000109c3fc0)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffff800010a1a2ac)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffff800010a24d24)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab2254)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c09a63c8)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:63
Inline: True
```
```
In drivers/spi/spi.c (c0ab16c4)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (c0af2510)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (c0afb368)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (c0b938d4)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2ee14)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (c0000000009411f4)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:63
Inline: True
```
```
In drivers/spi/spi.c (c000000000a88ed4)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (c000000000ad3a40)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (c000000000adfb60)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (c000000000b9599c)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffe00055f0d4)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:63
Inline: True
```
```
In drivers/spi/spi.c (ffffffe0006187f2)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffe00063ed02)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffe00064701c)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9f3a)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8167f715)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:63
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81778e5b)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff817a455e)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817ac66f)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:63
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81758c0b)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff817960cf)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff8179e06f)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816adaf5)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:63
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817a91fb)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff817e0ffe)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817e910f)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81862bf1)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff816c7f55)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/pm_runtime.h:63
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817c308b)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/usb/core/hub.c (ffffffff817fb2ee)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff8180363f)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187de51)
Location: include/linux/pm_runtime.h:63
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
</ul>

## Differences
