# Function: <code>pm_runtime_get_noresume</code>

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
In drivers/pci/pci.c (ffffffff814372ec)
Location: include/linux/pm_runtime.h:65
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/base/core.c (ffffffff8154937f)
Location: include/linux/pm_runtime.h:65
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff81556714)
Location: include/linux/pm_runtime.h:65
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_disable
```
```
In drivers/base/power/main.c (ffffffff8155b55b)
Location: include/linux/pm_runtime.h:65
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/usb/core/hub.c (ffffffff8160857b)
Location: include/linux/pm_runtime.h:65
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:hub_event
```
```
In drivers/usb/core/hcd.c (ffffffff8160c024)
Location: include/linux/pm_runtime.h:65
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81613882)
Location: include/linux/pm_runtime.h:65
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff8161ed6a)
Location: include/linux/pm_runtime.h:65
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8161fdeb)
Location: include/linux/pm_runtime.h:65
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816623e1)
Location: include/linux/pm_runtime.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
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
In drivers/pci/pci.c (ffffffff81482eac)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81495397)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/base/core.c (ffffffff8159b002)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff815a9d54)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff815ad56e)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff815fff1e)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff8166a134)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff8166bbde)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81673852)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff8167fec6)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8168079b)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c2611)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
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
In drivers/pci/pci.c (ffffffff814a443c)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814b6d47)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/base/core.c (ffffffff815c9562)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff815d8124)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff815dc32e)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff8162f56f)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81697e64)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff816998de)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff816a14e2)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff816adc03)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816ae4cb)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f05d1)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
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
In drivers/pci/pci.c (ffffffff814ae4fc)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff814c1687)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/base/core.c (ffffffff815de282)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff815ed06b)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff815f0eaa)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff81644635)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff816ad96e)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff816aec0e)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff816b65d2)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff816c2db3)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816c30f8)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705e49)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726f7f)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff8177e848)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff814ed8cc)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff815019f7)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/clk/clk.c (ffffffff815a7b00)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff81645282)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff8165441b)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81658327)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff816ad5c8)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81718798)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff8171a1fb)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81721e62)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff8172eb83)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8172eec8)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81777019)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817985cf)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798c46)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff817f4dec)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff8151d52c)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81530a14)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/clk/clk.c (ffffffff815df745)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff816806cc)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff8168fa46)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81693d39)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff816e9eb8)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81757bc6)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff81758fbb)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81760c92)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff8176dca2)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8176e468)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817b7d90)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817db2de)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817dba4e)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff8183e1f8)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff81532c2c)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81547ff4)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8155183a)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff815f9465)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff816a015c)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff816afdd6)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff816b43b9)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff8170d97c)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff8177c136)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff8177d52b)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81785677)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff81792322)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81792ae8)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817de484)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818021ae)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802df7)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff8186a1a8)
Location: include/linux/pm_runtime.h:69
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff8156237c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81578087)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8158179a)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8162b76f)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff816d886b)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff816e9cce)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff816ee283)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff817491c2)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff817b9a74)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff817bb9de)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817c3b90)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff817d0c67)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817d1015)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8181ef14)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818439fa)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818441fe)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff818ae078)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff8158351c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81599817)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a329a)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8164d2df)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff816fc970)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff8170dd2e)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81712261)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff8176d312)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff817ea2c4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff817ec20e)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817f4650)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff81801b67)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81801ee5)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818503d4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8187537b)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875b74)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff818e0528)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff8162a0dc)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81638ff7)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164be2d)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff816fc0ef)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff817b6356)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff817c904c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff817cb7a1)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
```
```
In drivers/scsi/hosts.c (ffffffff8182f8dc)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff818b96f9)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff818bb81e)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818c4220)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff818d23ec)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818d2a15)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194997c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a51f)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff819b34fa)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff8165053c)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8165fb07)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8167017d)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff81718fef)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff817cb7c6)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff817dde1c)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff817e0211)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
```
```
In drivers/scsi/hosts.c (ffffffff81c163ee)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff818c7fd9)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff818c85fe)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818d0110)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff818dc7cc)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818dce24)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f53c)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819500af)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff819b5a4a)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff816330ec)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81641fe7)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8165267d)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff816fa2ef)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff817af136)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff817c219c)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff817c4a51)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
```
```
In drivers/scsi/hosts.c (ffffffff81c080f8)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff818ab649)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff818abc52)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818b3740)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff818bfa5b)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818c0194)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819339d3)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933f61)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff8199a25a)
Location: include/linux/pm_runtime.h:92
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff816a325c)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff816b2cb7)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c43d9)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8177500b)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff81838358)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff8184bafc)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff8184ee35)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
```
```
In drivers/scsi/hosts.c (ffffffff81d0bf7c)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff819405c9)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff81940f13)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81948bd0)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff819560cb)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff819568e4)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci.c (ffffffff8199408f)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6da3)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d736f)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81a46b10)
Location: include/linux/pm_runtime.h:95
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff817c545c)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff817d66ce)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817ea033)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff818aad17)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff8197a6ca)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff8199159a)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81993365)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
```
```
In drivers/scsi/hosts.c (ffffffff81ed4ebf)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a8115c)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_unregister_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
```
```
In drivers/usb/core/hub.c (ffffffff81a98702)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff81a99313)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81aa1720)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff81aafc63)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ab04d6)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci.c (ffffffff81af0b63)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39954)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b3a08f)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb48ee)
Location: include/linux/pm_runtime.h:125
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff818e251c)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv.c (ffffffff818f7c91)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819100d3)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff819f6307)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff81ae753a)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff81b0194a)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81b03a05)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
```
```
In drivers/scsi/hosts.c (ffffffff81b76e9b)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81c1b5c6)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff81c1d2d3)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81c26fc0)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff81c37c83)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c38666)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci.c (ffffffff81c7da86)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf050)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccfa0f)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81d58fa1)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff8192595c)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv.c (ffffffff8193b0f1)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819537f3)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff81a3ea45)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff81b35924)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff81b4fa7a)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81b51a65)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
```
```
In drivers/scsi/hosts.c (ffffffff81bcab2b)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81c824eb)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff81c841e4)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81c8df83)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff81c9f013)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f9e6)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci.c (ffffffff81ce4cf6)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d3710e)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37b08)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc394d)
Location: include/linux/pm_runtime.h:129
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff8196e0dc)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983f81)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199cc83)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff81a8a375)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff81b8d344)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff81ba7ffa)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81baa055)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
```
```
In drivers/scsi/hosts.c (ffffffff81c1f75b)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81d36e2b)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff81d38be4)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81d42aa3)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff81d53c61)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d54636)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci.c (ffffffff81d99d66)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded346)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedd88)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7c22d)
Location: include/linux/pm_runtime.h:127
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffff8000106e748c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffff8000107010e0)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070bd3c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/amba/bus.c (ffff8000107b9434)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/clk/clk.c (ffff8000107bf7bc)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffff8000108e7380)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffff8000108fd520)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffff800010902c74)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffff80001096f9cc)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9b84)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/core/hub.c (ffff800010a19ad8)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffff800010a1c2d8)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffff800010a259d8)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffff800010a35fc4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a37340)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90f0c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba0e4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010ababc4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a744)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (c08825c8)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (c0898ce4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/amba/bus.c (c08e5740)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/clk/clk.c (c08e8180)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/iommu/exynos-iommu.c (c09ca0e0)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_attach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_detach_device
```
```
In drivers/base/core.c (c09d598c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (c09e88b0)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (c09ed0ac)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (c0a44c40)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acae5c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/core/hub.c (c0af1d88)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (c0af3170)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (c0afb7b4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (c0b094d8)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (c0b09a28)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (c0b63374)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b997f0)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99f0c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (c0c1513c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/host/sdhci.c (c0c25ce8)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
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
In drivers/pci/pci.c (c000000000861c04)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/base/core.c (c00000000097d674)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (c000000000999e24)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (c0000000009a1200)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (c000000000a29070)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (c000000000ad3054)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (c000000000ad475c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (c000000000ae029c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (c000000000af4054)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (c000000000af4d98)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (c000000000b6c660)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d2b0)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9de94)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (c000000000c37040)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffe0004bdc26)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffe0004cfd6e)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8708)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffe00050b0ee)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffe00057baba)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffe00058c258)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/scsi/hosts.c (ffffffe0005d99a6)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffe00063e5c8)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffe00063f7e8)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffe0006474be)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffe0006534fe)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffe000653d0c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffe0006a3964)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006be9de)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf332)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffe000712188)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff81577a3c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d6a7)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81596aaa)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8161333f)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff816c2160)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff816d347e)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff816d85e1)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff81721a02)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff817a26a4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff817a45ee)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817aca30)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff817b9f47)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ba2c5)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818061a4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81883ee8)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff8156617c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8157c1e7)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81585c3a)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8160786f)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff8169d410)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff816ae748)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff816b2c41)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff816fae32)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff817944e4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff8179615e)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8179e430)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff817ab977)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817abcf5)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci.c (ffffffff817b4fb5)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817cd924)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
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
In drivers/pci/pci.c (ffffffff8157726c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8158d567)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81596fea)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8164111f)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff816f0630)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff817019ee)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81705f21)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff817607d2)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff817df144)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff817e108e)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817e94d0)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff817f69e7)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817f6d65)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81845254)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-amd-mp2-pci.c (ffffffff818681bf)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_remove
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a82b)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186b024)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff818d5388)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff8159172c)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff815a7a17)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b142a)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffff8165b49f)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff8170ae6e)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/core.c:device_shutdown
```
```
In drivers/base/power/runtime.c (ffffffff8171c645)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff817208ec)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/hosts.c (ffffffff8177be32)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff817f9434)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/hcd.c (ffffffff817fb37e)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_start_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81803a00)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
```
```
In drivers/usb/core/port.c (ffffffff81810c27)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81810fa5)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185f7d4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818847bb)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884fb4)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff818f1ea8)
Location: include/linux/pm_runtime.h:68
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
</details>
</li>
</ul>

## Differences
