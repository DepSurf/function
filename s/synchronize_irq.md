# Function: <code>synchronize_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dab80)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff810dab80-ffffffff810dac2c: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e0190)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff810e0190-ffffffff810e023c: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6ae0)
Location: kernel/irq/manage.c:104
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff810e6ae0-ffffffff810e6b82: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e61e0)
Location: kernel/irq/manage.c:106
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff810e61e0-ffffffff810e6282: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ee480)
Location: kernel/irq/manage.c:106
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff810ee480-ffffffff810ee522: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f6870)
Location: kernel/irq/manage.c:106
Inline: False
Direct callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff810f6870-ffffffff810f6912: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81101fe0)
Location: kernel/irq/manage.c:106
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff81101fe0-ffffffff81102082: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110a7a0)
Location: kernel/irq/manage.c:132
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff8110a7a0-ffffffff8110a847: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81116b70)
Location: kernel/irq/manage.c:132
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff81116b70-ffffffff81116c17: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811254b0)
Location: kernel/irq/manage.c:133
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff811254b0-ffffffff81125557: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81121310)
Location: kernel/irq/manage.c:133
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff81121310-ffffffff811213b7: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811215f0)
Location: kernel/irq/manage.c:133
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff811215f0-ffffffff81121697: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81141b90)
Location: kernel/irq/manage.c:126
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff81141b90-ffffffff81141c37: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81165660)
Location: kernel/irq/manage.c:126
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_mmio.c:vm_synchronize_cbs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff81165660-ffffffff81165742: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81199590)
Location: kernel/irq/manage.c:126
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_mmio.c:vm_synchronize_cbs
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff81199590-ffffffff81199672: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811ab270)
Location: kernel/irq/manage.c:126
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_mmio.c:vm_synchronize_cbs
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff811ab270-ffffffff811ab352: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811bb32a)
Location: kernel/irq/manage.c:136
Inline: True
Inline callers:
  - kernel/irq/manage.c:disable_irq
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_mmio.c:vm_synchronize_cbs
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/platform.c:dwc2_driver_shutdown
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ohci-hcd.c:ohci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff811bafa0-ffffffff811bafc5: synchronize_irq (STB_GLOBAL)
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
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff8000101796a8)
Location: kernel/irq/manage.c:132
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
```
**Symbols:**

```
ffff8000101796a8-ffff800010179764: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03ca38c)
Location: kernel/irq/manage.c:132
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
```
**Symbols:**

```
c03ca38c-c03ca444: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d2c20)
Location: kernel/irq/manage.c:132
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/hvc/hvsi.c:hvsi_close
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
c0000000001d2c20-c0000000001d2d1c: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000113542)
Location: kernel/irq/manage.c:132
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:hcd_pci_runtime_suspend
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
```
**Symbols:**

```
ffffffe000113542-ffffffe0001135dc: synchronize_irq (STB_GLOBAL)
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
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110f150)
Location: kernel/irq/manage.c:132
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff8110f150-ffffffff8110f1f7: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ffe90)
Location: kernel/irq/manage.c:132
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff810ffe90-ffffffff810fff37: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d040)
Location: kernel/irq/manage.c:132
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff8110d040-ffffffff8110d0e7: synchronize_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void synchronize_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811185a0)
Location: kernel/irq/manage.c:132
Inline: False
Direct callers:
  - kernel/irq/manage.c:disable_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/pm.c:suspend_device_irqs
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/virtio/virtio_pci_common.c:vp_synchronize_vectors
  - drivers/tty/serial/serial_core.c:uart_port_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/usb/core/hcd-pci.c:suspend_common
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_stop
  - drivers/usb/host/ehci-hcd.c:ehci_suspend
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/uhci-hcd.c:uhci_pci_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/input/serio/i8042.c:i8042_stop
  - drivers/input/serio/i8042.c:i8042_stop
```
**Symbols:**

```
ffffffff811185a0-ffffffff81118642: synchronize_irq (STB_GLOBAL)
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
