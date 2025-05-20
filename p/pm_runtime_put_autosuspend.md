# Function: <code>pm_runtime_put_autosuspend</code>

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
In drivers/tty/serial/8250/8250_port.c (ffffffff815060a4)
Location: include/linux/pm_runtime.h:236
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rpm_put_tx
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81540eb9)
Location: include/linux/pm_runtime.h:236
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/mfd/arizona-irq.c (ffffffff8157e289)
Location: include/linux/pm_runtime.h:236
Inline: True
```
```
In drivers/spi/spi.c (ffffffff815e7af4)
Location: include/linux/pm_runtime.h:236
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/mmc/core/core.c (ffffffff816bdd7d)
Location: include/linux/pm_runtime.h:236
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_put_card
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff81495522)
Location: include/linux/pm_runtime.h:242
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8155a7ea)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/mfd/arizona-irq.c (ffffffff815d357a)
Location: include/linux/pm_runtime.h:242
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81641e37)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff816461ba)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/mmc/core/core.c (ffffffff8171fc40)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff814b6ed5)
Location: include/linux/pm_runtime.h:245
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815856ad)
Location: include/linux/pm_runtime.h:245
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffff816002c7)
Location: include/linux/pm_runtime.h:245
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81672f17)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff816772aa)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/mmc/core/core.c (ffffffff817524c0)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff814c180f)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81598ded)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffff8161416a)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81687778)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff8168ba95)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726cb3)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81770cd0)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff81501b3f)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fdbfd)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffff8167c80a)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816f1034)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff816f540b)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81798303)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff817e6a30)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff81530b81)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81637550)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffff816b8273)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817335b1)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817dafbf)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff8182fd8c)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8154810f)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81655b38)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d94b2)
Location: include/linux/pm_runtime.h:233
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8175602f)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818025fd)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff8185c00a)
Location: include/linux/pm_runtime.h:233
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff81578192)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81689ce8)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffff81714acb)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (ffffffff81792152)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818434ba)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff8189fed2)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8159991a)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ac298)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffff81738ddb)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (ffffffff817b5d2e)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81874e3a)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff818d243a)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff816390fa)
Location: include/linux/pm_runtime.h:244
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761151)
Location: include/linux/pm_runtime.h:244
Inline: True
Inline callers:
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
```
```
In drivers/mfd/arizona-irq.c (ffffffff817f675b)
Location: include/linux/pm_runtime.h:244
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (ffffffff8187aa65)
Location: include/linux/pm_runtime.h:244
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81949c1e)
Location: include/linux/pm_runtime.h:244
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff819a4b7a)
Location: include/linux/pm_runtime.h:244
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8165fbe1)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177c381)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
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
```
```
In drivers/mfd/arizona-irq.c (ffffffff8180948b)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (ffffffff81889720)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f8ee)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff819a7c1a)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff816420b9)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175f7c2)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
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
```
```
In drivers/mfd/arizona-irq.c (ffffffff817ee02e)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (ffffffff818691ee)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs_timing
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81933554)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff8198c91a)
Location: include/linux/pm_runtime.h:429
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff816b2d8b)
Location: include/linux/pm_runtime.h:439
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e34ef)
Location: include/linux/pm_runtime.h:439
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff818fbec8)
Location: include/linux/pm_runtime.h:439
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6915)
Location: include/linux/pm_runtime.h:439
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81a37f7a)
Location: include/linux/pm_runtime.h:439
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff817d67b5)
Location: include/linux/pm_runtime.h:468
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81922231)
Location: include/linux/pm_runtime.h:468
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff81a4d56d)
Location: include/linux/pm_runtime.h:468
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39477)
Location: include/linux/pm_runtime.h:468
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81ba4b6a)
Location: include/linux/pm_runtime.h:468
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv.c (ffffffff818f7ba9)
Location: include/linux/pm_runtime.h:472
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7eacb)
Location: include/linux/pm_runtime.h:472
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff81bd72db)
Location: include/linux/pm_runtime.h:472
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf1f7)
Location: include/linux/pm_runtime.h:472
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81d46dba)
Location: include/linux/pm_runtime.h:472
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv.c (ffffffff8193b002)
Location: include/linux/pm_runtime.h:472
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abf3cc)
Location: include/linux/pm_runtime.h:472
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81aca0b7)
Location: include/linux/pm_runtime.h:472
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff81c2dd0b)
Location: include/linux/pm_runtime.h:472
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d37264)
Location: include/linux/pm_runtime.h:472
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81db15aa)
Location: include/linux/pm_runtime.h:472
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv.c (ffffffff81983e95)
Location: include/linux/pm_runtime.h:470
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b12201)
Location: include/linux/pm_runtime.h:470
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:__uart_start
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1d197)
Location: include/linux/pm_runtime.h:470
Inline: True
Inline callers:
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
```
```
In drivers/spi/spi.c (ffffffff81ce0712)
Location: include/linux/pm_runtime.h:470
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded4e4)
Location: include/linux/pm_runtime.h:470
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81e6993a)
Location: include/linux/pm_runtime.h:470
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffff800010701064)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010887018)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffff800010933abc)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (ffff8000109c95c8)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cda04)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea174)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9b98)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abbd44)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abd014)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_master_xfer
```
```
In drivers/mmc/core/core.c (ffff800010b2d978)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (c0898e14)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (c09854f0)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/tty/serial/omap-serial.c (c09a023c)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
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
```
```
In drivers/mfd/arizona-irq.c (c0a16ab4)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (c0ab2fdc)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7f14)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acb4a0)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0ad0408)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset
```
```
In drivers/usb/musb/musb_core.c (c0b64da4)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_resume
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
```
```
In drivers/usb/musb/musb_gadget.c (c0b6faf8)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_stop
  - drivers/usb/musb/musb_gadget.c:musb_gadget_start
  - drivers/usb/musb/musb_gadget.c:musb_gadget_work
  - drivers/usb/musb/musb_gadget.c:musb_gadget_queue
```
```
In drivers/usb/musb/musb_debugfs.c (c0b71588)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_write
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_show
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_write
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_show
  - drivers/usb/musb/musb_debugfs.c:musb_regdump_show
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b99264)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9bf94)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9cfdc)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
```
```
In drivers/mmc/core/core.c (c0c06d98)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2c274)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
```
```
In sound/soc/soc-pcm.c (c0cb24d0)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - sound/soc/soc-pcm.c:soc_pcm_close
  - sound/soc/soc-pcm.c:soc_pcm_open
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
In drivers/tty/serial/8250/8250_port.c (c00000000092e0cc)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/mfd/arizona-irq.c (c0000000009d4a30)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (c000000000a8b1e4)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d67c)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (c000000000c23fec)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffe0004cfe70)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551f8a)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffe0005a9924)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (ffffffe00061967e)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006beda0)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffe0007057c2)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d7aa)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671d08)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffff816fcb3b)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (ffffffff8177a80e)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/mmc/core/core.c (ffffffff81875dfa)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8157c2ea)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81650e08)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d094b)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (ffffffff8175a5be)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d66a)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a00d8)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffff8172c29b)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (ffffffff817aabae)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-amd-mp2-pci.c (ffffffff81868359)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868d5e)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a2ea)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff818c729a)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/pci/pcie/portdrv_pci.c (ffffffff815a7b1a)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ba598)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/mfd/arizona-irq.c (ffffffff817476db)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/spi/spi.c (ffffffff817c4b31)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8188427a)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff818e3d4a)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
</details>
</li>
</ul>

## Differences
