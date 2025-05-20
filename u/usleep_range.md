# Function: <code>usleep_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff818232f0)
Location: kernel/time/timer.c:1713
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff818232f0-ffffffff81823355: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8189dd70)
Location: kernel/time/timer.c:1920
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/access.c:pci_vpd_wait
  - drivers/pci/host/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff8189dd70-ffffffff8189ddd5: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff818d2c00)
Location: kernel/time/timer.c:1915
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/access.c:pci_vpd_wait
  - drivers/pci/host/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/host/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff818d2c00-ffffffff818d2c83: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81909e10)
Location: kernel/time/timer.c:1905
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/access.c:pci_vpd_wait
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu_unroll
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff81909e10-ffffffff81909e93: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81994150)
Location: kernel/time/timer.c:1976
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/access.c:pci_vpd_wait
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff81994150-ffffffff819941d2: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff819f06d0)
Location: kernel/time/timer.c:1987
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff819f06d0-ffffffff819f0752: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a2ba50)
Location: kernel/time/timer.c:1986
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff81a2ba50-ffffffff81a2bad2: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a9bc80)
Location: kernel/time/timer.c:1990
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff81a9bc80-ffffffff81a9bd06: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81ad35d0)
Location: kernel/time/timer.c:2079
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff81ad35d0-ffffffff81ad3656: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81bcb6e0)
Location: kernel/time/timer.c:2100
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pwm/pwm-lpss.c:pwm_lpss_wait_for_update
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:mmc_sleep
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
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
ffffffff81bcb6e0-ffffffff81bcb766: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81c44580)
Location: kernel/time/timer.c:2063
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
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
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_down_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/platform.c:dwc2_resume
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
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:mmc_sleep
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
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
ffffffff81c44580-ffffffff81c44606: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81c377f0)
Location: kernel/time/timer.c:2081
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
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/platform.c:dwc2_resume
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
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
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
ffffffff81c377f0-ffffffff81c37876: usleep_range (STB_GLOBAL)
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810a965a)
Location: include/linux/delay.h:65
Inline: True
```
```
In kernel/power/process.c (ffffffff811308a1)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81696678)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/pci/vpd.c (ffffffff816aafc8)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816cfe06)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8176339d)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff8176c07b)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
```
```
In drivers/regulator/core.c (ffffffff817a7231)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_enable_delay
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff818043f2)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8180543f)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180b518)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8180bf33)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81863e3c)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/misc/sram.c (ffffffff818772e0)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/twl6040.c (ffffffff8187f7c2)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
```
```
In drivers/ata/libata-core.c (ffffffff818d22ce)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/spi/spi.c (ffffffff818f8ff9)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
```
```
In drivers/spi/spi-mem.c (ffffffff818ffb05)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff8190571c)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81908924)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81908e05)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190af5c)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff8193baf5)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
```
```
In drivers/usb/core/hcd.c (ffffffff81943ddc)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
```
```
In drivers/usb/dwc2/core.c (ffffffff819580fe)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff8195c5df)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81966a3c)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197be66)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff819922c8)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff819a4821)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d5462)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d66fa)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff819db620)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/mmc/core/core.c (ffffffff81a3b919)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff81a3e303)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81a41b59)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81a44848)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81a46dc7)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81a57713)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81a58afc)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810bef4c)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
```
```
In kernel/power/process.c (ffffffff811520a6)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/pwm/pwm-lpss.c (ffffffff817b7518)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/pci/vpd.c (ffffffff817ce006)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f8bd6)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff818972f1)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff818a0f14)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
```
```
In drivers/regulator/core.c (ffffffff818e1791)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_delay_helper
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81943d75)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81944ebf)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194b968)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8194c503)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff819ac013)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/misc/sram.c (ffffffff819bf53c)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/twl6040.c (ffffffff819c7dae)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
```
```
In drivers/ata/libata-core.c (ffffffff81a229ad)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81a4a4a6)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
```
```
In drivers/spi/spi-mem.c (ffffffff81a510d1)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5802a)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81a5bc82)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81a5c383)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e45a)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81a937cd)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
```
```
In drivers/usb/core/hcd.c (ffffffff81a9c22a)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
```
```
In drivers/usb/dwc2/core.c (ffffffff81ab1f5e)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ab6647)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ac0be8)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad455c)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff81aeed55)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81b02215)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37e8a)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39202)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81b3a32b)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81b3f087)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/mmc/core/core.c (ffffffff81ba88a1)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff81bab5cc)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81baf258)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81bb2368)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81bb4bc7)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81bc71e5)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc885b)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
```
In net/core/dev.c (ffffffff81c0d1cc)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810dab86)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
```
```
In kernel/power/process.c (ffffffff81180eb3)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/pwm/pwm-lpss.c (ffffffff818d1bdb)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/pci/pci.c (ffffffff818def56)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
```
```
In drivers/pci/vpd.c (ffffffff818ed9e2)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8192517d)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df03c)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff819ea504)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
```
```
In drivers/regulator/core.c (ffffffff81a36971)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_delay_helper
```
```
In drivers/reset/reset-simple.c (ffffffff81a47a1a)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa699a)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa7e5f)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aaf4e1)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab06b3)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81b1f5e3)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/misc/sram.c (ffffffff81b34cdc)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/twl6040.c (ffffffff81b3ee37)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
```
```
In drivers/ata/libata-core.c (ffffffff81ba417d)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81bd1216)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
```
```
In drivers/spi/spi-mem.c (ffffffff81bda2d1)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81be1dc6)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81be6707)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81be6e13)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be9198)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c15a0d)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
```
```
In drivers/usb/core/hcd.c (ffffffff81c2116c)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
```
```
In drivers/usb/dwc2/core.c (ffffffff81c3a59a)
Location: include/linux/delay.h:65
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81c3f017)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c4a7a8)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5f1af)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff81c7bd87)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c9123b)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb408f)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd4ca)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccebba)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81ccfd6b)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81cd5467)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/mmc/core/core.c (ffffffff81d4b121)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff81d4e914)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81d52c36)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81d56628)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81d592a7)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81d6fcd5)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d71991)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
```
```
In net/core/dev.c (ffffffff81dbcddd)
Location: include/linux/delay.h:65
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810e6116)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
```
```
In kernel/power/process.c (ffffffff81191da3)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81914bcb)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/pci/pci.c (ffffffff819223b6)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
```
```
In drivers/pci/vpd.c (ffffffff81930ee2)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81968ecd)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a26d4c)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff81a32c24)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
```
```
In drivers/regulator/core.c (ffffffff81a80441)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_delay_helper
```
```
In drivers/reset/reset-simple.c (ffffffff81a91bba)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81af21e5)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af368f)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afb3b6)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81afc503)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81b6e7e3)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/misc/sram.c (ffffffff81b881bc)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/twl6040.c (ffffffff81b92193)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
```
```
In drivers/ata/libata-core.c (ffffffff81bfa87d)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81c28e86)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
```
```
In drivers/spi/spi-mem.c (ffffffff81c30cc1)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81c396ba)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81c3df8f)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81c3f173)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c415c6)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c7c81d)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
```
```
In drivers/usb/core/hcd.c (ffffffff81c880ec)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
```
```
In drivers/usb/dwc2/core.c (ffffffff81ca194a)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ca65b4)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cb1dc1)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc66e8)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff81ce2ff6)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81cf7948)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1b6df)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d3523a)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d36c51)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81d3d0f7)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/md/dm-init.c (ffffffff83726573)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
```
```
In drivers/md/dm.c (ffffffff81d77ba3)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81db59d1)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff81db922e)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbd5e6)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81dc0f98)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81dc3c57)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81ddd992)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81ddf671)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
```
```
In net/core/dev.c (ffffffff81e2d60d)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
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
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810ee509)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
```
```
In kernel/power/process.c (ffffffff811a0793)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8195cb3b)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8196a916)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
```
```
In drivers/pci/vpd.c (ffffffff81979912)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_wait
```
```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b27fd)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4b45)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a71d5c)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/acpi/pmic/intel_pmic_xpower.c (ffffffff81a7e094)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_get_raw_temp
```
```
In drivers/regulator/core.c (ffffffff81ad29e1)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/regulator/core.c:_regulator_delay_helper
```
```
In drivers/reset/reset-simple.c (ffffffff81ae454a)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff81b45775)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b46c1f)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4ea46)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81b4fb13)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff81bc23e3)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
```
```
In drivers/misc/sram.c (ffffffff81bdc06c)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/twl6040.c (ffffffff81be6133)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
  - drivers/mfd/twl6040.c:twl6040_power_up_manual
```
```
In drivers/ata/libata-core.c (ffffffff81c5031d)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81cdb5d6)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi.c:spi_delay_exec
```
```
In drivers/spi/spi-mem.c (ffffffff81ce3b51)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81ceea4a)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81cf3495)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
```
In drivers/net/phy/mdio_device.c (ffffffff81cf4732)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_reset
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6c56)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d3146d)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
```
```
In drivers/usb/core/hcd.c (ffffffff81d3cb3c)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:hcd_bus_resume
```
```
In drivers/usb/dwc2/core.c (ffffffff81d5659a)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81d5b204)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d66ad1)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7b5ca)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
```
```
In drivers/usb/host/xhci.c (ffffffff81d98148)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_suspend
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81dad278)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd142f)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb3ca)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81deca11)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:amd_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81df3a47)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/md/dm-init.c (ffffffff8395a466)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
```
```
In drivers/md/dm.c (ffffffff81e2edd3)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/delay.h:66
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81e6de21)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
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
```
```
In drivers/mmc/core/mmc.c (ffffffff81e7177e)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81e75c16)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81e798d8)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81e7c537)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e9382f)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e955a1)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
```
```
In net/core/dev.c (ffffffff81eeb90d)
Location: include/linux/delay.h:66
Inline: True
Inline callers:
  - net/core/dev.c:napi_disable
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
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff800010da6278)
Location: kernel/time/timer.c:2079
Inline: False
Direct callers:
  - arch/arm64/kernel/psci.c:cpu_psci_cpu_kill
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_force_lat_summer_cal
  - drivers/phy/phy-xgene.c:xgene_phy_force_lat_summer_cal
  - drivers/phy/phy-xgene.c:xgene_phy_force_lat_summer_cal
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_setup_hw
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_bridge_init
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_host_init
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_pd_power_on
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_reset
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_assert
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable_stall
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable_stall
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_phy_crbit_assert
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/phy/mdio-mux-bcm-iproc.c:iproc_mdio_wait_for_idle
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setalarm
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffff800010da6278-ffff800010da6320: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0e9de6c)
Location: kernel/time/timer.c:2079
Inline: False
Direct callers:
  - arch/arm/mach-meson/platsmp.c:meson8_smp_cpu_kill
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:sata_phy_power_on
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:pcie_phy_power_on
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_exit
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_exit
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_init
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_phy_init
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_port_reset
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_establish_link
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_wait_lock
  - drivers/clk/ti/adpll.c:ti_adpll_prepare
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_genpd_power_off
  - drivers/soc/tegra/pmc.c:tegra_genpd_power_off
  - drivers/soc/tegra/pmc.c:tegra_genpd_power_off
  - drivers/soc/tegra/pmc.c:tegra_genpd_power_off
  - drivers/soc/tegra/pmc.c:tegra_genpd_power_off
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_deassert
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_control_assert
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/asic3.c:asic3_leds_suspend
  - drivers/mfd/asic3.c:asic3_mmc_enable
  - drivers/mfd/asic3.c:asic3_mmc_enable
  - drivers/mfd/asic3.c:ds1wm_enable
  - drivers/mfd/asic3.c:ds1wm_enable
  - drivers/mfd/asic3.c:ds1wm_enable
  - drivers/mfd/asic3.c:ds1wm_enable
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx_phy_crbit_assert
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/cpsw_sl.c:cpsw_sl_wait_for_idle
  - drivers/net/ethernet/ti/cpsw_sl.c:cpsw_sl_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_start
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_wait_idle
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_message_start
  - drivers/thermal/armada_thermal.c:armada_wait_sensor_validity
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
  - drivers/mmc/host/sdhci.c:sdhci_start_signal_voltage_switch
  - drivers/platform/chrome/cros_ec_proto.c:send_command
  - drivers/memory/tegra/mc.c:tegra_mc_hotreset_assert
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
```
**Symbols:**

```
c0e9de6c-c0e9df14: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c000000000ee8820)
Location: kernel/time/timer.c:2079
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_send
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_recv
  - drivers/char/tpm/tpm_i2c_infineon.c:wait_for_stat
  - drivers/char/tpm/tpm_i2c_infineon.c:get_burstcount
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_write_generic
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_write_generic
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_write_generic
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
  - drivers/char/tpm/tpm_i2c_infineon.c:iic_tpm_read
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_get_burstcount
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_write_status
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
**Symbols:**

```
c000000000ee8820-c000000000ee88ec: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe0008c8606)
Location: kernel/time/timer.c:2079
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_disable_reset
  - drivers/mfd/arizona-core.c:arizona_poll_reg
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffffffe0008c8606-ffffffe0008c8668: usleep_range (STB_GLOBAL)
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
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a72440)
Location: kernel/time/timer.c:2079
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff81a72440-ffffffff81a724c6: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a2e810)
Location: kernel/time/timer.c:2079
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81a2e810-ffffffff81a2e896: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81ade850)
Location: kernel/time/timer.c:2079
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff81ade850-ffffffff81ade8d6: usleep_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void usleep_range(long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81aeacd0)
Location: kernel/time/timer.c:2079
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/pci/vpd.c:pci_vpd_wait
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/sram.c:atmel_securam_wait
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/spi/spi.c:spi_stop_queue
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/dwc2/core.c:dwc2_wait_for_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/chrome/cros_ec_proto.c:send_command
```
**Symbols:**

```
ffffffff81aeacd0-ffffffff81aead56: usleep_range (STB_GLOBAL)
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
