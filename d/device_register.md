# Function: <code>device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81548a70)
Location: drivers/base/core.c:1186
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/node.c:register_one_node
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/core.c:__nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffff81548a70-ffffffff81548a8d: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159a716)
Location: drivers/base/core.c:1186
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_register_driver
  - drivers/base/node.c:register_one_node
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffff8159a6a0-ffffffff8159a6bd: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c8c76)
Location: drivers/base/core.c:1772
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_register_driver
  - drivers/base/node.c:register_one_node
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/rtc/class.c:rtc_device_register
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_new_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffff815c8c00-ffffffff815c8c1d: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dd996)
Location: drivers/base/core.c:1770
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffff815dd920-ffffffff815dd93d: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81644996)
Location: drivers/base/core.c:1905
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:register_virtio_device
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffff81644920-ffffffff8164493d: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167fdc1)
Location: drivers/base/core.c:1952
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffff8167fd40-ffffffff8167fd5d: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169eb01)
Location: drivers/base/core.c:2031
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffff8169ea80-ffffffff8169ea9d: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d70be)
Location: drivers/base/core.c:2235
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/soundwire/slave.c:sdw_acpi_find_slaves
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffff816d7040-ffffffff816d705f: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fb1be)
Location: drivers/base/core.c:2272
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffff816fb140-ffffffff816fb15f: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b43fe)
Location: drivers/base/core.c:2770
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:tick_init_sysfs
  - kernel/time/clockevents.c:tick_init_sysfs
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_init_cache_dev
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff817b4370-ffffffff817b4391: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817caa1e)
Location: drivers/base/core.c:3179
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:tick_init_sysfs
  - kernel/time/clockevents.c:tick_init_sysfs
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_init_cache_dev
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff817ca990-ffffffff817ca9b1: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ae38e)
Location: drivers/base/core.c:3406
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff817ae300-ffffffff817ae321: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff818375ae)
Location: drivers/base/core.c:3471
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:init_memory_block
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81837520-ffffffff81837541: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8197964a)
Location: drivers/base/core.c:3506
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:add_memory_block
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff819795c0-ffffffff819795e6: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae612a)
Location: drivers/base/core.c:3705
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - mm/memory-tiers.c:find_create_memory_tier
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:add_memory_block
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
**Symbols:**

```
ffffffff81ae6090-ffffffff81ae60b6: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b344ca)
Location: drivers/base/core.c:3704
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - mm/memory-tiers.c:find_create_memory_tier
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:add_memory_block
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/wwan/wwan_core.c:wwan_create_port
  - drivers/net/wwan/wwan_core.c:wwan_create_dev
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
**Symbols:**

```
ffffffff81b34430-ffffffff81b34456: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b8bec9)
Location: drivers/base/core.c:3718
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_link_add
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - mm/memory-tiers.c:find_create_memory_tier
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:add_memory_block
  - drivers/gpu/drm/drm_sysfs.c:drm_class_device_register
  - drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
**Symbols:**

```
ffffffff81b8be00-ffffffff81b8be26: device_register (STB_GLOBAL)
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
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e57b0)
Location: drivers/base/core.c:2272
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/arm_scmi/bus.c:scmi_device_create
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffff8000108e5718-ffff8000108e574c: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d3f5c)
Location: drivers/base/core.c:2272
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/arm/mach-imx/devices/devices.c:mxc_device_init
  - arch/arm/mach-imx/devices/devices.c:mxc_device_init
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/firmware/arm_scmi/bus.c:scmi_device_create
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - sound/soc/soc-core.c:snd_soc_instantiate_card
```
**Symbols:**

```
c09d3ed0-c09d3ef8: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097b23c)
Location: drivers/base/core.c:2272
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_bus_init
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
c00000000097b180-c00000000097b1c0: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057a4c0)
Location: drivers/base/core.c:2272
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffe00057a430-ffffffe00057a464: device_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c09ae)
Location: drivers/base/core.c:2272
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff816c0930-ffffffff816c094f: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169bc5e)
Location: drivers/base/core.c:2272
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/hv/vmbus_drv.c:vmbus_device_register
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/vme/vme.c:vme_register_driver
```
**Symbols:**

```
ffffffff8169bbe0-ffffffff8169bbff: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816eee7e)
Location: drivers/base/core.c:2272
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffff816eee00-ffffffff816eee1f: device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int device_register(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817093de)
Location: drivers/base/core.c:2272
Inline: True
Inline callers:
  - drivers/base/core.c:__root_device_register
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/time/clocksource.c:init_clocksource_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - drivers/pwm/sysfs.c:export_store
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/rapidio/rio.c:rio_register_mport
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/pnp/core.c:__pnp_add_device
  - drivers/pnp/core.c:pnp_register_protocol
  - drivers/pnp/card.c:pnp_add_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio_mmio.c:vm_cmdline_set
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/xen-balloon.c:xen_balloon_init
  - drivers/regulator/core.c:regulator_register
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:register_cpu
  - drivers/base/isa.c:isa_bus_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nvdimm_bus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:__thermal_cooling_device_register
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
```
**Symbols:**

```
ffffffff81709320-ffffffff8170933f: device_register (STB_GLOBAL)
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
