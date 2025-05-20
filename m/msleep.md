# Function: <code>msleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ec6f0)
Location: kernel/time/timer.c:1673
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup.c:cgroup_mount
  - block/blk-core.c:__blk_drain_queue
  - block/blk-iopoll.c:blk_iopoll_disable
  - block/blk-cgroup.c:blkg_conf_prep
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_ctx
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm_tis.c:get_burstcount
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_hotplug
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_exit
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/dev.c:netdev_run_todo
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff810ec6f0-ffffffff810ec725: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f3d80)
Location: kernel/time/timer.c:1874
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup.c:cgroup_mount
  - block/blk-core.c:__blk_drain_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_hotplug
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_get_hwparams
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff810f3d80-ffffffff810f3db5: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810faf30)
Location: kernel/time/timer.c:1879
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - block/blk-core.c:__blk_drain_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_hotplug
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff810faf30-ffffffff810faf66: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fdf40)
Location: kernel/time/timer.c:1869
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - fs/ext4/ioctl.c:ext4_ioctl
  - block/blk-core.c:__blk_drain_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/probe.c:pci_bus_read_dev_vendor_id
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
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
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_hotplug
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff810fdf40-ffffffff810fdf76: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811087f0)
Location: kernel/time/timer.c:1940
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - mm/vmscan.c:shrink_inactive_list
  - fs/ext4/ioctl.c:ext4_ioctl
  - block/blk-core.c:__blk_drain_queue
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_flr_wait
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_hotplug
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff811087f0-ffffffff81108824: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81113ad0)
Location: kernel/time/timer.c:1951
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pcie_flr
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_lib.c:device_block
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_hotplug
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff81113ad0-ffffffff81113b04: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81120330)
Location: kernel/time/timer.c:1950
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_hotplug
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/net/phy/phy_device.c:genphy_soft_reset
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff81120330-ffffffff81120364: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112ac20)
Location: kernel/time/timer.c:1954
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_hotplug
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff8112ac20-ffffffff8112ac59: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81136bc0)
Location: kernel/time/timer.c:2043
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff81136bc0-ffffffff81136bf9: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81144a20)
Location: kernel/time/timer.c:2064
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - fs/efivarfs/file.c:efivarfs_file_read
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/base/core.c:online_store
  - drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_handle_remote_wakeup
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:wait_for_connected
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:io_job_start
  - drivers/mmc/core/mmc.c:mmc_sleep
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff81144a20-ffffffff81144a5c: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141de0)
Location: kernel/time/timer.c:2027
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - fs/efivarfs/file.c:efivarfs_file_read
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:board_added
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:sriov_restore_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/iommu/amd/init.c:init_iommu_perf_ctr
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/base/core.c:online_store
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/mfd/arizona-core.c:wm5102_clear_write_sequencer
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_device.c:phy_poll_reset
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_handle_remote_wakeup
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:wait_for_connected
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_clear_force_mode
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:io_job_start
  - drivers/mmc/core/mmc.c:mmc_sleep
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_wait_allrefs
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff81141de0-ffffffff81141e1c: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81142be0)
Location: kernel/time/timer.c:2045
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - fs/efivarfs/file.c:efivarfs_file_read
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/base/core.c:online_store
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff81142be0-ffffffff81142c1c: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81166190)
Location: kernel/time/timer.c:2031
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - fs/efivarfs/file.c:efivarfs_file_read
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_wait_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/base/core.c:online_store
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/pci-quirks.c:ehci_bios_handoff
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pll_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff81166190-ffffffff811661cb: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199d10)
Location: kernel/time/timer.c:2086
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - kernel/printk/printk.c:__pr_flush
  - kernel/printk/printk.c:__pr_flush
  - kernel/printk/printk.c:__pr_flush
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_pm_reset
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/base/core.c:online_store
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pll_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff81199d10-ffffffff81199d53: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d83c0)
Location: kernel/time/timer.c:2317
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func
  - fs/efivarfs/file.c:efivarfs_file_read
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_dev_wait
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/base/core.c:online_store
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pll_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff811d83c0-ffffffff811d8403: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ec7f0)
Location: kernel/time/timer.c:2317
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - kernel/power/hibernate.c:find_resume_device
  - kernel/power/hibernate.c:find_resume_device
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func
  - fs/efivarfs/file.c:efivarfs_file_read
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link_status
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_dev_wait
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/base/core.c:online_store
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pll_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff811ec7f0-ffffffff811ec833: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81202810)
Location: kernel/time/timer.c:2333
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - kernel/power/hibernate.c:find_resume_device
  - kernel/power/hibernate.c:find_resume_device
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_device
  - kernel/printk/printk.c:console_unblank
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func
  - fs/efivarfs/file.c:efivarfs_file_read
  - block/blk-mq.c:blk_mq_hctx_notify_offline
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link
  - drivers/pci/pci.c:pcie_wait_for_link_status
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_dev_wait
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:nvme_disable_and_flr
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/xen/grant-table.c:gnttab_batch_copy
  - drivers/xen/grant-table.c:gnttab_batch_map
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_set_ref_clk
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/base/core.c:online_store
  - drivers/base/cpu.c:cpu_subsys_online
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy.c:phy_speed_down
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ehci-hcd.c:ehci_handover_companion_ports
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/core.c:mmc_power_up
  - drivers/mmc/core/core.c:mmc_power_up
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - net/core/dev.c:netdev_wait_allrefs_any
  - net/core/netpoll.c:netpoll_setup
```
**Symbols:**

```
ffffffff81202810-ffffffff81202853: msleep (STB_GLOBAL)
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
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019f0f8)
Location: kernel/time/timer.c:2043
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/video/fbdev/amba-clcd.c:clcdfb_enable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
  - drivers/video/fbdev/mx3fb.c:__blank
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/clk/mvebu/armada-37xx-periph.c:clk_pm_cpu_set_rate
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_wait_for_bb
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/thermal/armada_thermal.c:armada_overheat_isr_thread
  - drivers/thermal/armada_thermal.c:armada375_init
  - drivers/thermal/armada_thermal.c:armada375_init
  - drivers/thermal/armada_thermal.c:armada370_init
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
  - drivers/memory/brcmstb_dpfe.c:__send_command
  - drivers/memory/brcmstb_dpfe.c:__send_command
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffff80001019f0f8-ffff80001019f140: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e8fc8)
Location: kernel/time/timer.c:2043
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/arm/kernel/psci_smp.c:psci_cpu_kill
  - arch/arm/mach-hisi/platmcpm.c:hip04_cpu_kill
  - arch/arm/mach-meson/platsmp.c:meson8_smp_cpu_kill
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3x_usb_hub_init
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_host_init
  - drivers/video/fbdev/amba-clcd.c:clcdfb_enable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
  - drivers/video/fbdev/mx3fb.c:__blank
  - drivers/video/fbdev/mx3fb.c:sdc_enable_channel
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel
  - drivers/dma/ipu/ipu_idmac.c:ipu_disable_channel
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/sm501.c:sm501_set_power
  - drivers/mfd/sm501.c:sm501_set_clock
  - drivers/mfd/sm501.c:sm501_unit_power
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/sata_highbank.c:ahci_highbank_hardreset
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset
  - drivers/auxdisplay/arm-charlcd.c:charlcd_init_work
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_charger_detect
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_resume
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_sm501_resume
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_wait_for_bb
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/thermal/armada_thermal.c:armada_overheat_isr_thread
  - drivers/thermal/armada_thermal.c:armada375_init
  - drivers/thermal/armada_thermal.c:armada375_init
  - drivers/thermal/armada_thermal.c:armada370_init
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/host/sdhci.c:sdhci_get_ro
  - sound/soc/soc-ac97.c:snd_soc_ac97_reset
  - sound/soc/soc-ac97.c:snd_soc_ac97_warm_reset
  - sound/soc/codecs/sgtl5000.c:vag_and_mute_control
  - sound/soc/codecs/sgtl5000.c:vag_and_mute_control
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
c03e8fc8-c03e9010: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001ffe20)
Location: kernel/time/timer.c:2043
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/powerpc/kernel/rtas.c:rtas_busy_delay
  - arch/powerpc/kernel/rtas-rtc.c:rtas_set_rtc_time
  - arch/powerpc/kernel/rtas-rtc.c:rtas_get_rtc_time
  - arch/powerpc/kernel/eeh_pe.c:eeh_bridge_check_link
  - arch/powerpc/kernel/eeh_pe.c:eeh_bridge_check_link
  - arch/powerpc/kernel/eeh_pe.c:eeh_bridge_check_link
  - arch/powerpc/kernel/eeh_pe.c:eeh_wait_state
  - arch/powerpc/kernel/eeh_driver.c:eeh_reset_device
  - arch/powerpc/kernel/smp.c:__cpu_up
  - arch/powerpc/kernel/smp.c:generic_cpu_die
  - arch/powerpc/sysdev/xive/native.c:xive_native_disable_vp
  - arch/powerpc/sysdev/xive/native.c:xive_native_enable_vp
  - arch/powerpc/sysdev/xive/native.c:xive_native_alloc_vp_block
  - arch/powerpc/sysdev/xive/native.c:xive_native_teardown_cpu
  - arch/powerpc/sysdev/xive/native.c:xive_native_setup_cpu
  - arch/powerpc/sysdev/xive/native.c:xive_native_free_irq
  - arch/powerpc/sysdev/xive/native.c:xive_native_alloc_irq
  - arch/powerpc/sysdev/xive/native.c:xive_native_get_ipi
  - arch/powerpc/sysdev/xive/native.c:xive_native_configure_queue
  - arch/powerpc/sysdev/xive/native.c:xive_native_configure_irq
  - arch/powerpc/platforms/powernv/opal.c:opal_flush_chars
  - arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_write
  - arch/powerpc/platforms/powernv/opal-nvram.c:opal_nvram_write
  - arch/powerpc/platforms/powernv/opal-flash.c:opal_flash_update_print_message
  - arch/powerpc/platforms/powernv/opal-dump.c:dump_attr_read
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_reset
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_reset
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_reset
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_reset
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_bridge_reset
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_bridge_reset
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_phb_reset
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_phb_reset
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_poll
  - arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt
  - arch/powerpc/platforms/pseries/mobility.c:migration_store
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_reset
  - arch/powerpc/platforms/pseries/eeh_pseries.c:pseries_eeh_reset
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_cpu_die
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/video/fbdev/gxt4500.c:gxt4500_set_par
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_resume
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/rtc/rtc-opal.c:opal_set_rtc_time
  - drivers/rtc/rtc-opal.c:opal_set_rtc_time
  - drivers/rtc/rtc-opal.c:opal_set_rtc_time
  - drivers/rtc/rtc-opal.c:opal_get_rtc_time
  - drivers/rtc/rtc-opal.c:opal_get_rtc_time
  - drivers/rtc/rtc-opal.c:opal_get_rtc_time
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
c0000000001ffe20-c0000000001ffe88: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012dab0)
Location: kernel/time/timer.c:2043
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pwm/pwm-stmpe.c:stmpe_24xx_pwm_config
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/host/mmc_spi.c:mmc_spi_set_ios
  - drivers/mmc/host/mmc_spi.c:mmc_spi_set_ios
  - drivers/mmc/host/mmc_spi.c:mmc_spi_set_ios
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffe00012dab0-ffffffe00012daf4: msleep (STB_GLOBAL)
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
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112f370)
Location: kernel/time/timer.c:2043
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/block/xen-blkfront.c:blkfront_freeze
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/core.c:nvme_shutdown_ctrl
  - drivers/nvme/host/core.c:nvme_wait_ready
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff8112f370-ffffffff8112f3a9: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81121df0)
Location: kernel/time/timer.c:2043
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/scsi_transport_fc.c:fc_block_rport
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/core.c:nvme_shutdown_ctrl
  - drivers/nvme/host/core.c:nvme_wait_ready
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - drivers/hv/vmbus_drv.c:vmbus_bus_suspend
  - drivers/hv/connection.c:vmbus_post_msg
  - drivers/hv/channel_mgmt.c:vmbus_onoffer_rescind
  - drivers/hv/channel_mgmt.c:vmbus_onoffer_rescind
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff81121df0-ffffffff81121e29: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112d090)
Location: kernel/time/timer.c:2043
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff8112d090-ffffffff8112d0c9: msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void msleep(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81138e20)
Location: kernel/time/timer.c:2043
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:prepare_namespace
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - mm/vmscan.c:shrink_inactive_list
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
  - block/blk-cgroup.c:blkg_conf_prep
  - lib/irq_poll.c:irq_poll_disable
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_reset_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pcie_wait_for_link_delay
  - drivers/pci/pci.c:pci_af_flr
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_wait_for_pending
  - drivers/pci/quirks.c:quirk_apple_poweroff_thunderbolt
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
  - drivers/pci/pcie/dpc.c:dpc_reset_link
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_ctrl.c:board_added
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/pci/iov.c:pci_restore_iov_state
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
  - drivers/pci/iov.c:sriov_enable
  - drivers/acpi/osl.c:acpi_os_sleep
  - drivers/acpi/bus.c:sb_notify_work
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_activate
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_notify
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/8250/8250_pci.c:pci_xircom_init
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max14830_power
  - drivers/tty/serial/max310x.c:max310x_power
  - drivers/connector/cn_queue.c:cn_queue_free_dev
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
  - drivers/scsi/scsi_scan.c:do_scsi_scan_host
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/ata/libata-core.c:ata_msleep
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_port_power_cycle
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/message.c:usb_control_msg
  - drivers/usb/core/config.c:usb_get_configuration
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/core.c:dwc2_force_dr_mode
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_endpoint_disable
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_port_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/host/ehci-hcd.c:ehci_resume
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:set_owner
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_resume
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_resume
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_init
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_bus_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_resume
  - drivers/usb/host/ohci-hcd.c:ohci_rh_suspend
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_resume
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_selftest
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_do_sync
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm-kcopyd.c:run_io_job
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_send_msg
  - net/core/dev.c:netdev_run_todo
  - net/core/dev.c:napi_disable
  - net/core/dev.c:napi_disable
  - net/core/netpoll.c:netpoll_setup
  - net/core/netpoll.c:netpoll_setup
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff81138e20-ffffffff81138e59: msleep (STB_GLOBAL)
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
