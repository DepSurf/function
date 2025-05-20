# Function: <code>ktime_add_us</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff818d2c2d)
Location: include/linux/ktime.h:193
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/misc/sram.c (ffffffff815fb372)
Location: include/linux/ktime.h:193
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
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
In kernel/time/timer.c (ffffffff81909e3d)
Location: include/linux/ktime.h:193
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/misc/sram.c (ffffffff8160f132)
Location: include/linux/ktime.h:193
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff816126b7)
Location: include/linux/ktime.h:193
Inline: True
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
In kernel/time/timer.c (ffffffff8199417d)
Location: include/linux/ktime.h:193
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/misc/sram.c (ffffffff816779b2)
Location: include/linux/ktime.h:193
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff8167af27)
Location: include/linux/ktime.h:193
Inline: True
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
In kernel/time/timer.c (ffffffff819f0704)
Location: include/linux/ktime.h:193
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81512632)
Location: include/linux/ktime.h:193
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d0bc1)
Location: include/linux/ktime.h:193
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/misc/sram.c (ffffffff816b3411)
Location: include/linux/ktime.h:193
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff816b6c83)
Location: include/linux/ktime.h:193
Inline: True
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
In kernel/time/timer.c (ffffffff81a2ba84)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81527eb2)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ea1f1)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/misc/sram.c (ffffffff816d4671)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff816d7ed4)
Location: include/linux/ktime.h:196
Inline: True
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
In kernel/time/timer.c (ffffffff81a9bcb4)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81557112)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161bf60)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/misc/sram.c (ffffffff8170fec1)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff8171320d)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81802769)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
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
In kernel/time/timer.c (ffffffff81ad3604)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81578752)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163da00)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/misc/sram.c (ffffffff817341b1)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff8173750d)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81833669)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
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
In kernel/time/timer.c (ffffffff81bcb714)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8161d504)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_wait_for_update
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eadc0)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/reset/reset-brcmstb-rescal.c (ffffffff8173323d)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
```
```
In drivers/misc/sram.c (ffffffff817f176f)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff817f4580)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/net/phy/phy_device.c (ffffffff8188372a)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_poll_reset
```
```
In drivers/net/phy/bcm84881.c (ffffffff81889028)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
```
```
In drivers/usb/host/xhci.c (ffffffff8190896a)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81948799)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff8194db2f)
Location: include/linux/ktime.h:178
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
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
In kernel/time/timer.c (ffffffff81c445b7)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81644086)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81708520)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/reset/reset-brcmstb-rescal.c (ffffffff8174f3dd)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
```
```
In drivers/misc/sram.c (ffffffff81805dbf)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff81807fe0)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/net/phy/phy_device.c (ffffffff81891e5a)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_poll_reset
```
```
In drivers/net/phy/bcm84881.c (ffffffff81897298)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f1f18)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci.c (ffffffff819113aa)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81929ca7)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8192b233)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194e599)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff8195351f)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
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
In kernel/time/timer.c (ffffffff81c37827)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81626ddb)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816e9b23)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81707a57)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
```
```
In drivers/regulator/core.c (ffffffff8172b446)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/misc/sram.c (ffffffff817eaa3f)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff817ecbb0)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/net/phy/phy_device.c (ffffffff81874cc0)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879e86)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d5708)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci.c (ffffffff818f499c)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8190d1f7)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8190e759)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81932109)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81932b89)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff819373af)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
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
In kernel/time/timer.c (ffffffff81d560ec)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range_state
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81696657)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8176337f)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81783327)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
```
```
In drivers/regulator/core.c (ffffffff817ab339)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/misc/sram.c (ffffffff818772af)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/spi/spi-mem.c (ffffffff818ffa09)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81905710)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190af26)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81970373)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci.c (ffffffff81992298)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff819addc7)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d5429)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d5f39)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff819db60f)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
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
In kernel/time/timer.c (ffffffff81f280dc)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range_state
```
```
In drivers/pwm/pwm-lpss.c (ffffffff817b74f7)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff818972d7)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818b9f03)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
```
```
In drivers/regulator/core.c (ffffffff818e5fe0)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/misc/sram.c (ffffffff819bf508)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/spi/spi-mem.c (ffffffff81a50f68)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5801e)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e426)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81aca375)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci.c (ffffffff81aeed25)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81b0c4f7)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37e50)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b38a60)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81b3a300)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81b3f076)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
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
In kernel/time/timer.c (ffffffff820d3cbc)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range_state
```
```
In drivers/pwm/pwm-lpss.c (ffffffff818d1bba)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df01e)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a08863)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
```
```
In drivers/regulator/core.c (ffffffff81a3e96d)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/misc/sram.c (ffffffff81b34ca8)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/spi/spi-mem.c (ffffffff81bda168)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81be1dba)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be9166)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81c54915)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci.c (ffffffff81c7bd57)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81c9c4c7)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd490)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81cce370)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81ccfd40)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81cd5456)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
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
In kernel/time/timer.c (ffffffff82157f3c)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range_state
```
```
In kernel/trace/trace_osnoise.c (ffffffff81295d91)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_sleep
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81914baa)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a26d2e)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/regulator/core.c (ffffffff81a883f7)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/misc/sram.c (ffffffff81b88188)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/spi/spi-mem.c (ffffffff81c30be8)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81c396ae)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c41596)
Location: include/linux/ktime.h:179
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81ce2fc6)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d35200)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d36c12)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81d3d0e6)
Location: include/linux/ktime.h:179
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
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
In kernel/time/timer.c (ffffffff8223adac)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range_state
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b1401)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_sleep
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8195cb1a)
Location: include/linux/ktime.h:177
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4b0d)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a71d3e)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/regulator/core.c (ffffffff81adaae7)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_do_enable
```
```
In drivers/misc/sram.c (ffffffff81bdc038)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/spi/spi-mem.c (ffffffff81ce3a78)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81ceea3e)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6c26)
Location: include/linux/ktime.h:177
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff81d98118)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb390)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81dec9d2)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81df3a36)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e9380b)
Location: include/linux/ktime.h:177
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
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
In kernel/time/timer.c (ffff800010da62b0)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072b964)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731f8c)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a88fc)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/clk/imx/clk-frac-pll.c (ffff8000107d3b0c)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
```
```
In drivers/clk/imx/clk-pfdv2.c (ffff8000107d483c)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
```
```
In drivers/clk/imx/clk-pllv4.c (ffff8000107d5d74)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
```
```
In drivers/clk/imx/clk-sccg-pll.c (ffff8000107d65d0)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/clk/imx/clk-pll14xx.c (ffff8000107d6ae4)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_common.c (ffff8000107f485c)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/soc/imx/gpcv2.c (ffff8000108181f0)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
```
```
In drivers/soc/mediatek/mtk-infracfg.c (ffff800010818b64)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
```
```
In drivers/soc/mediatek/mtk-scpsys.c (ffff800010819488)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
```
```
In drivers/soc/amlogic/meson-clk-measure.c (ffff80001081990c)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
```
```
In drivers/soc/rockchip/pm_domains.c (ffff80001081eac4)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a583c)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d1918)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d522c)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d8bf8)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable_stall
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable_stall
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108dadd8)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
```
```
In drivers/misc/sram.c (ffff80001092ae20)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/lochnagar-i2c.c (ffff800010931224)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
```
```
In drivers/mfd/arizona-core.c (ffff800010932434)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109ccf44)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
```
```
In drivers/usb/phy/phy-mxs-usb.c (ffff800010a39a58)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
```
```
In drivers/usb/host/xhci.c (ffff800010a70634)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/media/cec/cec-pin.c (ffff800010ac4bcc)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
```
In drivers/thermal/armada_thermal.c (ffff800010addca4)
Location: include/linux/ktime.h:196
Inline: True
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
In arch/arm/mach-meson/platsmp.c (c03305a8)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
```
```
In kernel/time/timer.c (c0e9dea4)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/bus/ti-sysc.c (c0828d20)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
```
```
In drivers/phy/samsung/phy-exynos-pcie.c (c082c770)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
```
```
In drivers/pci/controller/pci-tegra.c (c08ad1fc)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b5570)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_check_cfg_cpld
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bbd18)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf364)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
```
```
In drivers/clk/clk-milbeaut.c (c08f4ed8)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate
```
```
In drivers/clk/imx/clk-frac-pll.c (c08fae5c)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
```
```
In drivers/clk/imx/clk-pfdv2.c (c08fb8e8)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
```
```
In drivers/clk/imx/clk-pllv4.c (c08fcd64)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
```
```
In drivers/clk/imx/clk-sccg-pll.c (c08fd1e8)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/clk/imx/clk-pll14xx.c (c08fde70)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_wait_lock
```
```
In drivers/clk/uniphier/clk-uniphier-cpugear.c (c091c2c4)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/soc/imx/gpcv2.c (c0934e6c)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
```
```
In drivers/soc/mediatek/mtk-infracfg.c (c0935860)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
```
```
In drivers/soc/mediatek/mtk-scpsys.c (c0935d24)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
```
```
In drivers/soc/amlogic/meson-clk-measure.c (c0936418)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
```
```
In drivers/soc/rockchip/pm_domains.c (c09390e8)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
```
```
In drivers/soc/tegra/pmc.c (c093d730)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
```
```
In drivers/tty/serial/mvebu-uart.c (c09a1438)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
```
```
In drivers/iommu/rockchip-iommu.c (c09c5ed0)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
```
```
In drivers/iommu/qcom_iommu.c (c09cb7b0)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
```
```
In drivers/misc/sram.c (c0a09560)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/lochnagar-i2c.c (c0a14334)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
```
```
In drivers/mfd/arizona-core.c (c0a14cc8)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab6000)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfae0)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_suspend
```
```
In drivers/usb/phy/phy-mxs-usb.c (c0b0c9e0)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
```
```
In drivers/usb/host/xhci.c (c0b44598)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/thermal/armada_thermal.c (c0bbf8b0)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_wait_sensor_validity
```
```
In drivers/mmc/host/cqhci.c (c0c3008c)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_off
```
```
In drivers/firmware/tegra/bpmp.c (c0c42030)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
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
In kernel/time/timer.c (c000000000ee8878)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/misc/sram.c (c0000000009c9dec)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/lochnagar-i2c.c (c0000000009d1734)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
```
```
In drivers/mfd/arizona-core.c (c0000000009d24fc)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/usb/host/xhci.c (c000000000b44c8c)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
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
In kernel/time/timer.c (ffffffe0008c862a)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/misc/sram.c (ffffffe0005a2780)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/lochnagar-i2c.c (ffffffe0005a7656)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
```
```
In drivers/mfd/arizona-core.c (ffffffe0005a7dce)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/usb/host/xhci.c (ffffffe000688dd0)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
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
In kernel/time/timer.c (ffffffff81a72474)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81609430)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/misc/sram.c (ffffffff816fa241)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff816fb26d)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817eba49)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
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
In kernel/time/timer.c (ffffffff81a2e844)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fb070)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/misc/sram.c (ffffffff816ce051)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff816cf07d)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817b0b59)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
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
In kernel/time/timer.c (ffffffff81ade884)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8156c4a2)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81631840)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/misc/sram.c (ffffffff81727671)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff8172a9cd)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff818284e9)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
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
In kernel/time/timer.c (ffffffff81aead04)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - kernel/time/timer.c:usleep_range
```
```
In drivers/pwm/pwm-lpss.c (ffffffff815869a2)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164bb80)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/misc/sram.c (ffffffff81742ab1)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff81745e0d)
Location: include/linux/ktime.h:196
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff818424b9)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/media/cec/cec-pin.c (ffffffff8188c884)
Location: include/linux/ktime.h:196
Inline: True
Inline callers:
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
  - drivers/media/cec/cec-pin.c:cec_pin_timer
```
</details>
</li>
</ul>

## Differences
