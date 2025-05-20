# Function: <code>add_uevent_var</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff813ec900)
Location: lib/kobject_uevent.c:386
Inline: False
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
```
**Symbols:**

```
ffffffff813ec900-ffffffff813eca1c: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81432bc0)
Location: lib/kobject_uevent.c:386
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
```
**Symbols:**

```
ffffffff81432bc0-ffffffff81432cdc: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8144ee30)
Location: lib/kobject_uevent.c:386
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
```
**Symbols:**

```
ffffffff8144ee30-ffffffff8144ef4c: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff818ef070)
Location: lib/kobject_uevent.c:527
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff818ef070-ffffffff818ef174: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81975350)
Location: lib/kobject_uevent.c:578
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/base/firmware_class.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81975350-ffffffff81975454: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff819d1880)
Location: lib/kobject_uevent.c:648
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff819d1880-ffffffff819d1988: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0aea0)
Location: lib/kobject_uevent.c:650
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a0aea0-ffffffff81a0afa8: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a7a880)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - drivers/soundwire/bus_type.c:sdw_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a7a880-ffffffff81a7a988: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ab1be0)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81ab1be0-ffffffff81ab1ce8: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815ec000)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - block/partitions/core.c:part_uevent
  - block/partitions/core.c:part_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_action_args
  - lib/kobject_uevent.c:kobject_action_args
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/acpi/device_sysfs.c:acpi_device_uevent_modalias
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
```
**Symbols:**

```
ffffffff815ec000-ffffffff815ec108: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff816107e0)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - block/partitions/core.c:part_uevent
  - block/partitions/core.c:part_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_action_args
  - lib/kobject_uevent.c:kobject_action_args
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/roles/class.c:usb_role_switch_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - drivers/md/dm-uevent.c:dm_build_path_uevent
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
```
**Symbols:**

```
ffffffff816107e0-ffffffff816108e8: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815f3ea0)
Location: lib/kobject_uevent.c:654
Inline: False
Direct callers:
  - block/partitions/core.c:part_uevent
  - block/partitions/core.c:part_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_action_args
  - lib/kobject_uevent.c:kobject_action_args
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/roles/class.c:usb_role_switch_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
```
**Symbols:**

```
ffffffff815f3ea0-ffffffff815f3fa8: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81661190)
Location: lib/kobject_uevent.c:654
Inline: False
Direct callers:
  - block/genhd.c:block_uevent
  - block/partitions/core.c:part_uevent
  - block/partitions/core.c:part_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_action_args
  - lib/kobject_uevent.c:kobject_action_args
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/phy/phy.c:usb_phy_uevent
  - drivers/usb/phy/phy.c:usb_phy_uevent
  - drivers/usb/roles/class.c:usb_role_switch_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
```
**Symbols:**

```
ffffffff81661190-ffffffff8166131b: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8177af00)
Location: lib/kobject_uevent.c:654
Inline: False
Direct callers:
  - block/genhd.c:block_uevent
  - block/partitions/core.c:part_uevent
  - block/partitions/core.c:part_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_action_args
  - lib/kobject_uevent.c:kobject_action_args
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/phy/phy.c:usb_phy_uevent
  - drivers/usb/phy/phy.c:usb_phy_uevent
  - drivers/usb/roles/class.c:usb_role_switch_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
```
**Symbols:**

```
ffffffff8177af00-ffffffff8177b0bb: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff82023db0)
Location: lib/kobject_uevent.c:654
Inline: False
Direct callers:
  - block/genhd.c:block_uevent
  - block/partitions/core.c:part_uevent
  - block/partitions/core.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/phy/phy.c:usb_phy_uevent
  - drivers/usb/phy/phy.c:usb_phy_uevent
  - drivers/usb/roles/class.c:usb_role_switch_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_action_args
  - lib/kobject_uevent.c:kobject_action_args
```
**Symbols:**

```
ffffffff82023db0-ffffffff82023f6b: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff820a3eb0)
Location: lib/kobject_uevent.c:654
Inline: False
Direct callers:
  - block/genhd.c:block_uevent
  - block/partitions/core.c:part_uevent
  - block/partitions/core.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/phy/phy.c:usb_phy_uevent
  - drivers/usb/phy/phy.c:usb_phy_uevent
  - drivers/usb/roles/class.c:usb_role_switch_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_action_args
  - lib/kobject_uevent.c:kobject_action_args
```
**Symbols:**

```
ffffffff820a3eb0-ffffffff820a406b: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8217bf80)
Location: lib/kobject_uevent.c:654
Inline: False
Direct callers:
  - block/genhd.c:block_uevent
  - block/partitions/core.c:part_uevent
  - block/partitions/core.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/auxiliary.c:auxiliary_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/base/firmware_loader/sysfs.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/phy/phy.c:usb_phy_uevent
  - drivers/usb/phy/phy.c:usb_phy_uevent
  - drivers/usb/roles/class.c:usb_role_switch_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_path_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/bus.c:mmc_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_action_args
  - lib/kobject_uevent.c:kobject_action_args
```
**Symbols:**

```
ffffffff8217bf80-ffffffff8217c13b: add_uevent_var (STB_GLOBAL)
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
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffff800010d8bf40)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/roles/class.c:usb_role_switch_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - drivers/of/device.c:of_device_uevent_modalias
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffff800010d8bf40-ffff800010d8c064: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (c0e862ec)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/gadget/udc/core.c:usb_udc_uevent
  - drivers/usb/gadget/udc/core.c:usb_udc_uevent
  - drivers/usb/roles/class.c:usb_role_switch_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - drivers/of/device.c:of_device_uevent_modalias
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
c0e862ec-c0e863f0: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (c000000000ecd8c0)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_hotplug
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/of/device.c:of_device_uevent_modalias
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
c000000000ecd8c0-c000000000ecd9bc: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffe0008b4f46)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/of/device.c:of_device_uevent_modalias
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffe0008b4f46-ffffffe0008b5002: add_uevent_var (STB_GLOBAL)
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
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a50a30)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/nvme/host/core.c:nvme_class_uevent
  - drivers/nvme/host/core.c:nvme_class_uevent
  - drivers/nvme/host/core.c:nvme_class_uevent
  - drivers/nvme/host/core.c:nvme_class_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a50a30-ffffffff81a50b38: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0db30)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/nvme/host/core.c:nvme_class_uevent
  - drivers/nvme/host/core.c:nvme_class_uevent
  - drivers/nvme/host/core.c:nvme_class_uevent
  - drivers/nvme/host/core.c:nvme_class_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - drivers/hv/vmbus_drv.c:vmbus_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a0db30-ffffffff81a0dc38: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81abce20)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81abce20-ffffffff81abcf28: add_uevent_var (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int add_uevent_var(struct kobj_uevent_env *env, const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ac92a0)
Location: lib/kobject_uevent.c:653
Inline: False
Direct callers:
  - block/partition-generic.c:part_uevent
  - block/partition-generic.c:part_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/pci/pci-driver.c:pci_uevent
  - drivers/rapidio/rio-driver.c:rio_uevent
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/core.c:dev_uevent
  - drivers/base/cpu.c:cpu_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/base/firmware_loader/fallback.c:firmware_uevent
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/dax/bus.c:dax_bus_uevent
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_uevent
  - drivers/spi/spi.c:spi_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/usb.c:usb_dev_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/serio/serio.c:serio_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_dev_uevent
  - drivers/input/input.c:input_add_uevent_bm_var
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/eisa/eisa-bus.c:eisa_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/mmc/core/sdio_bus.c:sdio_bus_uevent
  - drivers/firmware/dmi-id.c:dmi_dev_uevent
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81ac92a0-ffffffff81ac93a8: add_uevent_var (STB_GLOBAL)
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
