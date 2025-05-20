# Function: <code>device_release_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8154b740)
Location: drivers/base/dd.c:715
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/pnp/card.c:card_probe
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff8154b740-ffffffff8154b770: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8159d440)
Location: drivers/base/dd.c:806
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/pnp/card.c:card_probe
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:unbind_store
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff8159d440-ffffffff8159d470: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815cc4d0)
Location: drivers/base/dd.c:872
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/pnp/card.c:card_probe
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:unbind_store
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff815cc4d0-ffffffff815cc4e4: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815e1080)
Location: drivers/base/dd.c:881
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:unbind_store
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff815e1080-ffffffff815e1094: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816481a0)
Location: drivers/base/dd.c:921
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:unbind_store
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff816481a0-ffffffff816481b4: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816836c0)
Location: drivers/base/dd.c:942
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:unbind_store
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff816836c0-ffffffff816836d4: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a33c0)
Location: drivers/base/dd.c:1026
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:device_reprobe
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:unbind_store
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff816a33c0-ffffffff816a33d4: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816dc200)
Location: drivers/base/dd.c:1174
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff816dc200-ffffffff816dc214: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81700240)
Location: drivers/base/dd.c:1191
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff81700240-ffffffff81700254: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b90c0)
Location: drivers/base/dd.c:1165
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff817b90c0-ffffffff817b90f7: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817cde50)
Location: drivers/base/dd.c:1213
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff817cde50-ffffffff817cde87: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b1850)
Location: drivers/base/dd.c:1228
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff817b1850-ffffffff817b1887: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8183ab00)
Location: drivers/base/dd.c:1257
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff8183ab00-ffffffff8183ab37: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8197e630)
Location: drivers/base/dd.c:1267
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff8197e630-ffffffff8197e64e: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81aebbb0)
Location: drivers/base/dd.c:1295
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim_one
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff81aebbb0-ffffffff81aebbce: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b39df0)
Location: drivers/base/dd.c:1311
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim_one
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff81b39df0-ffffffff81b39e0e: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b918b0)
Location: drivers/base/dd.c:1311
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim_one
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff81b918b0-ffffffff81b918ce: device_release_driver (STB_GLOBAL)
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
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108eb550)
Location: drivers/base/dd.c:1191
Inline: False
Direct callers:
  - drivers/bus/fsl-mc/dprc-driver.c:dprc_scan_objects
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffff8000108eb550-ffff8000108eb584: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d9648)
Location: drivers/base/dd.c:1191
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
c09d9648-c09d966c: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c000000000982be0)
Location: drivers/base/dd.c:1191
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
c000000000982be0-c000000000982bfc: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057f160)
Location: drivers/base/dd.c:1191
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffe00057f160-ffffffe00057f18e: device_release_driver (STB_GLOBAL)
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
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c5a30)
Location: drivers/base/dd.c:1191
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/nvme/host/pci.c:nvme_remove_dead_ctrl_work
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff816c5a30-ffffffff816c5a44: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a0cb0)
Location: drivers/base/dd.c:1191
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/nvme/host/pci.c:nvme_remove_dead_ctrl_work
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff816a0cb0-ffffffff816a0cc4: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f3f00)
Location: drivers/base/dd.c:1191
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff816f3f00-ffffffff816f3f14: device_release_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_release_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170e730)
Location: drivers/base/dd.c:1191
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_bus_device
  - drivers/acpi/scan.c:acpi_bus_trim
  - drivers/acpi/acpi_processor.c:acpi_processor_remove
  - drivers/base/bus.c:bus_remove_device
  - drivers/net/phy/phy_device.c:phy_detach
  - drivers/usb/core/driver.c:usb_driver_release_interface
  - drivers/input/serio/serio.c:serio_disconnect_port
  - drivers/input/serio/serio.c:serio_disconnect_port
```
**Symbols:**

```
ffffffff8170e730-ffffffff8170e744: device_release_driver (STB_GLOBAL)
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
