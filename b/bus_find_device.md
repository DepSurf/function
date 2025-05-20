# Function: <code>bus_find_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81549aa0)
Location: drivers/base/bus.c:335
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:store_drivers_probe
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff81549aa0-ffffffff81549b67: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8159b6f0)
Location: drivers/base/bus.c:334
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
```
**Symbols:**

```
ffffffff8159b6f0-ffffffff8159b7b7: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815c9c50)
Location: drivers/base/bus.c:334
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff815c9c50-ffffffff815c9d17: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815de990)
Location: drivers/base/bus.c:334
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
**Symbols:**

```
ffffffff815de990-ffffffff815dea55: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816459c0)
Location: drivers/base/bus.c:334
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/nvmem/core.c:devm_nvmem_device_get
```
**Symbols:**

```
ffffffff816459c0-ffffffff81645a87: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81680e20)
Location: drivers/base/bus.c:332
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_get_first_match_name
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81680e20-ffffffff81680ee5: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a08b0)
Location: drivers/base/bus.c:335
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_get_first_match_name
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/base/bus.c:store_drivers_probe
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816a08b0-ffffffff816a0971: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816d97f0)
Location: drivers/base/bus.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816d97f0-ffffffff816d98b3: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fd7f0)
Location: drivers/base/bus.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816fd7f0-ffffffff816fd8b3: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b7060)
Location: drivers/base/bus.c:326
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/base/devcon.c:device_connection_fwnode_match
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
ffffffff817b7060-ffffffff817b7123: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817cbd90)
Location: drivers/base/bus.c:326
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/base/auxiliary.c:auxiliary_find_device
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
ffffffff817cbd90-ffffffff817cbe53: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817af700)
Location: drivers/base/bus.c:326
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/base/auxiliary.c:auxiliary_find_device
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
ffffffff817af700-ffffffff817af7c3: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81838960)
Location: drivers/base/bus.c:322
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/base/auxiliary.c:auxiliary_find_device
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
ffffffff81838960-ffffffff81838a23: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8197ae00)
Location: drivers/base/bus.c:322
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/base/auxiliary.c:auxiliary_find_device
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
ffffffff8197ae00-ffffffff8197aede: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81ae7d90)
Location: drivers/base/bus.c:322
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/base/auxiliary.c:auxiliary_find_device
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
ffffffff81ae7d90-ffffffff81ae7e6e: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *bus_find_device(const struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b36510)
Location: drivers/base/bus.c:390
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/base/auxiliary.c:auxiliary_find_device
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-base.c:i2c_find_adapter_by_fwnode
  - drivers/i2c/i2c-core-base.c:i2c_find_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_allocate_context
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
ffffffff81b36510-ffffffff81b365fc: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *bus_find_device(const struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b8df30)
Location: drivers/base/bus.c:390
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_dev_present
  - drivers/pci/search.c:pci_get_base_class
  - drivers/pci/search.c:pci_get_class
  - drivers/pci/search.c:pci_get_domain_bus_and_slot
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/base/auxiliary.c:auxiliary_find_device
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-base.c:i2c_find_adapter_by_fwnode
  - drivers/i2c/i2c-core-base.c:i2c_find_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_allocate_context
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
ffffffff81b8df30-ffffffff81b8e01c: bus_find_device (STB_GLOBAL)
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
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e8460)
Location: drivers/base/bus.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
  - drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
  - drivers/of/of_mdio.c:of_phy_find_device
  - drivers/nvmem/core.c:__nvmem_device_get
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
ffff8000108e8460-ffff8000108e8540: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d6868)
Location: drivers/base/bus.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
  - drivers/of/of_mdio.c:of_phy_find_device
  - drivers/nvmem/core.c:__nvmem_device_get
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
c09d6868-c09d6944: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097e850)
Location: drivers/base/bus.c:325
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_find_node
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
  - drivers/of/of_mdio.c:of_phy_find_device
  - drivers/nvmem/core.c:__nvmem_device_get
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
c00000000097e850-c00000000097e990: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057c6b8)
Location: drivers/base/bus.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node
  - drivers/i2c/i2c-core-of.c:of_find_i2c_device_by_node
  - drivers/of/of_mdio.c:of_phy_find_device
  - drivers/nvmem/core.c:__nvmem_device_get
  - drivers/nvmem/core.c:__nvmem_device_get
```
**Symbols:**

```
ffffffe00057c6b8-ffffffe00057c748: bus_find_device (STB_GLOBAL)
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
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c2fe0)
Location: drivers/base/bus.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816c2fe0-ffffffff816c30a3: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169e290)
Location: drivers/base/bus.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff8169e290-ffffffff8169e353: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f14b0)
Location: drivers/base/bus.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816f14b0-ffffffff816f1573: bus_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *bus_find_device(struct bus_type *bus, struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170bcf0)
Location: drivers/base/bus.c:325
Inline: False
Direct callers:
  - drivers/pci/probe.c:no_pci_devices
  - drivers/pci/search.c:pci_get_dev_by_id
  - drivers/acpi/utils.c:acpi_dev_get_first_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_find_device
  - drivers/base/bus.c:drivers_probe_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:bind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/bus.c:unbind_store
  - drivers/base/platform.c:platform_find_device_by_driver
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
  - drivers/gpu/drm/drm_mipi_dsi.c:of_find_mipi_dsi_device_by_node
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/usb/core/usb.c:usb_find_interface
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff8170bcf0-ffffffff8170bdb3: bus_find_device (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *data</code> ➡️ <code>const void *data</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*match)(struct device *, void *)</code> ➡️ <code>int (*match)(struct device *, const void *)</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bus_type *bus</code> ➡️ <code>const struct bus_type *bus</code>
</li>
</ul>
</details>
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
