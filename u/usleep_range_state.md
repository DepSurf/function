# Function: <code>usleep_range_state</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void usleep_range_state(long unsigned int min, long unsigned int max, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81d560b0)
Location: kernel/time/timer.c:2068
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff81d560b0-ffffffff81d56138: usleep_range_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void usleep_range_state(long unsigned int min, long unsigned int max, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81f280a0)
Location: kernel/time/timer.c:2123
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - net/core/dev.c:napi_disable
```
**Symbols:**

```
ffffffff81f280a0-ffffffff81f28134: usleep_range_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void usleep_range_state(long unsigned int min, long unsigned int max, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff820d3c80)
Location: kernel/time/timer.c:2354
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
  - net/core/dev.c:napi_disable
```
**Symbols:**

```
ffffffff820d3c80-ffffffff820d3d14: usleep_range_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void usleep_range_state(long unsigned int min, long unsigned int max, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff82157f00)
Location: kernel/time/timer.c:2354
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/cpu.c:cpuhp_wait_for_sync_state
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
  - net/core/dev.c:napi_disable
```
**Symbols:**

```
ffffffff82157f00-ffffffff82157f94: usleep_range_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void usleep_range_state(long unsigned int min, long unsigned int max, unsigned int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8223ad70)
Location: kernel/time/timer.c:2370
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/cpu.c:cpuhp_wait_for_sync_state
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_up
  - drivers/mmc/core/core.c:mmc_power_up
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
  - net/core/dev.c:napi_disable
```
**Symbols:**

```
ffffffff8223ad70-ffffffff8223ae04: usleep_range_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
