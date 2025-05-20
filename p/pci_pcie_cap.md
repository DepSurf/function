# Function: <code>pci_pcie_cap</code>

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
In drivers/pci/access.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:1791
Inline: True
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
In drivers/pci/access.c (ffffffff81479a15)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (0)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (0)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149e09e)
Location: include/linux/pci.h:1865
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:1865
Inline: True
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
In drivers/pci/access.c (ffffffff8149aea5)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (0)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (0)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bfcce)
Location: include/linux/pci.h:1927
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:1927
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:1927
Inline: True
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
In drivers/pci/access.c (ffffffff814a4bc8)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814ca43e)
Location: include/linux/pci.h:1959
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:1959
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:1959
Inline: True
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
In drivers/pci/access.c (ffffffff814e39a8)
Location: include/linux/pci.h:2015
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/pci/pcie/aer/aerdrv_acpi.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8150a9f6)
Location: include/linux/pci.h:2015
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:2015
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:2015
Inline: True
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
In drivers/pci/access.c (ffffffff815133a6)
Location: include/linux/pci.h:2018
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2018
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8151c346)
Location: include/linux/pci.h:2018
Inline: True
Inline callers:
  - drivers/pci/pci.c:pcie_flr
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/pci.h:2018
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:2018
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:2018
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2018
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:2018
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:2018
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/pci.h:2018
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:2018
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:2018
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153b549)
Location: include/linux/pci.h:2018
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_enable_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_off_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_off
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_attention_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:2018
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:2018
Inline: True
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
In drivers/pci/access.c (ffffffff81528ae6)
Location: include/linux/pci.h:2065
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81531bb4)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81552a12)
Location: include/linux/pci.h:2065
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:2065
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:2065
Inline: True
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
In drivers/pci/access.c (ffffffff81557cd5)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81561254)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582893)
Location: include/linux/pci.h:2139
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_blink
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_green_led_on
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:2139
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:2139
Inline: True
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
In drivers/pci/access.c (ffffffff815792e5)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81582414)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/vc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a4273)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: include/linux/pci.h:2113
Inline: True
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
In drivers/pci/access.c (ffffffff8161e5f3)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff816202a0)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
```
```
In drivers/pci/pci.c (ffffffff8162b803)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
```
```
In drivers/pci/pci-driver.c (ffffffff8162d86d)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff8162f8c4)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-sysfs.c (ffffffff8162fa65)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
```
```
In drivers/pci/vc.c (ffffffff81637925)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81639065)
Location: include/linux/pci.h:2131
Inline: True
```
```
In drivers/pci/pcie/aspm.c (ffffffff8163b185)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
```
In drivers/pci/pcie/pme.c (ffffffff8163d730)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pcie/dpc.c (ffffffff8163e365)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
```
In drivers/pci/pcie/ptm.c (ffffffff8163e901)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff81640193)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff81645f7f)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164ce63)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (ffffffff81657285)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a52a4)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a4248)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a7052)
Location: include/linux/pci.h:2131
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_irqs_ioctl
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
In drivers/pci/access.c (ffffffff81644e23)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff81646930)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
```
```
In drivers/pci/pci.c (ffffffff81651502)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
```
```
In drivers/pci/pci-driver.c (ffffffff81652f5d)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff81654f54)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-sysfs.c (ffffffff816550f5)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
```
```
In drivers/pci/vc.c (ffffffff8165c2e5)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff8165fb48)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/aspm.c (ffffffff816619d5)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
```
In drivers/pci/pcie/pme.c (ffffffff81663dc0)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pcie/dpc.c (ffffffff81664a85)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
```
In drivers/pci/pcie/ptm.c (ffffffff81664c41)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
```
```
In drivers/pci/pci-acpi.c (ffffffff816665a3)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff8166c354)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816711b3)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (ffffffff81677845)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b26f6)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b3287)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5f42)
Location: include/linux/pci.h:2135
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_irqs_ioctl
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
In drivers/pci/access.c (ffffffff81627ac3)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff81629650)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
```
```
In drivers/pci/pci.c (ffffffff81633f82)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
```
```
In drivers/pci/pci-driver.c (ffffffff81635a11)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff81637ad4)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-sysfs.c (ffffffff81637d25)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
```
```
In drivers/pci/vc.c (ffffffff8163e895)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff81642028)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/aspm.c (ffffffff816435c5)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
```
```
In drivers/pci/pcie/aer.c (ffffffff81645288)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/pme.c (ffffffff81646230)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pcie/dpc.c (ffffffff81646f15)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
```
In drivers/pci/pcie/ptm.c (ffffffff816471f1)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
```
```
In drivers/pci/pci-acpi.c (ffffffff81648a53)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff8164e894)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816536c3)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (ffffffff81659df5)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff817955e6)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81896462)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818993f2)
Location: include/linux/pci.h:2174
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_irqs_ioctl
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
In drivers/pci/access.c (ffffffff816973c3)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_read_word
```
```
In drivers/pci/probe.c (ffffffff81699030)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
```
```
In drivers/pci/pci.c (ffffffff816a4162)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
```
```
In drivers/pci/pci-driver.c (ffffffff816a5c01)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff816a7d64)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a7f95)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
```
```
In drivers/pci/vc.c (ffffffff816af425)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff816b2cfa)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/aspm.c (ffffffff816b4315)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
```
```
In drivers/pci/pcie/aer.c (ffffffff816b611e)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/pme.c (ffffffff816b7ab0)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pcie/dpc.c (ffffffff816b87c5)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
```
In drivers/pci/pcie/ptm.c (ffffffff816b8ad1)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
```
```
In drivers/pci/pci-acpi.c (ffffffff816ba473)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff816c0584)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c5448)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (ffffffff816cc125)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181d456)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_find_matched_atsr_unit
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192a418)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_get_irq_count
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192cf12)
Location: include/linux/pci.h:2235
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_irqs_ioctl
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
In drivers/pci/access.c (ffffffff817b89f3)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
```
```
In drivers/pci/probe.c (ffffffff817ba50f)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
```
```
In drivers/pci/pci.c (ffffffff817c6552)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
```
```
In drivers/pci/pci-driver.c (ffffffff817c8f63)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff817ca855)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-sysfs.c (ffffffff817caae5)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
```
```
In drivers/pci/vc.c (ffffffff817d28f5)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffff817d671a)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/aspm.c (ffffffff817d7875)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pci_restore_aspm_l1ss_state
  - drivers/pci/pcie/aspm.c:pci_save_aspm_l1ss_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
```
```
In drivers/pci/pcie/aer.c (ffffffff817d9d78)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/pme.c (ffffffff817dbf5c)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pcie/dpc.c (ffffffff817dcc35)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
```
In drivers/pci/pcie/ptm.c (ffffffff817dcfcc)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
  - drivers/pci/pcie/ptm.c:pci_restore_ptm_state
  - drivers/pci/pcie/ptm.c:pci_save_ptm_state
  - drivers/pci/pcie/ptm.c:pci_disable_ptm
```
```
In drivers/pci/pci-acpi.c (ffffffff817dfea4)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff817e5da5)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817e9bd8)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (ffffffff817f2825)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff819582ca)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a81782)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_get_irq_count
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a83640)
Location: include/linux/pci.h:2267
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_irqs_ioctl
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
In drivers/pci/access.c (ffffffff818d3463)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
```
```
In drivers/pci/probe.c (ffffffff818d54af)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
```
```
In drivers/pci/pci.c (ffffffff818e391c)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
```
```
In drivers/pci/pci-driver.c (ffffffff818e6883)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff818e8355)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e8645)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
```
```
In drivers/pci/vc.c (ffffffff818f31a5)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv.c (ffffffff818f7921)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/aspm.c (ffffffff818f8e95)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
```
```
In drivers/pci/pcie/aer.c (ffffffff818fb7b7)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/pme.c (ffffffff818fddac)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pcie/dpc.c (ffffffff818fefc5)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
```
In drivers/pci/pcie/ptm.c (ffffffff818ff86c)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff81902dd3)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff819084b5)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs_match
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8190fbf8)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81917379)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In drivers/pci/iov.c (ffffffff8191ae95)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abf38a)
Location: include/linux/pci.h:2306
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
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
In drivers/pci/access.c (ffffffff819164c7)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
```
```
In drivers/pci/probe.c (ffffffff8191870f)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
```
```
In drivers/pci/pci.c (ffffffff81926ec0)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_dev_wait
```
```
In drivers/pci/pci-driver.c (ffffffff81929eb5)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff8192b965)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192bc55)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
```
```
In drivers/pci/vc.c (ffffffff819365c5)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv.c (ffffffff8193ad91)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/aspm.c (ffffffff8193c225)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pci_enable_link_state
  - drivers/pci/pcie/aspm.c:pci_enable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
```
```
In drivers/pci/pcie/aer.c (ffffffff8193ed10)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/pme.c (ffffffff8194125c)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pcie/dpc.c (ffffffff81942555)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
```
In drivers/pci/pcie/ptm.c (ffffffff81942ddc)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff81946463)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff8194bb05)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs_match
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/quirks.c:pcie_failed_link_retrain
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81953318)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195a982)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In drivers/pci/iov.c (ffffffff8195e4a5)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0bd7a)
Location: include/linux/pci.h:2398
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
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
In drivers/pci/access.c (ffffffff8195e4f7)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_read_dword
  - drivers/pci/access.c:pcie_capability_read_word
  - drivers/pci/access.c:pcie_capability_reg_implemented
```
```
In drivers/pci/probe.c (ffffffff81960c6f)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_configure_mps
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_cfg_space_size
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/probe.c:pci_set_bus_speed
```
```
In drivers/pci/pci.c (ffffffff8196f660)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_acs_enabled
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_save_state
  - drivers/pci/pci.c:pci_dev_wait
```
```
In drivers/pci/pci-driver.c (ffffffff81972d6d)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (ffffffff819742b5)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-sysfs.c (ffffffff81974545)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
```
```
In drivers/pci/vc.c (ffffffff8197f425)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_enable
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983bf1)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/aspm.c (ffffffff81986095)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:aspm_ctrl_attrs_are_visible
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:clkpm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_1_pcipm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_2_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l1_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:l0s_aspm_show
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_capable
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:pcie_aspm_enabled
  - drivers/pci/pcie/aspm.c:__pci_enable_link_state
  - drivers/pci/pcie/aspm.c:__pci_enable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:__pci_disable_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock
```
```
In drivers/pci/pcie/aer.c (ffffffff81987dd6)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_root_reset
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a4bc)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_from_pci_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pcie/dpc.c (ffffffff8198b7e5)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
```
In drivers/pci/pcie/ptm.c (ffffffff8198c0ac)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/pci-acpi.c (ffffffff8198f793)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:program_hpx_type2
  - drivers/pci/pci-acpi.c:program_hpx_type2
```
```
In drivers/pci/quirks.c (ffffffff81994dd5)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs_match
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_zhaoxin_pcie_ports_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes
  - drivers/pci/quirks.c:pcie_failed_link_retrain
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199c7a8)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a3f80)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
```
In drivers/pci/iov.c (ffffffff819a7b05)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b6035a)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_ats_supported
```
```
In arch/x86/pci/fixup.c (ffffffff82170c71)
Location: include/linux/pci.h:2469
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:amd_rp_pme_resume
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
In drivers/pci/access.c (ffff8000106dbb6c)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci.c (ffff8000106e5f54)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/vc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070cee4)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:2113
Inline: True
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
In drivers/pci/access.c (c0877e9c)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/probe.c (c08791d4)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (c08841d4)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (c08865f0)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (c0888210)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-sysfs.c (c08883f8)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
```
```
In drivers/pci/vc.c (c088fca8)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (c08953c0)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
```
```
In drivers/pci/pcie/portdrv_pci.c (c0898d84)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aspm.c (c0899444)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (c089c018)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (c089cdc4)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pcie/dpc.c (c089db5c)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
```
In drivers/pci/pcie/ptm.c (c089de74)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/iov.c (c08a2100)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
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
In drivers/pci/access.c (c000000000852eb0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/probe.c (c00000000085596c)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (c000000000864084)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/pci-driver.c (c000000000866428)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/pci/search.c (c000000000868ea8)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-sysfs.c (c000000000869188)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
```
```
In drivers/pci/vc.c (c000000000873d20)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (c00000000087b478)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
```
```
In drivers/pci/iov.c (c0000000008887e0)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab5d20)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab958c)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_irqs_ioctl
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
In drivers/pci/access.c (ffffffe0004b3fdc)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_dword
  - drivers/pci/access.c:pcie_capability_write_word
  - drivers/pci/access.c:pcie_capability_write_word
```
```
In drivers/pci/probe.c (ffffffe0004b5980)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pcie_bus_configure_settings
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_add_new_bus
  - drivers/pci/probe.c:pci_add_new_bus
```
```
In drivers/pci/pci.c (ffffffe0004bf616)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pcibios_set_master
  - drivers/pci/pci.c:pci_enable_atomic_ops_to_root
  - drivers/pci/pci.c:pci_configure_ari
  - drivers/pci/pci.c:pci_find_pcie_root_port
```
```
In drivers/pci/search.c (ffffffe0004c1d34)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/search.c:pci_for_each_dma_alias
```
```
In drivers/pci/pci-sysfs.c (ffffffe0004c1f34)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pcie_dev_attrs_are_visible
```
```
In drivers/pci/vc.c (ffffffe0004c8164)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
```
In drivers/pci/quirks.c (ffffffe0004cc994)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_intel_pch_acs
  - drivers/pci/quirks.c:pci_quirk_cavium_acs
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
  - drivers/pci/quirks.c:quirk_use_pcie_bridge_dma_alias
```
```
In drivers/pci/pcie/portdrv_pci.c (ffffffe0004cfdf2)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aspm.c (ffffffe0004d050a)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_get_link
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
  - drivers/pci/pcie/aspm.c:pcie_aspm_cap_init
```
```
In drivers/pci/pcie/aer.c (ffffffe0004d2e68)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_cleanup_aer_error_status_regs
```
```
In drivers/pci/pcie/pme.c (ffffffe0004d39a8)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pcie/dpc.c (ffffffe0004d4810)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:pci_restore_dpc_state
  - drivers/pci/pcie/dpc.c:pci_save_dpc_state
```
```
In drivers/pci/pcie/ptm.c (ffffffe0004d4afa)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
  - drivers/pci/pcie/ptm.c:pci_ptm_init
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d96fa)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (ffffffe0004e0c2c)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
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
In drivers/pci/access.c (ffffffff8156d805)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81576934)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/vc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597a83)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:2113
Inline: True
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
In drivers/pci/access.c (ffffffff8155bf75)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81565094)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/vc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81586c13)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: include/linux/pci.h:2113
Inline: True
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
In drivers/pci/access.c (ffffffff8156d035)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81576164)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/vc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597fc3)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: include/linux/pci.h:2113
Inline: True
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
In drivers/pci/access.c (ffffffff81587b35)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci.c (ffffffff81590644)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/search.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/vc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pci-acpi.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/portdrv_pci.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/pcie/ptm.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b2403)
Location: include/linux/pci.h:2113
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_set_indicators
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status
```
```
In drivers/pci/iov.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_intrs.c (0)
Location: include/linux/pci.h:2113
Inline: True
```
</details>
</li>
</ul>

## Differences
