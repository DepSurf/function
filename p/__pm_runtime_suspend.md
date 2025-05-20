# Function: <code>__pm_runtime_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815572d0)
Location: drivers/base/power/runtime.c:919
Inline: False
Direct callers:
  - block/blk-core.c:blk_post_runtime_resume
  - drivers/tty/serial/8250/8250_port.c:serial8250_rpm_put_tx
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_put_card
```
**Symbols:**

```
ffffffff815572d0-ffffffff8155734a: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9320)
Location: drivers/base/power/runtime.c:919
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_runtime_active
  - block/blk-core.c:blk_post_runtime_resume
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff815a9320-ffffffff815a939c: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d7ee0)
Location: drivers/base/power/runtime.c:996
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_runtime_active
  - block/blk-core.c:blk_post_runtime_resume
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff815d7ee0-ffffffff815d7f5d: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ecd50)
Location: drivers/base/power/runtime.c:996
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_runtime_active
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff815ecd50-ffffffff815ecdcd: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81654110)
Location: drivers/base/power/runtime.c:997
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_runtime_active
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81654110-ffffffff8165418d: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168fe80)
Location: drivers/base/power/runtime.c:997
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_runtime_active
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff8168fe80-ffffffff8168fefd: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816b0280)
Location: drivers/base/power/runtime.c:1004
Inline: False
Direct callers:
  - block/blk-pm.c:blk_set_runtime_active
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff816b0280-ffffffff816b0392: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ea1c0)
Location: drivers/base/power/runtime.c:1033
Inline: False
Direct callers:
  - block/blk-pm.c:blk_set_runtime_active
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff816ea1c0-ffffffff816ea246: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170e220)
Location: drivers/base/power/runtime.c:1035
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff8170e220-ffffffff8170e2a6: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c9ad0)
Location: drivers/base/power/runtime.c:1035
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff817c9ad0-ffffffff817c9bcf: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817de5d0)
Location: drivers/base/power/runtime.c:1065
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff817de5d0-ffffffff817de6c0: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c29b0)
Location: drivers/base/power/runtime.c:1065
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:spi_set_cs_timing
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff817c29b0-ffffffff817c2aa0: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184ccb0)
Location: drivers/base/power/runtime.c:1084
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff8184ccb0-ffffffff8184cd9d: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81991f10)
Location: drivers/base/power/runtime.c:1109
Inline: False
Direct callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81991f10-ffffffff81992017: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b02300)
Location: drivers/base/power/runtime.c:1122
Inline: False
Direct callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81b02300-ffffffff81b02407: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b503f0)
Location: drivers/base/power/runtime.c:1122
Inline: False
Direct callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81b503f0-ffffffff81b504bf: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba8970)
Location: drivers/base/power/runtime.c:1123
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/tty/serial/serial_core.c:__uart_start
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81ba8970-ffffffff81ba8a3f: __pm_runtime_suspend (STB_GLOBAL)
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
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fdcd8)
Location: drivers/base/power/runtime.c:1035
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_master_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffff8000108fdcd8-ffff8000108fddec: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e80b4)
Location: drivers/base/power/runtime.c:1035
Inline: False
Direct callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_get_char
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_put_char
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_break_ctl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_get_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_tx_empty
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_unthrottle
  - drivers/tty/serial/omap-serial.c:serial_omap_throttle
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_rx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_enable_ms
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_autosuspend_device
  - drivers/usb/musb/musb_core.c:musb_resume
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_gadget.c:musb_gadget_stop
  - drivers/usb/musb/musb_gadget.c:musb_gadget_start
  - drivers/usb/musb/musb_gadget.c:musb_gadget_work
  - drivers/usb/musb/musb_gadget.c:musb_gadget_queue
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_write
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_show
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_write
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_show
  - drivers/usb/musb/musb_debugfs.c:musb_regdump_show
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/power/avs/smartreflex.c:sr_disable
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
  - sound/soc/soc-pcm.c:soc_pcm_close
  - sound/soc/soc-pcm.c:soc_pcm_open
```
**Symbols:**

```
c09e80b4-c09e8160: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c00000000099aa60)
Location: drivers/base/power/runtime.c:1035
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
c00000000099aa60-c00000000099ab48: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058c808)
Location: drivers/base/power/runtime.c:1035
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffe00058c808-ffffffe00058c89a: __pm_runtime_suspend (STB_GLOBAL)
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
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d3970)
Location: drivers/base/power/runtime.c:1035
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff816d3970-ffffffff816d39f6: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816aec20)
Location: drivers/base/power/runtime.c:1035
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff816aec20-ffffffff816aeca6: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81701ee0)
Location: drivers/base/power/runtime.c:1035
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff81701ee0-ffffffff81701f66: __pm_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __pm_runtime_suspend(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171bdf0)
Location: drivers/base/power/runtime.c:1035
Inline: False
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_runtime_idle
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_release_host
```
**Symbols:**

```
ffffffff8171bdf0-ffffffff8171be5e: __pm_runtime_suspend (STB_GLOBAL)
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
