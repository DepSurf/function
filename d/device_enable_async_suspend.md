# Function: <code>device_enable_async_suspend</code>

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
In drivers/pci/probe.c (ffffffff81432001)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
```
In drivers/pci/pci.c (ffffffff814373a5)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81448cb9)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff815536f7)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff815a80b0)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff815b5a9e)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff815db08f)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff8160872f)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff81613319)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff816195b2)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff8161f525)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/mmc/core/bus.c (ffffffff816c1a97)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff816cad3b)
Location: include/linux/device.h:926
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff8147d841)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
```
In drivers/pci/pci.c (ffffffff81482fa5)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81494f09)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff815a56f7)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff815fff37)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8160e1b4)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff81634c6f)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff816683f7)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff8167337a)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff81679772)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff8167fed6)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/mmc/core/bus.c (ffffffff817246cc)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff81724ca3)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8172dcf2)
Location: include/linux/device.h:942
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff8149ede1)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff814a4705)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff814b68b9)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff815d3eb7)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8162f58f)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8163da68)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff81665dbf)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81696117)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff816a1039)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff816a7452)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff816adc13)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/mmc/core/bus.c (ffffffff8175764c)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff81757c23)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81760cb2)
Location: include/linux/device.h:1051
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff814a8c2f)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff814ae7c5)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff814c111d)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff815e8a3b)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81644655)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81652582)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff8167a562)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff816ab526)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff816b6106)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff816bc7a2)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff816c2dc2)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e0c06)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff817754e8)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff81775e8d)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8177f4eb)
Location: include/linux/device.h:1055
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff814e7c5f)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff814edb95)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8150154d)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff8164fd4b)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff816ad5e8)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816bb99a)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff816e3bc2)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81716986)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff8172199c)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff81728172)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff8172eb92)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174d49d)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff817eb7c8)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff817ec21d)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff817f5a9c)
Location: include/linux/device.h:1053
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff8151731a)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff8151d7c5)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8153052b)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff8168b36a)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff816e9ed8)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816f7d9f)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff8172043e)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817557ad)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff81760730)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff81766fc2)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff8176dcb1)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178dc80)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff818349d0)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff8183540d)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8183ef5c)
Location: include/linux/device.h:1098
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff8152cd9a)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81532f05)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815479eb)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff816ab59a)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8170d99c)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8171a69f)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff81742d2e)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81779cdd)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff81784df1)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff8178b542)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff81792331)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817b427d)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff81860960)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff818613c0)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8186af0d)
Location: include/linux/device.h:1151
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff8155b6a2)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81562675)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81577ae8)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff816e514a)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff817491e5)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81755d95)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff8177e9ea)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817ba7a5)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff817c2f00)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff817c9b52)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff817d0c78)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817f37d6)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff818a4681)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff818a50d6)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818aedfd)
Location: include/linux/device.h:1174
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff8157c752)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81583815)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81599268)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff8170942a)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8176d335)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8177a015)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff817a26aa)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817eb01f)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff817f3880)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff817fa692)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff81801b78)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81824686)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff818d6b01)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff818d7556)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818e12ad)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff81621c83)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff8162a375)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81638b9b)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
```
```
In drivers/base/power/sysfs.c (ffffffff817c447a)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8182f8ff)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183d06b)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff818664da)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff818ba674)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff818c33cd)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff818ca8b2)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff818d23fd)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f62e6)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff819a9461)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff819a9ec6)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b43ad)
Location: include/linux/device.h:723
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff81648843)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff816507d5)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8165f6ab)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_device_init
```
```
In drivers/base/power/sysfs.c (ffffffff817d8f5a)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81c16411)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8184d86b)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff818752ea)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81c1b19a)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff818cf6b0)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff818d59c2)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff818dc7dd)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818fee96)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff81c2a376)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff819aca93)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b69fd)
Location: include/linux/device.h:691
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff8162b445)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff816333e5)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff81641c97)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff817bd32a)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81c0811b)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81830d21)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff81857aea)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81c0d03d)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff818b2cdc)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff818b8f12)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff818bfa6c)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e25f7)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff81c1c734)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff81990f33)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8199b1ad)
Location: include/linux/device.h:697
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff8169a912)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff816a3585)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff816b2931)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff818476aa)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81d0bf9f)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bcd55)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff818e650a)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81d13fea)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff8194800a)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff8194e9d2)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff819560dc)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e777)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff81d2d34a)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff81a3c9b3)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81a47aed)
Location: include/linux/device.h:714
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff817bc0b3)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff817c57f1)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff817d6299)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff8198c1ba)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81ed4edf)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a050af)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a08f25)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff81a3798a)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81edeb57)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff81aa0aad)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff81aa7a22)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff81aafc72)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ad9ea4)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b31788)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b3a030)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/bus.c (ffffffff81ef97e0)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff81ba9a6b)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81bb5a6d)
Location: include/linux/device.h:789
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff818d7cc9)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff818e2911)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv.c (ffffffff818f7b0b)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/base/power/sysfs.c (ffffffff81afbc9a)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81b76eb4)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b83d5f)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b882f9)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff81bbc8ae)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81c18aef)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff81c2601a)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff81c2e972)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff81c37c92)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c64f87)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc62d8)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf9b0)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/bus.c (ffffffff81d4b906)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff81d4c87b)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81d5a32d)
Location: include/linux/device.h:786
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff8191af59)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81925d51)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv.c (ffffffff8193af64)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/base/power/sysfs.c (ffffffff81b4a08a)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81bcab44)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd7acc)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdc1d5)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff81c1411e)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81c7fac8)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff81c8cfca)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff81c95bd2)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff81c9f022)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccc3b7)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2df68)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37aa9)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/bus.c (ffffffff81db61b6)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff81db714b)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4ccd)
Location: include/linux/device.h:912
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff81963389)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff8196e4d1)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983df7)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/base/power/sysfs.c (ffffffff81ba247a)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81c1f774)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c76c)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c30f05)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff81c692f0)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81d344c3)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff81d41aeb)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff81d4a6c1)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff81d53c70)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d812af)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de3efb)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedd29)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/bus.c (ffffffff81e6e64d)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff81e6f61b)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d60d)
Location: include/linux/device.h:944
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffff8000106dfdb4)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffff8000106e7814)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffff8000107008fc)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffff8000108f7250)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffff80001096f9f8)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097f6fc)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffff8000109ae67c)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffff800010a175c8)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffff800010a24440)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffff800010a2bd18)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffff800010a35fe0)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/mmc/core/bus.c (ffff800010b30b2c)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffff800010b318d4)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b64c)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (c087ba34)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (c08828f4)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (c08986ac)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (c09e31d0)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (c0a44c6c)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (c0a52518)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (c0a7dadc)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (c0aef684)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (c0afa990)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (c0b015fc)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (c0b094fc)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/mmc/core/bus.c (c0c0b884)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (c0c0c574)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (c0c15f18)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (c0000000008589d8)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (c000000000862014)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/sysfs.c (c000000000992968)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (c000000000a2909c)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (c000000000a3b1c4)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (c000000000a75860)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (c000000000ad02ac)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (c000000000adf32c)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (c000000000ae8d70)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (c000000000af4074)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/mmc/core/bus.c (c000000000c2a6dc)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (c000000000c2b6ac)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (c000000000c38294)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffe0004b7ce2)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffe0004bdede)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffe0004cf856)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/scsi/hosts.c (ffffffe0005d99c6)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffe0005e5980)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffe00060b5b0)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffe00063c444)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffe000646a32)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffe00064d07e)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffe000653512)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/mmc/core/bus.c (ffffffe00070967e)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffe00070a2e4)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffe000712d84)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff81570c72)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81577d35)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158d0f8)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff816ceb7a)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff81721a25)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8172e705)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff8176776a)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817a33ff)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff817abc60)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff817b2a72)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff817b9f58)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817dca66)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff8187a4c1)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff8187af16)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81884c6d)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff8155f3d2)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81566475)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8157bc38)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff816a9eaa)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff816fae55)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81707b25)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff817475ca)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817922bb)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff8179d660)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff817a44a2)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff817ab988)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/pci/probe.c (ffffffff815704a2)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81577565)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158cfb8)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff816fd0ea)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff817607f5)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8176d4d5)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff8179752a)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817dfe9f)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff817e8700)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff817ef512)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff817f69f8)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81819506)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff818cb961)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff818cc3b6)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818d610d)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
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
In drivers/pci/probe.c (ffffffff8158a982)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci.c (ffffffff81591a25)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pcie/portdrv_core.c (ffffffff815a7468)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
```
In drivers/base/power/sysfs.c (ffffffff8171797a)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:async_store
```
```
In drivers/scsi/hosts.c (ffffffff8177be55)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81788c75)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff817b139a)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817fa18f)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/message.c (ffffffff8180294e)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/endpoint.c (ffffffff81809752)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/port.c (ffffffff81810c38)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818334f6)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/mmc/core/bus.c (ffffffff818e8481)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/host.c (ffffffff818e8ed6)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_alloc_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818f2c2d)
Location: include/linux/device.h:1416
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_add_func
```
</details>
</li>
</ul>

## Differences
