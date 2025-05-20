# Function: <code>__const_udelay</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff813f64d0)
Location: arch/x86/lib/delay.c:157
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__udelay
  - arch/x86/lib/delay.c:__ndelay
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcu.c:try_check_zero
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - drivers/pci/access.c:pci_vpd_pci22_wait
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:wait_on_sem
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/base/power/trace.c:early_resume_init
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_host_init
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_hub_control
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/i2c/i2c-core.c:i2c_generic_recovery
  - drivers/i2c/i2c-core.c:i2c_generic_recovery
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
**Symbols:**

```
ffffffff813f64d0-ffffffff813f64fd: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8143d115)
Location: arch/x86/lib/delay.c:157
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcu.c:try_check_zero
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:wait_on_sem
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core.c:i2c_generic_recovery
  - drivers/i2c/i2c-core.c:i2c_generic_recovery
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
**Symbols:**

```
ffffffff8143d0a0-ffffffff8143d0cf: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8145a095)
Location: arch/x86/lib/delay.c:157
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcu.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:wait_on_sem
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core.c:i2c_generic_recovery
  - drivers/i2c/i2c-core.c:i2c_generic_recovery
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
**Symbols:**

```
ffffffff8145a020-ffffffff8145a04f: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff818fbdc5)
Location: arch/x86/lib/delay.c:164
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_generic_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_recovery
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff818fbd30-ffffffff818fbd6d: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81982c25)
Location: arch/x86/lib/delay.c:165
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_enter_hibernation
  - drivers/usb/dwc2/core.c:dwc2_exit_hibernation
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_generic_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_recovery
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81982b80-ffffffff81982bc3: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff819df195)
Location: arch/x86/lib/delay.c:165
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/tsc.c:native_calibrate_cpu
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:wait_for_panic
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff819df0f0-ffffffff819df138: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a1a0c5)
Location: arch/x86/lib/delay.c:165
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_link_up
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_start
  - drivers/usb/host/xhci.c:xhci_halt
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81a1a020-ffffffff81a1a068: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a89cf0)
Location: arch/x86/lib/delay.c:165
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_link_up
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
```
**Symbols:**

```
ffffffff81a89cf0-ffffffff81a89d35: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81ac0fb0)
Location: arch/x86/lib/delay.c:165
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
```
**Symbols:**

```
ffffffff81ac0fb0-ffffffff81ac0ff5: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff815fd440)
Location: arch/x86/lib/delay.c:207
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:__erst_clear_from_storage
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd/iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_irq_on
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:ehci_reset_port
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_early_setup
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/remoteproc/remoteproc_core.c:rproc_panic_handler
  - net/core/netpoll.c:__netpoll_send_skb
```
**Symbols:**

```
ffffffff815fd440-ffffffff815fd485: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81622170)
Location: arch/x86/lib/delay.c:207
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/tsc.c:pit_calibrate_tsc
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu_unroll
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/acpi/apei/erst.c:__erst_clear_from_storage
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd/iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_irq_on
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:ehci_reset_port
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery
  - drivers/i2c/i2c-core-base.c:i2c_gpio_init_generic_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/remoteproc/remoteproc_core.c:rproc_panic_handler
  - net/core/netpoll.c:__netpoll_send_skb
```
**Symbols:**

```
ffffffff81622170-ffffffff816221b5: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81605a50)
Location: arch/x86/lib/delay.c:207
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd/iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_irq_on
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/remoteproc/remoteproc_core.c:rproc_panic_handler
  - net/core/netpoll.c:__netpoll_send_skb
```
**Symbols:**

```
ffffffff81605a50-ffffffff81605a95: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81674340)
Location: arch/x86/lib/delay.c:207
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd/iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_irq_on
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_notify
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/remoteproc/remoteproc_core.c:rproc_panic_handler
  - net/core/netpoll.c:__netpoll_send_skb
```
**Symbols:**

```
ffffffff81674340-ffffffff81674385: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8178ea20)
Location: arch/x86/lib/delay.c:207
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd/iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_notify
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/remoteproc/remoteproc_core.c:rproc_panic_handler
  - net/core/netpoll.c:__netpoll_send_skb
```
**Symbols:**

```
ffffffff8178ea20-ffffffff8178ea71: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8204c3a0)
Location: arch/x86/lib/delay.c:207
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/printk/printk.c:vprintk_emit
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/dma/hsu/hsu.c:hsu_dma_get_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd/iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/remoteproc/remoteproc_core.c:rproc_panic_handler
  - net/core/netpoll.c:__netpoll_send_skb
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
```
**Symbols:**

```
ffffffff8204c3a0-ffffffff8204c3f1: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff820cacb0)
Location: arch/x86/lib/delay.c:207
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smpboot.c:smp_kick_mwait_play_dead
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/printk/printk.c:vprintk_emit
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/dma/hsu/hsu.c:hsu_dma_get_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
  - drivers/iommu/amd/iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd/iommu.c:iommu_poll_ppr_log
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/spi/spi.c:spi_transfer_cs_change_delay_exec
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/remoteproc/remoteproc_core.c:rproc_panic_handler
  - net/core/netpoll.c:__netpoll_send_skb
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
```
**Symbols:**

```
ffffffff820cacb0-ffffffff820cad01: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff821a54f0)
Location: arch/x86/lib/delay.c:207
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_check_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tboot.c:tboot_dying_cpu
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_end
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:mce_start
  - arch/x86/kernel/cpu/mce/core.c:wait_for_panic
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smpboot.c:smp_kick_mwait_play_dead
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/io_apic.c:unlock_ExtINT_logic
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/printk/printk.c:vprintk_emit
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_getchar
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - drivers/pci/pci.c:pci_restore_config_space_range
  - drivers/pci/pci.c:pci_set_low_power_state
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_ep_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_prog_outbound_atu
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/dma/hsu/hsu.c:hsu_dma_get_status
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_lsr
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
  - drivers/iommu/amd/iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd/iommu.c:iommu_poll_ppr_log
  - drivers/iommu/amd/iommu.c:iommu_print_event
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_thaw
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/spi/spi.c:spi_transfer_cs_change_delay_exec
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_core_reset
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core.c:dwc2_restore_essential_regs
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_lpm_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_clock_gating
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_partial_power_down
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_disable_ehci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_ohci
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_handshake_check_state
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:early_ehci_bios_handoff
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_controller_init
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_kbd_write
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:__i8042_command
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_avoid_UIP
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
  - drivers/thermal/intel/intel_hfi.c:hfi_disable
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/remoteproc/remoteproc_core.c:rproc_panic_handler
  - net/core/netpoll.c:__netpoll_send_skb
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
```
**Symbols:**

```
ffffffff821a54f0-ffffffff821a5539: __const_udelay (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/lib/delay.c (ffff800010d828d0)
Location: arch/arm64/lib/delay.c:43
Inline: True
Inline callers:
  - arch/arm64/lib/delay.c:__ndelay
  - arch/arm64/lib/delay.c:__udelay
Direct callers:
  - arch/arm64/kernel/smp.c:crash_smp_send_stop
  - arch/arm64/kernel/smp.c:smp_send_stop
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - lib/stmp_device.c:stmp_reset_block
  - lib/stmp_device.c:stmp_clear_poll_bit
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
  - drivers/irqchip/irq-gic-v3-its.c:its_wait_for_range_completion
  - drivers/bus/hisi_lpc.c:wait_lpc_idle
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pull_config_set
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pull_config_set
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_ps_hold_poweroff
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_ps_hold_restart
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_set_debounce
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_raise_irq
  - drivers/pci/controller/pci-aardvark.c:advk_pci_bridge_emul_pcie_conf_write
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_wait_for_dl
  - drivers/pci/controller/pcie-rcar.c:phy_wait_for_ack
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:s10_tlp_read_packet
  - drivers/pci/controller/pcie-altera.c:tlp_read_packet
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_raise_irq
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_raise_irq
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/video/fbdev/amba-clcd.c:clcdfb_enable
  - drivers/video/fbdev/amba-clcd.c:clcdfb_disable
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/actions/owl-reset.c:owl_reset_reset
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_prepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_prepare
  - drivers/clk/mediatek/clk-pll.c:mtk_pll_set_rate
  - drivers/clk/mediatek/clk-apmixed.c:mtk_ref2usb_tx_prepare
  - drivers/clk/meson/g12a.c:g12a_cpu_clk_mux_notifier_cb
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clk_gate_set
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_reset
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_reset
  - drivers/clk/sunxi-ng/ccu_reset.c:ccu_reset_reset
  - drivers/dma/amba-pl08x.c:pl08x_pause
  - drivers/dma/mxs-dma.c:mxs_dma_reset_chan
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
  - drivers/soc/fsl/qbman/bman.c:bman_acquire
  - drivers/soc/fsl/qbman/bman.c:bman_acquire
  - drivers/soc/fsl/qbman/bman.c:bman_release
  - drivers/soc/fsl/qbman/bman.c:bm_shutdown_pool
  - drivers/soc/fsl/qbman/bman.c:bm_shutdown_pool
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_shutdown_fq
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq_np
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq_np
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq
  - drivers/soc/fsl/qbman/qman.c:qman_query_fq
  - drivers/soc/fsl/qbman/qman.c:qman_oos_fq
  - drivers/soc/fsl/qbman/qman.c:qman_retire_fq
  - drivers/soc/fsl/qbman/qman.c:qman_schedule_fq
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
  - drivers/soc/fsl/qbman/qman.c:qm_congestion_task
  - drivers/soc/fsl/qbman/qman.c:qm_congestion_task
  - drivers/soc/fsl/qbman/qman.c:drain_mr_fqrni
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_on
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_off
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_send_data
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/reset/reset-berlin.c:berlin_reset_reset
  - drivers/reset/reset-imx7.c:imx8mq_reset_set
  - drivers/reset/reset-imx7.c:imx7_reset_set
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_out38x
  - drivers/tty/serial/imx.c:imx_uart_flush_buffer
  - drivers/tty/serial/msm_serial.c:__msm_console_write
  - drivers/tty/serial/msm_serial.c:msm_poll_put_char
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_put_poll_char
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_init
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_reset
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_reset
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_reset
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_cmdcfg_maskset
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_cmdcfg_maskset
  - drivers/net/ethernet/broadcom/bgmac-platform.c:platform_bgmac_clk_enable
  - drivers/net/ethernet/broadcom/bgmac-platform.c:platform_bgmac_clk_enable
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_read
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
  - drivers/net/ethernet/freescale/fman/fman.c:fman_reset_mac
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_port.c:init_low_level_driver
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_isr
  - drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_mii_out
  - drivers/net/ethernet/smsc/smc91x.c:smc_mii_out
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_wait
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_handshake
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:_ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
  - drivers/power/reset/gpio-poweroff.c:gpio_poweroff_do_poweroff
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
  - drivers/power/reset/gpio-restart.c:gpio_restart_notify
  - drivers/power/reset/msm-poweroff.c:do_msm_poweroff
  - drivers/power/reset/msm-poweroff.c:deassert_pshold
  - drivers/power/reset/vexpress-poweroff.c:vexpress_reset_do
  - drivers/power/reset/syscon-reboot.c:syscon_restart_handle
  - drivers/power/reset/syscon-poweroff.c:syscon_poweroff
  - drivers/md/md.c:md_notify_reboot
  - drivers/edac/altera_edac.c:altr_init_memory_port
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_dmae_finalize
  - drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_pwrreg
  - drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_pwrreg
  - drivers/clocksource/sh_cmt.c:sh_cmt_start
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
**Symbols:**

```
ffff800010d82840-ffff800010d82870: __const_udelay (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a5fe00)
Location: arch/x86/lib/delay.c:165
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_link_up
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
```
**Symbols:**

```
ffffffff81a5fe00-ffffffff81a5fe45: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a1ced0)
Location: arch/x86/lib/delay.c:165
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_link_up
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/hv/connection.c:vmbus_post_msg
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
```
**Symbols:**

```
ffffffff81a1ced0-ffffffff81a1cf15: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81acc1f0)
Location: arch/x86/lib/delay.c:165
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_link_up
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
```
**Symbols:**

```
ffffffff81acc1f0-ffffffff81acc235: __const_udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __const_udelay(long unsigned int xloops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81ad86e0)
Location: arch/x86/lib/delay.c:165
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow
  - arch/x86/kernel/irq.c:fixup_irqs
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/i8259.c:init_8259A
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu
  - arch/x86/kernel/io_delay.c:native_io_delay
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/apic/apic.c:native_safe_apic_wait_icr_idle
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/hpet.c:hpet_clkevt_set_state_periodic
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/smpboot.c:cpu_wait_death
  - kernel/power/hibernate.c:hibernation_debug_sleep
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/debug/kdb/kdb_io.c:kdb_input_flush
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_support.c:get_dap_lock
  - drivers/pci/pci.c:pci_restore_config_dword
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/quirks.c:quirk_via_vlink
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_inbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_prog_outbound_atu
  - drivers/rapidio/rio.c:rio_route_clr_table
  - drivers/rapidio/rio.c:rio_route_add_entry
  - drivers/rapidio/rio.c:rio_lock_device
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_mport_chk_dev_access
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_pci.c:sbs_init
  - drivers/char/agp/intel-gtt.c:i830_chipset_flush
  - drivers/iommu/amd_iommu.c:__iommu_queue_command_sync
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_clear
  - drivers/usb/dwc2/core.c:dwc2_hsotg_wait_bit_set
  - drivers/usb/dwc2/core.c:dwc2_flush_rx_fifo
  - drivers/usb/dwc2/core.c:dwc2_flush_tx_fifo
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_enter_partial_power_down
  - drivers/usb/dwc2/core.c:dwc2_exit_partial_power_down
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_otg_intr
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_exit_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/dwc2/hcd.c:dwc2_host_enter_hibernation
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_bus_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:io_watchdog_func
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-hcd.c:ohci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_hub_control
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/xhci.c:xhci_reset
  - drivers/usb/host/xhci.c:xhci_handshake
  - drivers/usb/early/ehci-dbgp.c:early_dbgp_init
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:_dbgp_external_startup
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_panic_blink
  - drivers/input/serio/i8042.c:i8042_toggle_aux
  - drivers/input/serio/i8042.c:i8042_port_close
  - drivers/input/serio/i8042.c:i8042_flush
  - drivers/input/serio/i8042.c:i8042_wait_write
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_power_on
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/i2c/i2c-core-base.c:i2c_generic_scl_recovery
  - drivers/md/md.c:md_notify_reboot
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
```
**Symbols:**

```
ffffffff81ad86e0-ffffffff81ad871f: __const_udelay (STB_GLOBAL)
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
