# Function: <code>_msecs_to_jiffies</code>

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
In arch/x86/events/intel/cqm.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/time/time.c (ffffffff810eace7)
Location: include/linux/jiffies.h:299
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/deadline-iosched.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/video/console/fbcon.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/misc/bmp085.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/power/power_supply_core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/power/charger-manager.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:299
Inline: True
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
In arch/x86/events/intel/cqm.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In kernel/time/time.c (ffffffff810f1975)
Location: include/linux/jiffies.h:299
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In block/deadline-iosched.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/video/console/fbcon.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/power/power_supply_core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/power/charger-manager.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:299
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:299
Inline: True
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
In arch/x86/events/intel/cqm.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In kernel/time/time.c (ffffffff810f8af5)
Location: include/linux/jiffies.h:303
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In block/deadline-iosched.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/video/console/fbcon.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:303
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:303
Inline: True
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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In kernel/time/time.c (ffffffff810fab27)
Location: include/linux/jiffies.h:304
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In block/deadline-iosched.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/video/console/fbcon.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:304
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:304
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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In kernel/time/time.c (ffffffff811054b7)
Location: include/linux/jiffies.h:305
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In block/deadline-iosched.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/pci/access.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:305
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:305
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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/time/time.c (ffffffff81110317)
Location: include/linux/jiffies.h:308
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/deadline-iosched.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/power/runtime.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:308
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
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/time/time.c (ffffffff8111b907)
Location: include/linux/jiffies.h:308
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:308
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
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/time/time.c (ffffffff81126337)
Location: include/linux/jiffies.h:309
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/soundwire/stream.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/time/time.c (ffffffff811322d7)
Location: include/linux/jiffies.h:309
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In kernel/time/time.c (ffffffff81141747)
Location: include/linux/jiffies.h:307
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/platform/x86/intel_scu_ipc.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:307
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:307
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/time/time.c (ffffffff8113d957)
Location: include/linux/jiffies.h:308
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/platform/x86/intel_scu_ipc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/time/time.c (ffffffff8113eba7)
Location: include/linux/jiffies.h:308
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/platform/x86/intel_scu_ipc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/time/time.c (ffffffff81162037)
Location: include/linux/jiffies.h:308
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/disk-events.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/irq_helpers.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/time/time.c (ffffffff81194f67)
Location: include/linux/jiffies.h:308
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/disk-events.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/irq_helpers.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/time/time.c (ffffffff811d2cc7)
Location: include/linux/jiffies.h:308
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In security/apparmor/notify.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/disk-events.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/irq_helpers.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In kernel/time/time.c (ffffffff811e6fb7)
Location: include/linux/jiffies.h:308
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In security/apparmor/notify.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/disk-events.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/regulator/irq_helpers.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/devlink/health.c (0)
Location: include/linux/jiffies.h:308
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:308
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In kernel/reboot.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In kernel/rcu/update.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/jiffies.h:458
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In mm/kfence/core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In security/apparmor/notify.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In block/disk-events.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In io_uring/sqpoll.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/regulator/irq_helpers.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/gpu/drm/drm_vblank.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_helper.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/gpu/drm/drm_self_refresh_helper.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/devlink/health.c (0)
Location: include/linux/jiffies.h:458
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:458
Inline: True
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
In arch/arm64/kernel/psci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/arm64/kernel/smp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/jiffies.h:309
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/bus/fsl-mc/mc-sys.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/controller/pci-aardvark.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/amba/bus.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/clk/imx/clk-busy.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/clk/imx/clk-pllv3.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/soc/qcom/rpmh.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/8250/8250_fsl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libahci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/net/ethernet/smsc/smc91x.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/rtc/rtc-sun6i.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/busses/i2c-omap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/firmware/ti_sci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/firmware/arm_scmi/driver.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/firmware/imx/imx-scu.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/pl320-ipc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:309
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
In arch/arm/kernel/smp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/arm/mach-hisi/hotplug.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/arm/mach-imx/src.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/arm/mach-imx/hotplug.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/arm/mach-omap2/omap_phy_internal.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/arm/mach-tegra/platsmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/time/time.c (c03e4748)
Location: include/linux/jiffies.h:309
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pinctrl/tegra/pinctrl-tegra-xusb.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/controller/pci-tegra.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/amba/bus.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/clk/imx/clk-busy.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/clk/imx/clk-pllv3.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/clk/samsung/clk-cpu.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/clk/tegra/clk-pll.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/soc/tegra/pmc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/8250/8250_fsl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libahci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mtd/nand/raw/nand_base.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mtd/nand/raw/nand_legacy.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mtd/nand/raw/omap2.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/net/ethernet/ti/cpts.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/net/ethernet/ti/cpsw_sl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/auxdisplay/arm-charlcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/musb/musb_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/musb/musb_virthub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/musb/musb_gadget.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/busses/i2c-imx.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/busses/i2c-omap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/host/sdhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/host/omap_hsmmc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/host/cqhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/firmware/arm_scmi/driver.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/firmware/imx/imx-scu.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/pl320-ipc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/tegra-hsp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In sound/core/pcm_native.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In sound/core/pcm_lib.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In sound/soc/soc-dapm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In sound/soc/soc-jack.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In sound/soc/soc-pcm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In sound/soc/soc-compress.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
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
In arch/powerpc/platforms/powernv/opal.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/powerpc/platforms/powernv/vas-window.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/powerpc/platforms/pseries/vio.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/time/time.c (c0000000001f9fa0)
Location: include/linux/jiffies.h:309
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/8250/8250_fsl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_i2c_atmel.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_i2c_infineon.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_i2c_nuvoton.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/cpufreq/powernv-cpufreq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
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
In arch/riscv/kernel/smpboot.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/time/time.c (ffffffe00012a20a)
Location: include/linux/jiffies.h:309
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/host/mmc_spi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/time/time.c (ffffffff8112aa87)
Location: include/linux/jiffies.h:309
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/nvme/host/lightnvm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/time/time.c (ffffffff8111d2f7)
Location: include/linux/jiffies.h:309
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/nvme/host/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/time/time.c (ffffffff811287a7)
Location: include/linux/jiffies.h:309
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sysctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/power/process.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In kernel/time/time.c (0)
Location: include/linux/jiffies.h:309
Inline: True
Inline callers:
  - kernel/time/time.c:__msecs_to_jiffies
```
```
In kernel/time/timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/genhd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In block/mq-deadline.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In lib/random32.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt_ioctl.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/serio/libps2.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_metrics.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv4/tcp_cubic.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:309
Inline: True
```
</details>
</li>
</ul>

## Differences
