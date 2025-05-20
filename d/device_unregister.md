# Function: <code>device_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81547030)
Location: drivers/base/core.c:1296
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:workqueue_sysfs_register
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - block/bsg.c:bsg_unregister_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/video/backlight/backlight.c:backlight_device_unregister
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_destroy
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/node.c:unregister_one_node
  - drivers/base/memory.c:unregister_memory_section
  - drivers/nvdimm/core.c:nvdimm_bus_unregister
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_unregister_master
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/i2c/i2c-core.c:__unregister_dummy
  - drivers/i2c/i2c-core.c:__unregister_client
  - drivers/i2c/i2c-core.c:i2c_do_del_adapter
  - drivers/i2c/i2c-core.c:i2c_sysfs_delete_device
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_dev_release
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/extcon/extcon.c:extcon_dev_unregister
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffff81547030-ffffffff8154708a: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81598cb0)
Location: drivers/base/core.c:1296
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_create
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - block/bsg.c:bsg_unregister_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_unregister
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_destroy
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/isa.c:isa_register_driver
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_one_node
  - drivers/base/memory.c:unregister_memory_section
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_master
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core.c:i2c_unregister_device
  - drivers/i2c/i2c-core.c:i2c_unregister_device
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_dev_release
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/extcon/extcon.c:extcon_dev_unregister
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffff81598cb0-ffffffff81598d06: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c7770)
Location: drivers/base/core.c:1887
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - block/bsg.c:bsg_unregister_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_unregister
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_destroy
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/isa.c:isa_register_driver
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_one_node
  - drivers/base/memory.c:unregister_memory_section
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_master
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core.c:i2c_unregister_device
  - drivers/i2c/i2c-core.c:i2c_unregister_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/thermal/thermal_core.c:thermal_zone_device_unregister
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/devfreq/devfreq.c:devm_devfreq_dev_release
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/extcon/extcon.c:extcon_dev_unregister
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffff815c7770-ffffffff815c77c6: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dc460)
Location: drivers/base/core.c:1885
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_one_node
  - drivers/base/memory.c:unregister_memory_section
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:of_led_classdev_register
  - drivers/devfreq/devfreq.c:devm_devfreq_dev_release
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffff815dc460-ffffffff815dc4b6: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816434a0)
Location: drivers/base/core.c:2020
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_one_node
  - drivers/base/memory.c:unregister_memory_section
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_slave_store
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:of_led_classdev_register
  - drivers/devfreq/devfreq.c:devm_devfreq_dev_release
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffff816434a0-ffffffff816434f6: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167e5a0)
Location: drivers/base/core.c:2067
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_one_node
  - drivers/base/memory.c:unregister_memory_section
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_slave_store
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:of_led_classdev_register
  - drivers/devfreq/devfreq.c:devm_devfreq_dev_release
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffff8167e5a0-ffffffff8167e5f6: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169dfb0)
Location: drivers/base/core.c:2142
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_one_node
  - drivers/base/memory.c:unregister_memory_section
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_slave_store
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:of_led_classdev_register
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffff8169dfb0-ffffffff8169e006: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d6390)
Location: drivers/base/core.c:2368
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_slave_store
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:of_led_classdev_register
  - drivers/soundwire/bus.c:sdw_delete_slave
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffff816d6390-ffffffff816d63e6: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fa3d0)
Location: drivers/base/core.c:2405
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:slave_store
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffff816fa3d0-ffffffff816fa426: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b3490)
Location: drivers/base/core.c:2906
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:slave_store
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_unregister
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devm_devfreq_dev_release
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff817b3490-ffffffff817b34e8: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c7e60)
Location: drivers/base/core.c:3318
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:__device_link_del
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:slave_store
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_unregister
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff817c7e60-ffffffff817c7eb8: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ab370)
Location: drivers/base/core.c:3545
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:__device_link_del
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:slave_store
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_unregister
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff817ab370-ffffffff817ab3c8: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff818346d0)
Location: drivers/base/core.c:3610
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:__device_link_del
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/base/memory.c:init_memory_block
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:slave_store
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_remove_dev
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_unregister
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_release
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff818346d0-ffffffff81834725: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819761a0)
Location: drivers/base/core.c:3644
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:__device_link_del
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:remove_memory_block
  - drivers/base/memory.c:add_memory_block
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_remove_dev
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_unregister
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_release
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/vme/vme.c:__vme_register_driver_bus
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff819761a0-ffffffff81976200: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae2260)
Location: drivers/base/core.c:3843
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - mm/memory-tiers.c:memtier_hotplug_callback
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:__device_link_del
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:remove_memory_block
  - drivers/base/memory.c:add_memory_block
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_remove_dev
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/staging/vme_user/vme.c:vme_unregister_driver
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/staging/vme_user/vme.c:vme_unregister_bridge
  - drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_unregister
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_release
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff81ae2260-ffffffff81ae22c0: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b30180)
Location: drivers/base/core.c:3852
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - mm/memory-tiers.c:memtier_hotplug_callback
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:__device_link_del
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_unregister
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:remove_memory_block
  - drivers/base/memory.c:add_memory_block
  - drivers/base/soc.c:soc_device_unregister
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/dax/bus.c:unregister_dax_mapping
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_remove_dev
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/staging/vme_user/vme.c:vme_unregister_driver
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/staging/vme_user/vme.c:vme_unregister_bridge
  - drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_unregister
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_release
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
  - drivers/nvmem/core.c:nvmem_device_release
```
**Symbols:**

```
ffffffff81b30180-ffffffff81b301e0: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b87980)
Location: drivers/base/core.c:3866
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - mm/memory-tiers.c:memtier_hotplug_callback
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:devm_pci_epc_release
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/dma/dmaengine.c:__dma_async_device_channel_unregister
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:__device_link_del
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:arch_unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_unregister
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:remove_memory_block
  - drivers/base/memory.c:add_memory_block
  - drivers/base/soc.c:soc_device_unregister
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/dax/bus.c:unregister_dax_mapping
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_sysfs.c:drm_class_device_unregister
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_remove
  - drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_unregister
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/gpu/drm/drm_mipi_dsi.c:devm_mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_unregister_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/staging/vme_user/vme.c:vme_unregister_driver
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/staging/vme_user/vme.c:vme_unregister_bridge
  - drivers/platform/x86/intel_scu_ipc.c:devm_intel_scu_ipc_unregister
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devm_devfreq_event_release
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_unregister
```
**Symbols:**

```
ffffffff81b87980-ffffffff81b879e0: device_unregister (STB_GLOBAL)
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
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e4bb8)
Location: drivers/base/core.c:2405
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/bus/vexpress-config.c:vexpress_config_bridge_register
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/amba/bus.c:amba_device_unregister
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/base/soc.c:soc_device_unregister
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/firmware/arm_scmi/bus.c:scmi_device_destroy
  - drivers/of/device.c:of_device_unregister
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffff8000108e4bb8-ffff8000108e4c2c: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d3604)
Location: drivers/base/core.c:2405
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/bus/vexpress-config.c:vexpress_config_bridge_register
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/amba/bus.c:amba_device_unregister
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/soc.c:soc_device_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/mtd/mtdcore.c:del_mtd_device
  - drivers/mtd/mtdcore.c:add_mtd_device
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/musb/musb_gadget.c:musb_gadget_setup
  - drivers/usb/gadget/udc/core.c:usb_del_gadget_udc
  - drivers/usb/gadget/udc/core.c:usb_del_gadget_udc
  - drivers/usb/roles/class.c:usb_role_switch_unregister
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/firmware/arm_scmi/bus.c:scmi_device_destroy
  - drivers/of/device.c:of_device_unregister
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
  - sound/soc/soc-core.c:soc_cleanup_card_resources
```
**Symbols:**

```
c09d3604-c09d3678: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097a0f0)
Location: drivers/base/core.c:2405
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/pci_dlpar.c:remove_phb_dynamic
  - arch/powerpc/platforms/pseries/vio.c:vio_unregister_device
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/base/soc.c:soc_device_unregister
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/of/device.c:of_device_unregister
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
c00000000097a0f0-c00000000097a188: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe0005799e4)
Location: drivers/base/core.c:2405
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/regulator/core.c:regulator_unregister
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_unregister_device
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/of/device.c:of_device_unregister
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffe0005799e4-ffffffe000579a52: device_unregister (STB_GLOBAL)
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
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bfbc0)
Location: drivers/base/core.c:2405
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:slave_store
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
```
**Symbols:**

```
ffffffff816bfbc0-ffffffff816bfc16: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169ae70)
Location: drivers/base/core.c:2405
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:slave_store
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/hv/vmbus_drv.c:vmbus_device_unregister
  - drivers/hv/vmbus_drv.c:vmbus_device_register
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
```
**Symbols:**

```
ffffffff8169ae70-ffffffff8169aec6: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ee090)
Location: drivers/base/core.c:2405
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:slave_store
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffff816ee090-ffffffff816ee0e6: device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_unregister(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817088d0)
Location: drivers/base/core.c:2405
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_online
  - arch/x86/kernel/cpu/mce/core.c:mce_device_remove
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:destroy_workqueue
  - mm/backing-dev.c:bdi_unregister
  - block/bsg.c:bsg_register_queue
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:gpiod_unexport
  - drivers/pwm/sysfs.c:pwmchip_sysfs_unexport
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/remove.c:pci_remove_bus
  - drivers/pci/pcie/portdrv_core.c:remove_iter
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_destroy
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_destroy
  - drivers/rapidio/rio.c:rio_unregister_mport
  - drivers/rapidio/rio.c:rio_del_device
  - drivers/rapidio/rio.c:rio_free_net
  - drivers/video/backlight/backlight.c:backlight_device_register
  - drivers/acpi/container.c:container_device_detach
  - drivers/pnp/core.c:__pnp_remove_device
  - drivers/pnp/core.c:pnp_unregister_protocol
  - drivers/pnp/card.c:pnp_remove_card
  - drivers/dma/dmaengine.c:dma_async_device_unregister
  - drivers/dma/dmaengine.c:dma_async_device_register
  - drivers/virtio/virtio.c:unregister_virtio_device
  - drivers/virtio/virtio_mmio.c:virtio_mmio_exit
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/pcpu.c:xen_sync_pcpus
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/regulator/core.c:regulator_unregister
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/base/core.c:device_destroy
  - drivers/base/core.c:root_device_unregister
  - drivers/base/core.c:__root_device_register
  - drivers/base/bus.c:bus_unregister
  - drivers/base/platform.c:platform_bus_init
  - drivers/base/cpu.c:unregister_cpu
  - drivers/base/attribute_container.c:attribute_container_remove_device
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/cacheinfo.c:cpu_cache_sysfs_exit
  - drivers/base/power/wakeup_stats.c:wakeup_source_sysfs_remove
  - drivers/base/isa.c:isa_unregister_driver
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/node.c:unregister_node
  - drivers/base/memory.c:unregister_memory
  - drivers/nvdimm/bus.c:nd_async_device_unregister
  - drivers/nvdimm/bus.c:nvdimm_bus_unregister
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_remove_device_fn
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:slave_store
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/usb/core/endpoint.c:usb_remove_ep_devs
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_exit
  - drivers/edac/edac_mc_sysfs.c:edac_unregister_sysfs
  - drivers/edac/edac_mc_sysfs.c:edac_remove_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/eisa/eisa-bus.c:eisa_register_device
  - drivers/leds/led-class.c:led_classdev_register_ext
  - drivers/remoteproc/remoteproc_core.c:rproc_vdev_release
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
  - drivers/devfreq/devfreq.c:devfreq_remove_device
  - drivers/devfreq/devfreq-event.c:devfreq_event_remove_edev
  - drivers/vme/vme.c:vme_unregister_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_register_driver
  - drivers/vme/vme.c:vme_unregister_bridge
  - drivers/powercap/powercap_sys.c:powercap_unregister_zone
```
**Symbols:**

```
ffffffff817088d0-ffffffff81708926: device_unregister (STB_GLOBAL)
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
