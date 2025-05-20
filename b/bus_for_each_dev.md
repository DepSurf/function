# Function: <code>bus_for_each_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815498d0)
Location: drivers/base/bus.c:301
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffff815498d0-ffffffff81549981: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8159b520)
Location: drivers/base/bus.c:300
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffff8159b520-ffffffff8159b5d1: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815c9a80)
Location: drivers/base/bus.c:300
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffff815c9a80-ffffffff815c9b31: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815de7d0)
Location: drivers/base/bus.c:300
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffff815de7d0-ffffffff815de87f: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816457f0)
Location: drivers/base/bus.c:300
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffff816457f0-ffffffff816458a1: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81680c50)
Location: drivers/base/bus.c:298
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffff81680c50-ffffffff81680cff: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a06d0)
Location: drivers/base/bus.c:301
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffff816a06d0-ffffffff816a0784: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816d9600)
Location: drivers/base/bus.c:291
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffff816d9600-ffffffff816d96bd: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fd600)
Location: drivers/base/bus.c:291
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffff816fd600-ffffffff816fd6bd: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b74fe)
Location: drivers/base/bus.c:292
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
```
**Symbols:**

```
ffffffff817b6e90-ffffffff817b6f4d: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817cc21e)
Location: drivers/base/bus.c:292
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
```
**Symbols:**

```
ffffffff817cbbc0-ffffffff817cbc7d: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817afb8e)
Location: drivers/base/bus.c:292
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_port
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
```
**Symbols:**

```
ffffffff817af530-ffffffff817af5ed: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81838e4e)
Location: drivers/base/bus.c:288
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:__spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_port
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
```
**Symbols:**

```
ffffffff81838790-ffffffff8183884d: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8197b3ad)
Location: drivers/base/bus.c:288
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_for_each_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:__spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
```
**Symbols:**

```
ffffffff8197ac00-ffffffff8197acd7: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81ae842d)
Location: drivers/base/bus.c:288
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_for_each_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:__spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/usb/core/driver.c:usb_register_device_driver
  - drivers/i2c/i2c-core-base.c:i2c_register_driver
```
**Symbols:**

```
ffffffff81ae7b60-ffffffff81ae7c37: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bus_for_each_dev(const struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b36d7f)
Location: drivers/base/bus.c:354
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_for_each_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/base/dd.c:driver_attach
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/memory.c:for_each_memory_block
  - drivers/base/soc.c:soc_device_match
  - drivers/spi/spi.c:__spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/usb/core/driver.c:usb_register_device_driver
```
**Symbols:**

```
ffffffff81b36310-ffffffff81b363f3: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bus_for_each_dev(const struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b8e79f)
Location: drivers/base/bus.c:354
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_rescan_devices
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_for_each_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_shrink_memory_count
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:iommu_domain_alloc
  - drivers/iommu/iommu.c:bus_iommu_probe
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/iommu/iommu.c:iommu_device_unregister
  - drivers/base/dd.c:driver_attach
  - drivers/base/platform.c:__platform_driver_probe
  - drivers/base/memory.c:for_each_memory_block
  - drivers/base/soc.c:soc_device_match
  - drivers/spi/spi.c:__spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/usb/core/driver.c:usb_register_device_driver
```
**Symbols:**

```
ffffffff81b8dd30-ffffffff81b8de13: bus_for_each_dev (STB_GLOBAL)
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
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e8228)
Location: drivers/base/bus.c:291
Inline: False
Direct callers:
  - drivers/amba/bus.c:amba_find_device
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
  - drivers/firmware/arm_scmi/bus.c:scmi_bus_exit
```
**Symbols:**

```
ffff8000108e8228-ffff8000108e82f8: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d6644)
Location: drivers/base/bus.c:291
Inline: False
Direct callers:
  - arch/arm/mach-omap2/omap_device.c:__omap_device_late_init
  - drivers/amba/bus.c:amba_find_device
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
  - drivers/firmware/arm_scmi/bus.c:scmi_bus_exit
```
**Symbols:**

```
c09d6644-c09d6714: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097e540)
Location: drivers/base/bus.c:291
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
```
**Symbols:**

```
c00000000097e540-c00000000097e668: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057c530)
Location: drivers/base/bus.c:291
Inline: False
Direct callers:
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffe00057c530-ffffffe00057c5b6: bus_for_each_dev (STB_GLOBAL)
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
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c2df0)
Location: drivers/base/bus.c:291
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
```
**Symbols:**

```
ffffffff816c2df0-ffffffff816c2ead: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169e0a0)
Location: drivers/base/bus.c:291
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
```
**Symbols:**

```
ffffffff8169e0a0-ffffffff8169e15d: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f12c0)
Location: drivers/base/bus.c:291
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffff816f12c0-ffffffff816f137d: bus_for_each_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bus_for_each_dev(struct bus_type *bus, struct device *start, void *data, int (*fn)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170bb00)
Location: drivers/base/bus.c:291
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/base/bus.c:bus_rescan_devices
  - drivers/base/dd.c:driver_attach
  - drivers/base/memory.c:for_each_memory_block
  - drivers/spi/spi.c:spi_add_device
  - drivers/usb/core/usb.c:usb_for_each_dev
  - drivers/i2c/i2c-core-base.c:i2c_for_each_dev
```
**Symbols:**

```
ffffffff8170bb00-ffffffff8170bbbd: bus_for_each_dev (STB_GLOBAL)
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
