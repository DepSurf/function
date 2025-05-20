# Function: <code>device_set_wakeup_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155ba10)
Location: drivers/base/power/wakeup.c:410
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/power/charger-manager.c:cm_suspend_noirq
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
```
**Symbols:**

```
ffffffff8155ba10-ffffffff8155ba7f: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ae5c0)
Location: drivers/base/power/wakeup.c:408
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:cm_suspend_noirq
  - drivers/power/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff815ae5c0-ffffffff815ae61e: device_set_wakeup_capable.part.3 (STB_LOCAL)
ffffffff815ae620-ffffffff815ae645: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dd3c0)
Location: drivers/base/power/wakeup.c:408
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff815dd3c0-ffffffff815dd41e: device_set_wakeup_capable.part.5 (STB_LOCAL)
ffffffff815dd420-ffffffff815dd445: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f1b50)
Location: drivers/base/power/wakeup.c:410
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff815f1b50-ffffffff815f1bb7: device_set_wakeup_capable.part.10 (STB_LOCAL)
ffffffff815f1bc0-ffffffff815f1be6: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81659130)
Location: drivers/base/power/wakeup.c:410
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81659130-ffffffff8165919e: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81694e20)
Location: drivers/base/power/wakeup.c:414
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81694e20-ffffffff81694e8d: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b54c0)
Location: drivers/base/power/wakeup.c:420
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff816b54c0-ffffffff816b552d: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816ef0a8)
Location: drivers/base/power/wakeup.c:404
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff816efc5f-ffffffff816efc70: device_set_wakeup_capable.cold (STB_LOCAL)
ffffffff816ef060-ffffffff816ef0c7: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81713208)
Location: drivers/base/power/wakeup.c:424
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81713c69-ffffffff81713c7a: device_set_wakeup_capable.cold (STB_LOCAL)
ffffffff817131c0-ffffffff81713227: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817ce7b9)
Location: drivers/base/power/wakeup.c:483
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:fullbatt_handler
```
**Symbols:**

```
ffffffff817cf73c-ffffffff817cf74d: device_set_wakeup_capable.cold (STB_LOCAL)
ffffffff817ce770-ffffffff817ce7d7: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e2e79)
Location: drivers/base/power/wakeup.c:483
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81c0ef75-ffffffff81c0ef86: device_set_wakeup_capable.cold (STB_LOCAL)
ffffffff817e2e30-ffffffff817e2e97: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c7239)
Location: drivers/base/power/wakeup.c:483
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81c010dc-ffffffff81c010ed: device_set_wakeup_capable.cold (STB_LOCAL)
ffffffff817c71f0-ffffffff817c7257: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81851619)
Location: drivers/base/power/wakeup.c:484
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81d03ebd-ffffffff81d03ece: device_set_wakeup_capable.cold (STB_LOCAL)
ffffffff818515d0-ffffffff81851637: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81ecc7dd)
Location: drivers/base/power/wakeup.c:484
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81ecc7dd-ffffffff81ecc7ee: device_set_wakeup_capable.cold (STB_LOCAL)
ffffffff819973c0-ffffffff81997451: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b08380)
Location: drivers/base/power/wakeup.c:484
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81b08380-ffffffff81b08429: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b563b0)
Location: drivers/base/power/wakeup.c:479
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81b563b0-ffffffff81b56459: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81bae970)
Location: drivers/base/power/wakeup.c:479
Inline: True
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/battery.c:acpi_battery_remove
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81bae970-ffffffff81baea19: device_set_wakeup_capable (STB_GLOBAL)
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
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff800010903868)
Location: drivers/base/power/wakeup.c:424
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffff800010903868-ffff8000109038f4: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09ee2e0)
Location: drivers/base/power/wakeup.c:424
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
c09ee2e0-c09ee360: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a28e0)
Location: drivers/base/power/wakeup.c:424
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/rtc/rtc-opal.c:opal_rtc_probe
  - drivers/rtc/rtc-opal.c:opal_rtc_probe
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
c0000000009a28e0-c0000000009a29a4: device_set_wakeup_capable (STB_GLOBAL)
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
In drivers/pci/pci.c (ffffffe0004be0b4)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/pme.c (ffffffe0004d3bb0)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054cb38)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
```
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4fbc)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/twl-core.c (ffffffe0005b06bc)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:add_numbered_child
```
```
In drivers/mfd/max14577.c (ffffffe0005b779a)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffe0005b89c6)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffe0005b9660)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffe0005b9f9a)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffe0005babb2)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/tps6586x.c (ffffffe0005bd156)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffe0005bf178)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3722.c (ffffffe0005bff20)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/usb/core/hub.c (ffffffe00063c29e)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_set_device_state
```
```
In drivers/usb/core/hcd.c (ffffffe000640e5c)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
```
```
In drivers/usb/dwc2/platform.c (ffffffe00065a652)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-pci.c (ffffffe0006798fa)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067ec10)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_run
```
```
In drivers/usb/host/ohci-pci.c (ffffffe0006806e4)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_quirk_amd756
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe0006822f4)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b7544)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c914e)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006cc3f8)
Location: include/linux/pm_wakeup.h:109
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d9588)
Location: drivers/base/power/wakeup.c:424
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
```
**Symbols:**

```
ffffffff816d9f99-ffffffff816d9faa: device_set_wakeup_capable.cold (STB_LOCAL)
ffffffff816d9540-ffffffff816d95a7: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3bc8)
Location: drivers/base/power/wakeup.c:424
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/input/serio/i8042.c:i8042_start
```
**Symbols:**

```
ffffffff816b4619-ffffffff816b462a: device_set_wakeup_capable.cold (STB_LOCAL)
ffffffff816b3b80-ffffffff816b3be7: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81706ec8)
Location: drivers/base/power/wakeup.c:424
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81707929-ffffffff8170793a: device_set_wakeup_capable.cold (STB_LOCAL)
ffffffff81706e80-ffffffff81706ee7: device_set_wakeup_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void device_set_wakeup_capable(struct device *dev, bool capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817218f8)
Location: drivers/base/power/wakeup.c:424
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-acpi.c:pci_acpi_cleanup
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pcie/pme.c:pcie_pme_probe
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/usb/core/hub.c:usb_set_device_state
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ohci-hcd.c:ohci_run
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/input/serio/i8042.c:i8042_start
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_noirq
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
**Symbols:**

```
ffffffff81722359-ffffffff8172236a: device_set_wakeup_capable.cold (STB_LOCAL)
ffffffff817218b0-ffffffff81721917: device_set_wakeup_capable (STB_GLOBAL)
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
