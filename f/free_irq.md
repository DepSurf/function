# Function: <code>free_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810db950)
Location: kernel/irq/manage.c:1552
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_notify
  - kernel/irq/devres.c:devm_irq_release
  - kernel/irq/devres.c:devm_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_free_vectors
  - drivers/virtio/virtio_pci_common.c:vp_free_vectors
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_del_irq_chip
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/tps65912-irq.c:tps65912_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_exit
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_free_irq
  - drivers/usb/host/xhci.c:xhci_free_irq
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff810db950-ffffffff810db9d6: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e1260)
Location: kernel/irq/manage.c:1582
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_free_vectors
  - drivers/virtio/virtio_pci_common.c:vp_free_vectors
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_free_irq
  - drivers/usb/host/xhci.c:xhci_free_irq
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff810e1260-ffffffff810e12e6: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7bd0)
Location: kernel/irq/manage.c:1582
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/base/regmap/regmap-irq.c:devm_regmap_irq_chip_release
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_free_irq
  - drivers/usb/host/xhci.c:xhci_free_irq
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff810e7bd0-ffffffff810e7c53: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7040)
Location: kernel/irq/manage.c:1627
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff810e7040-ffffffff810e70a2: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ef320)
Location: kernel/irq/manage.c:1680
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff810ef320-ffffffff810ef389: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f74b0)
Location: kernel/irq/manage.c:1724
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove
```
**Symbols:**

```
ffffffff810f74b0-ffffffff810f7512: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102e70)
Location: kernel/irq/manage.c:1740
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-core.c:wm831x_device_exit
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-core.c:wm8350_device_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_remove
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81102e70-ffffffff81102ed2: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1861
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8110d71d-ffffffff8110d752: free_irq.cold (STB_LOCAL)
ffffffff8110bbe0-ffffffff8110bc47: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81117fe0)
Location: kernel/irq/manage.c:1853
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81117fe0-ffffffff81118046: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811258a0)
Location: kernel/irq/manage.c:1892
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_remove
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/evged.c:ged_shutdown
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/serial/8250/8250_core.c:serial_unlink_irq_chain
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_free_interrupt
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
**Symbols:**

```
ffffffff811258a0-ffffffff8112590a: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81121700)
Location: kernel/irq/manage.c:1962
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/evged.c:ged_shutdown
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/serial/8250/8250_core.c:serial_unlink_irq_chain
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/dmar.c:free_iommu
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_free_interrupt
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_setup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
**Symbols:**

```
ffffffff81121700-ffffffff8112176a: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811219e0)
Location: kernel/irq/manage.c:1963
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/evged.c:ged_shutdown
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_free_interrupt
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
**Symbols:**

```
ffffffff811219e0-ffffffff81121a4a: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81141f80)
Location: kernel/irq/manage.c:1992
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/evged.c:ged_shutdown
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_free_interrupt
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
**Symbols:**

```
ffffffff81141f80-ffffffff81141fea: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81165a90)
Location: kernel/irq/manage.c:2026
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib-cdev.c:lineevent_free
  - drivers/gpio/gpiolib-cdev.c:edge_detector_stop
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/evged.c:ged_shutdown
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_free_interrupt
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
**Symbols:**

```
ffffffff81165a90-ffffffff81165b08: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811999f0)
Location: kernel/irq/manage.c:2018
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib-cdev.c:lineevent_free
  - drivers/gpio/gpiolib-cdev.c:edge_detector_stop
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/evged.c:ged_shutdown
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_request_interrupt
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
**Symbols:**

```
ffffffff811999f0-ffffffff81199a68: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811ab6d0)
Location: kernel/irq/manage.c:2024
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib-cdev.c:lineevent_free
  - drivers/gpio/gpiolib-cdev.c:edge_detector_stop
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/evged.c:ged_shutdown
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/perfmon.c:iommu_pmu_unregister
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_request_interrupt
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
**Symbols:**

```
ffffffff811ab6d0-ffffffff811ab748: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811bb270)
Location: kernel/irq/manage.c:2021
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib-cdev.c:lineevent_free
  - drivers/gpio/gpiolib-cdev.c:edge_detector_stop
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/evged.c:ged_shutdown
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe
  - drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/perfmon.c:iommu_pmu_unregister
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_irq_exit
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/phy/phy.c:phy_request_interrupt
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/input/serio/i8042.c:i8042_setup_aux
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_release
```
**Symbols:**

```
ffffffff811bb270-ffffffff811bb2e8: free_irq (STB_GLOBAL)
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
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017a7b8)
Location: kernel/irq/manage.c:1853
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_teardown
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
  - drivers/acpi/evged.c:ged_shutdown
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources
  - drivers/soc/fsl/qbman/bman.c:bman_create_portal
  - drivers/soc/fsl/qbman/qman.c:qman_destroy_affine_portal
  - drivers/soc/fsl/qbman/qman.c:qman_create_portal
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/meson_uart.c:meson_uart_shutdown
  - drivers/tty/serial/msm_serial.c:msm_shutdown
  - drivers/tty/serial/owl-uart.c:owl_uart_shutdown
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_stop
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_remove
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/clocksource/timer-of.c:timer_of_cleanup
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_queue_shutdown
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_remove
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_remove
  - drivers/perf/arm-cci.c:pmu_free_irq
  - drivers/perf/arm_pmu.c:armpmu_free_irq
```
**Symbols:**

```
ffff80001017a7b8-ffff80001017a838: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cba98)
Location: kernel/irq/manage.c:1853
Inline: False
Direct callers:
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
  - arch/arm/mach-omap2/pm34xx.c:omap3_pm_init
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/bus/omap_l3_smx.c:omap3_l3_remove
  - drivers/bus/omap_l3_smx.c:omap3_l3_remove
  - drivers/bus/omap_l3_smx.c:omap3_l3_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_teardown
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_put_resources
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_remove
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_shutdown
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
  - drivers/tty/serial/meson_uart.c:meson_uart_shutdown
  - drivers/tty/serial/msm_serial.c:msm_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/owl-uart.c:owl_uart_shutdown
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/musb/musb_core.c:musb_free
  - drivers/rtc/rtc-pl031.c:pl031_remove
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - drivers/clocksource/timer-of.c:timer_of_cleanup
  - drivers/clocksource/dw_apb_timer.c:dw_apb_clockevent_stop
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_remove
  - drivers/memory/omap-gpmc.c:gpmc_remove
  - drivers/perf/arm-cci.c:pmu_free_irq
  - drivers/perf/arm_pmu.c:armpmu_free_irq
```
**Symbols:**

```
c03cba98-c03cbb44: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d4c00)
Location: kernel/irq/manage.c:1853
Inline: False
Direct callers:
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_shutdown
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
```
**Symbols:**

```
c0000000001d4c00-c0000000001d4cd4: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000114056)
Location: kernel/irq/manage.c:1853
Inline: False
Direct callers:
  - arch/riscv/kernel/perf_event.c:release_pmc_hardware
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/tty/serial/sifive.c:sifive_serial_remove
  - drivers/tty/serial/sifive.c:sifive_serial_probe
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/mmc/host/of_mmc_spi.c:of_mmc_spi_exit
  - drivers/clocksource/timer-of.c:timer_of_cleanup
```
**Symbols:**

```
ffffffe000114056-ffffffe0001140c8: free_irq (STB_GLOBAL)
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
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811105c0)
Location: kernel/irq/manage.c:1853
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff811105c0-ffffffff81110626: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811012f0)
Location: kernel/irq/manage.c:1853
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff811012f0-ffffffff81101356: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110e4b0)
Location: kernel/irq/manage.c:1853
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8110e4b0-ffffffff8110e516: free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const void *free_irq(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811199e0)
Location: kernel/irq/manage.c:1853
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_dead
  - kernel/irq/devres.c:devm_free_irq
  - kernel/irq/devres.c:devm_irq_release
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/pci/irq.c:pci_free_irq
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_release_ctlr
  - drivers/acpi/osl.c:acpi_os_remove_interrupt_handler
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/tty/hvc/hvc_irq.c:notifier_hangup_irq
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_irq
  - drivers/char/hpet.c:hpet_release
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_clear_wake_irq
  - drivers/mfd/88pm860x-core.c:pm860x_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_free_irq
  - drivers/mfd/wm831x-irq.c:wm831x_irq_exit
  - drivers/mfd/wm8350-irq.c:wm8350_irq_exit
  - drivers/mfd/twl6030-irq.c:twl6030_exit_irq
  - drivers/mfd/da9052-irq.c:da9052_free_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8925-core.c:max8925_device_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8997-irq.c:max8997_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/max8998-irq.c:max8998_irq_exit
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_remove
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_set_vector_signal
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_set_signal
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_try_enable_msi
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/usb/host/xhci.c:xhci_cleanup_msix
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/input/serio/i8042.c:i8042_free_irqs
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff811199e0-ffffffff81119a46: free_irq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>const void *</code>
</li>
</ul>
</details>
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
