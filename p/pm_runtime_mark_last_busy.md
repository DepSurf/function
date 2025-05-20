# Function: <code>pm_runtime_mark_last_busy</code>

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
In block/blk-core.c (ffffffff813b66c8)
Location: include/linux/pm_runtime.h:112
Inline: True
Inline callers:
  - block/blk-core.c:blk_pre_runtime_suspend
  - block/blk-core.c:blk_post_runtime_suspend
  - block/blk-core.c:blk_post_runtime_resume
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8150609d)
Location: include/linux/pm_runtime.h:112
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rpm_put_tx
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81540eb2)
Location: include/linux/pm_runtime.h:112
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/base/power/runtime.c (ffffffff81556a1b)
Location: include/linux/pm_runtime.h:112
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff8157cc8b)
Location: include/linux/pm_runtime.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff8157e282)
Location: include/linux/pm_runtime.h:112
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff815b8f5d)
Location: include/linux/pm_runtime.h:112
Inline: True
```
```
In drivers/spi/spi.c (ffffffff815e7aed)
Location: include/linux/pm_runtime.h:112
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81608937)
Location: include/linux/pm_runtime.h:112
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff81613869)
Location: include/linux/pm_runtime.h:112
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_runtime_suspend
```
```
In drivers/mmc/core/core.c (ffffffff816bdd76)
Location: include/linux/pm_runtime.h:112
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
  - drivers/mmc/core/core.c:mmc_put_card
```
```
In drivers/mmc/core/mmc.c (ffffffff816c47ac)
Location: include/linux/pm_runtime.h:112
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_resume
```
```
In drivers/mmc/core/sd.c (ffffffff816c7e2c)
Location: include/linux/pm_runtime.h:112
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_resume
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
In block/blk-core.c (ffffffff813fc710)
Location: include/linux/pm_runtime.h:117
Inline: True
Inline callers:
  - block/blk-core.c:blk_set_runtime_active
  - block/blk-core.c:blk_post_runtime_resume
  - block/blk-core.c:blk_post_runtime_suspend
  - block/blk-core.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8149551b)
Location: include/linux/pm_runtime.h:117
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8155a7e3)
Location: include/linux/pm_runtime.h:117
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
```
In drivers/base/power/runtime.c (ffffffff815a981f)
Location: include/linux/pm_runtime.h:117
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff815d1d5b)
Location: include/linux/pm_runtime.h:117
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff815d3573)
Location: include/linux/pm_runtime.h:117
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81611979)
Location: include/linux/pm_runtime.h:117
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81641e30)
Location: include/linux/pm_runtime.h:117
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff816461b3)
Location: include/linux/pm_runtime.h:117
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff816688fc)
Location: include/linux/pm_runtime.h:117
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81675627)
Location: include/linux/pm_runtime.h:117
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/core.c (ffffffff8171fc35)
Location: include/linux/pm_runtime.h:117
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
In block/blk-core.c (ffffffff81416000)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - block/blk-core.c:blk_set_runtime_active
  - block/blk-core.c:blk_post_runtime_resume
  - block/blk-core.c:blk_post_runtime_suspend
  - block/blk-core.c:blk_pre_runtime_suspend
  - block/blk-core.c:__blk_put_request
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814b6ece)
Location: include/linux/pm_runtime.h:116
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815856a6)
Location: include/linux/pm_runtime.h:116
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff815d85fa)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff815fe8cb)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff816002c0)
Location: include/linux/pm_runtime.h:116
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81641209)
Location: include/linux/pm_runtime.h:116
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81672f10)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff816772a3)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff8169661c)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff816a32b7)
Location: include/linux/pm_runtime.h:116
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/core.c (ffffffff817524b5)
Location: include/linux/pm_runtime.h:116
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
In block/blk-core.c (ffffffff814236e0)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - block/blk-core.c:blk_set_runtime_active
  - block/blk-core.c:__blk_put_request
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814c1808)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81598de6)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff815ecbc4)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff816127cb)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff81614163)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81655ae9)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81687771)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff8168ba8e)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff816aba4b)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff816b845f)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726cac)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81770cc5)
Location: include/linux/pm_runtime.h:106
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
In block/blk-core.c (ffffffff8144eb90)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - block/blk-core.c:blk_set_runtime_active
  - block/blk-core.c:__blk_put_request
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81501b38)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fdbf6)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81653f76)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff8167b03b)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff8167c803)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff816bf099)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816f102d)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff816f5404)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81716eab)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81723d6f)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817982fc)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff817e6a25)
Location: include/linux/pm_runtime.h:106
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
In block/blk-core.c (ffffffff81481626)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - block/blk-core.c:blk_set_runtime_active
  - block/blk-core.c:__blk_put_request
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81530b6b)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81637549)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8168eddc)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff816b6d79)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff816b8260)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff816fb6a9)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8173359e)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81755cf8)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817629f0)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817dafac)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff8182fd75)
Location: include/linux/pm_runtime.h:106
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
In block/blk-mq.c (ffffffff814a7558)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff814d5fb4)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - block/blk-pm.c:blk_set_runtime_active
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff815480fb)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81655b23)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816af10c)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff816d7fb9)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d94a0)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8171df49)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8175601e)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff8177a2ba)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81786ff4)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818025ec)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff8185bff5)
Location: include/linux/pm_runtime.h:106
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
In block/blk-mq.c (ffffffff814d54ae)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff81501e11)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-pm.c:blk_set_runtime_active
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8157817e)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81689cd3)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816e9a8f)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff81713539)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff81714ab9)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff8175967b)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81792141)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff817b7df2)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817c5477)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818434a9)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff8189febd)
Location: include/linux/pm_runtime.h:105
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
In block/blk-mq.c (ffffffff814ee78e)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff8151fc64)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81599906)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ac283)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8170daef)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff81737839)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff81738dc9)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff8177d59b)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817b5d1d)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff817e85c2)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817f5e17)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81874e29)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff818d2425)
Location: include/linux/pm_runtime.h:105
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
In block/blk-mq.c (ffffffff8154e6b9)
Location: include/linux/pm_runtime.h:110
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff81580bf4)
Location: include/linux/pm_runtime.h:110
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff816390e6)
Location: include/linux/pm_runtime.h:110
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761140)
Location: include/linux/pm_runtime.h:110
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
In drivers/base/power/runtime.c (ffffffff817c981f)
Location: include/linux/pm_runtime.h:110
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff817f4ed1)
Location: include/linux/pm_runtime.h:110
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
```
```
In drivers/mfd/arizona-irq.c (ffffffff817f6749)
Location: include/linux/pm_runtime.h:110
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff81840c4d)
Location: include/linux/pm_runtime.h:110
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8187aa54)
Location: include/linux/pm_runtime.h:110
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff818b7ae4)
Location: include/linux/pm_runtime.h:110
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818c5d07)
Location: include/linux/pm_runtime.h:110
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81949c0d)
Location: include/linux/pm_runtime.h:110
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff819a4b65)
Location: include/linux/pm_runtime.h:110
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
In block/blk-mq.c (ffffffff8156aa79)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff8159ddf5)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8165fbcd)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177c370)
Location: include/linux/pm_runtime.h:194
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
In drivers/base/power/runtime.c (ffffffff817de31f)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff81808a21)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
```
```
In drivers/mfd/arizona-irq.c (ffffffff81809479)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff8185118d)
Location: include/linux/pm_runtime.h:194
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8188970f)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff818c63f4)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818d1bd7)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f8dd)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff819a7c05)
Location: include/linux/pm_runtime.h:194
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
In block/blk-mq.c (ffffffff815729a9)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff815a4a35)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff816420a5)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175f7b1)
Location: include/linux/pm_runtime.h:194
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
In drivers/base/power/runtime.c (ffffffff817c2732)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff817ed581)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
  - drivers/mfd/arizona-core.c:arizona_runtime_resume
```
```
In drivers/mfd/arizona-irq.c (ffffffff817ee01c)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff8183421d)
Location: include/linux/pm_runtime.h:194
Inline: True
```
```
In drivers/spi/spi.c (ffffffff818691da)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs_timing
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff818a9758)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818b51e7)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81933543)
Location: include/linux/pm_runtime.h:194
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff8198c905)
Location: include/linux/pm_runtime.h:194
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
In block/blk-mq.c (ffffffff815d6fd9)
Location: include/linux/pm_runtime.h:197
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff8160d445)
Location: include/linux/pm_runtime.h:197
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff816b2d77)
Location: include/linux/pm_runtime.h:197
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e34de)
Location: include/linux/pm_runtime.h:197
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
In drivers/base/power/runtime.c (ffffffff8184c2f2)
Location: include/linux/pm_runtime.h:197
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/scsi/scsi_pm.c (ffffffff818c021a)
Location: include/linux/pm_runtime.h:197
Inline: True
```
```
In drivers/spi/spi.c (ffffffff818fbeb7)
Location: include/linux/pm_runtime.h:197
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff8193e668)
Location: include/linux/pm_runtime.h:197
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff8194a767)
Location: include/linux/pm_runtime.h:197
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6904)
Location: include/linux/pm_runtime.h:197
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81a37f65)
Location: include/linux/pm_runtime.h:197
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
In block/blk-mq.c (ffffffff81686564)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff816c1655)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff817d67a1)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81922220)
Location: include/linux/pm_runtime.h:227
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
In drivers/base/power/runtime.c (ffffffff81991cc4)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/scsi/scsi_pm.c (ffffffff81a0c783)
Location: include/linux/pm_runtime.h:227
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81a4d55b)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81a96693)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81aa343e)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39466)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81ba4b55)
Location: include/linux/pm_runtime.h:227
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
In block/blk-mq.c (ffffffff817446e3)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff81782785)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv.c (ffffffff818f7b95)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7eaba)
Location: include/linux/pm_runtime.h:231
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
In drivers/base/power/runtime.c (ffffffff81b02142)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/scsi/scsi_pm.c (ffffffff81b8c253)
Location: include/linux/pm_runtime.h:231
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81bd72ca)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81c19208)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81c28fbe)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf1e6)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81d46da5)
Location: include/linux/pm_runtime.h:231
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
In block/blk-mq.c (ffffffff81780106)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff817c28c8)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv.c (ffffffff8193afee)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abf3b7)
Location: include/linux/pm_runtime.h:231
Inline: True
```
```
In drivers/tty/serial/serial_port.c (ffffffff81ac46f5)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/tty/serial/serial_port.c:serial_port_runtime_resume
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81aca0a6)
Location: include/linux/pm_runtime.h:231
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
In drivers/base/power/runtime.c (ffffffff81b50232)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/scsi/scsi_pm.c (ffffffff81be0263)
Location: include/linux/pm_runtime.h:231
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81c2dcfa)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81c801c1)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81c8ff8e)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d37253)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81db1595)
Location: include/linux/pm_runtime.h:231
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
In block/blk-mq.c (ffffffff817c1956)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff81807394)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983e81)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b121ec)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:__uart_start
```
```
In drivers/tty/serial/serial_port.c (ffffffff81b17787)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/tty/serial/serial_port.c:serial_port_runtime_suspend
  - drivers/tty/serial/serial_port.c:serial_port_runtime_resume
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1d186)
Location: include/linux/pm_runtime.h:229
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
In drivers/base/power/runtime.c (ffffffff81ba87b2)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/scsi/scsi_pm.c (ffffffff81c35293)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81ce0701)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81d34b91)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81d44b3e)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded4d3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff81e69925)
Location: include/linux/pm_runtime.h:229
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
In block/blk-mq.c (ffff8000105ed41c)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffff800010628a08)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffff80001070105c)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffff80001088700c)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/base/power/runtime.c (ffff8000108fd118)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffff800010932840)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffff800010933ab0)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffff800010983754)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/spi/spi.c (ffff8000109c95bc)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cd9f8)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ea16c)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
```
```
In drivers/usb/core/hub.c (ffff800010a17bac)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffff800010a26e28)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9b8c)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abbd38)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abd008)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_master_xfer
```
```
In drivers/mmc/core/core.c (ffff800010b2d970)
Location: include/linux/pm_runtime.h:105
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
In block/blk-mq.c (c07998f8)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (c07d009c)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (c0898dfc)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (c09854d8)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/tty/serial/omap-serial.c (c09a0224)
Location: include/linux/pm_runtime.h:105
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
In drivers/base/power/runtime.c (c09e87b8)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (c0a15078)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (c0a16a9c)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (c0a55fe0)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/spi/spi.c (c0ab2fc4)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7efc)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acb488)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0ad03f0)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset
```
```
In drivers/usb/core/hub.c (c0aefc10)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (c0afced0)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autosuspend_device
  - drivers/usb/core/driver.c:usb_resume_both
```
```
In drivers/usb/musb/musb_core.c (c0b64d88)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_resume
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
```
```
In drivers/usb/musb/musb_gadget.c (c0b6fae0)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_stop
  - drivers/usb/musb/musb_gadget.c:musb_gadget_start
  - drivers/usb/musb/musb_gadget.c:musb_gadget_work
  - drivers/usb/musb/musb_gadget.c:musb_gadget_queue
```
```
In drivers/usb/musb/musb_debugfs.c (c0b71570)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_write
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_show
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_write
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_show
  - drivers/usb/musb/musb_debugfs.c:musb_regdump_show
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b9924c)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9bf7c)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9cfc4)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
```
```
In drivers/mmc/core/core.c (c0c06d7c)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2a85c)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_runtime_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
```
```
In sound/soc/soc-pcm.c (c0cb24b8)
Location: include/linux/pm_runtime.h:105
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
In block/blk-mq.c (c000000000783230)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (c0000000007ca4c4)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092e0b8)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/base/power/runtime.c (c000000000999998)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (c0000000009d27f8)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (c0000000009d4a20)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (c000000000a40280)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/spi/spi.c (c000000000a8b1d4)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (c000000000ad0a10)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (c000000000ae28a0)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d66c)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (c000000000c23fd4)
Location: include/linux/pm_runtime.h:105
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
In block/blk-mq.c (ffffffe00042cd9e)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffe000459e42)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffe0004cfe64)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551f82)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffe00058bf6a)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffe0005a7fe8)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffe0005a991c)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffe0005e8bbc)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/spi/spi.c (ffffffe000619676)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffe00063c95e)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffe000648c76)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006bed94)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffe0007057b6)
Location: include/linux/pm_runtime.h:105
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
In block/blk-mq.c (ffffffff814e6d6e)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff81518244)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d796)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671cf3)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816d323f)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff816fb599)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff816fcb29)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff81731c8b)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8177a7fd)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff817a09a2)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817ae1f7)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/core.c (ffffffff81875de5)
Location: include/linux/pm_runtime.h:105
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
In block/blk-mq.c (ffffffff814d72de)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff81508554)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8157c2d6)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81650df3)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816ae52f)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff816cf3a9)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d0939)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff8170b0ab)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8175a5ad)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff817927e2)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff8179fbf7)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In block/blk-mq.c (ffffffff814e2dfe)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff815142d4)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d656)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a00c3)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff817017af)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff8172acf9)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff8172c289)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff81770a5b)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817aab9d)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff817dd442)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817eac97)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868d4d)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a2d9)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff818c7285)
Location: include/linux/pm_runtime.h:105
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
In block/blk-mq.c (ffffffff814fbc7e)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
```
In block/blk-pm.c (ffffffff8152da8f)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff815a7b06)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ba583)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8171c56f)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff81746139)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_wait_for_boot
```
```
In drivers/mfd/arizona-irq.c (ffffffff817476c9)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff8178c1fb)
Location: include/linux/pm_runtime.h:105
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817c4b20)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff817f7712)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81804ed7)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81884269)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/mmc/core/core.c (ffffffff818e3d35)
Location: include/linux/pm_runtime.h:105
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_release_host
```
</details>
</li>
</ul>

## Differences
