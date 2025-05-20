# Function: <code>set_dev_node</code>

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
In arch/x86/kernel/quirks.c (ffffffff81035776)
Location: include/linux/device.h:866
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff814315a3)
Location: include/linux/device.h:866
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_create_root_bus
```
```
In drivers/base/core.c (ffffffff815467a3)
Location: include/linux/device.h:866
Inline: True
Inline callers:
  - drivers/base/core.c:device_initialize
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
```
In drivers/nvdimm/bus.c (ffffffff81597a45)
Location: include/linux/device.h:866
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
```
```
In drivers/usb/core/usb.c (ffffffff81603773)
Location: include/linux/device.h:866
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff81034972)
Location: include/linux/device.h:882
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8147da56)
Location: include/linux/device.h:882
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/base/core.c (ffffffff81599c55)
Location: include/linux/device.h:882
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff815ecb25)
Location: include/linux/device.h:882
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
```
```
In drivers/usb/core/usb.c (ffffffff8166342a)
Location: include/linux/device.h:882
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff810345b2)
Location: include/linux/device.h:991
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8149e226)
Location: include/linux/device.h:991
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/base/core.c (ffffffff815c8206)
Location: include/linux/device.h:991
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff81619915)
Location: include/linux/device.h:991
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
```
```
In drivers/usb/core/usb.c (ffffffff81691228)
Location: include/linux/device.h:991
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff8103263e)
Location: include/linux/device.h:995
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff814a815d)
Location: include/linux/device.h:995
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff81508a7b)
Location: include/linux/device.h:995
Inline: True
```
```
In drivers/base/core.c (ffffffff815dceea)
Location: include/linux/device.h:995
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff8162de39)
Location: include/linux/device.h:995
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
```
```
In drivers/usb/core/usb.c (ffffffff816a6784)
Location: include/linux/device.h:995
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff8103496e)
Location: include/linux/device.h:993
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff814e719d)
Location: include/linux/device.h:993
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff8154ae5b)
Location: include/linux/device.h:993
Inline: True
```
```
In drivers/base/core.c (ffffffff81643eea)
Location: include/linux/device.h:993
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff816965e9)
Location: include/linux/device.h:993
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
```
```
In drivers/usb/core/usb.c (ffffffff81711b57)
Location: include/linux/device.h:993
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff8103599e)
Location: include/linux/device.h:1038
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff815167a6)
Location: include/linux/device.h:1038
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff81581504)
Location: include/linux/device.h:1038
Inline: True
```
```
In drivers/base/core.c (ffffffff8167f277)
Location: include/linux/device.h:1038
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff816d26d9)
Location: include/linux/device.h:1038
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
```
```
In drivers/usb/core/usb.c (ffffffff81750890)
Location: include/linux/device.h:1038
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff81036b7e)
Location: include/linux/device.h:1091
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8152c1b6)
Location: include/linux/device.h:1091
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff815995c7)
Location: include/linux/device.h:1091
Inline: True
```
```
In drivers/base/core.c (ffffffff8169f6b7)
Location: include/linux/device.h:1091
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff816f3de4)
Location: include/linux/device.h:1091
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff81774cda)
Location: include/linux/device.h:1091
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff81038bbe)
Location: include/linux/device.h:1114
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8155ab96)
Location: include/linux/device.h:1114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff815ca897)
Location: include/linux/device.h:1114
Inline: True
```
```
In drivers/base/core.c (ffffffff816d7e3b)
Location: include/linux/device.h:1114
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff8172d3c5)
Location: include/linux/device.h:1114
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff817b2dcc)
Location: include/linux/device.h:1114
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff8103938e)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8157bc26)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff815ebb17)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/base/core.c (ffffffff816fbf3b)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff817514b5)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff817e34fc)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff8103c18e)
Location: include/linux/device.h:663
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff81621433)
Location: include/linux/device.h:663
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff81697587)
Location: include/linux/device.h:663
Inline: True
```
```
In drivers/base/core.c (ffffffff817b589d)
Location: include/linux/device.h:663
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff8180fc65)
Location: include/linux/device.h:663
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff818b204c)
Location: include/linux/device.h:663
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff8103c8ee)
Location: include/linux/device.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff81647fb3)
Location: include/linux/device.h:631
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff816b46d7)
Location: include/linux/device.h:631
Inline: True
```
```
In drivers/base/core.c (ffffffff817cad0d)
Location: include/linux/device.h:631
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff8181eba5)
Location: include/linux/device.h:631
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff818c0a22)
Location: include/linux/device.h:631
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff8103e11e)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8162ab43)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff81696907)
Location: include/linux/device.h:637
Inline: True
```
```
In drivers/base/core.c (ffffffff817ae67d)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff81801ec5)
Location: include/linux/device.h:637
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff818a3ca2)
Location: include/linux/device.h:637
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff81043dce)
Location: include/linux/device.h:654
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8169a023)
Location: include/linux/device.h:654
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff8170c6a7)
Location: include/linux/device.h:654
Inline: True
```
```
In drivers/base/core.c (ffffffff8183789d)
Location: include/linux/device.h:654
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff8188c3a5)
Location: include/linux/device.h:654
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff81938902)
Location: include/linux/device.h:654
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff8104bf51)
Location: include/linux/device.h:729
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff817bb663)
Location: include/linux/device.h:729
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff8183adea)
Location: include/linux/device.h:729
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/base/core.c (ffffffff819799ca)
Location: include/linux/device.h:729
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff819d584d)
Location: include/linux/device.h:729
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff81a901a8)
Location: include/linux/device.h:729
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff81058231)
Location: include/linux/device.h:726
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff818d7163)
Location: include/linux/device.h:726
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff81970498)
Location: include/linux/device.h:726
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/base/core.c (ffffffff81ae67ca)
Location: include/linux/device.h:726
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff81b5031d)
Location: include/linux/device.h:726
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff81c120a8)
Location: include/linux/device.h:726
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff810593d1)
Location: include/linux/device.h:852
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8191a3e3)
Location: include/linux/device.h:852
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff819b6b15)
Location: include/linux/device.h:852
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/base/core.c (ffffffff81b34c4a)
Location: include/linux/device.h:852
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff81ba37ed)
Location: include/linux/device.h:852
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff81c78e6a)
Location: include/linux/device.h:852
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff810605f1)
Location: include/linux/device.h:884
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff819627e3)
Location: include/linux/device.h:884
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff81a010c5)
Location: include/linux/device.h:884
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/base/core.c (ffffffff81b8c67a)
Location: include/linux/device.h:884
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff81bf79dd)
Location: include/linux/device.h:884
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff81d2d895)
Location: include/linux/device.h:884
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/arm64/kernel/pci.c (ffff8000100a7c6c)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - arch/arm64/kernel/pci.c:pcibios_root_bridge_prepare
```
```
In drivers/pci/probe.c (ffff8000106df20c)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffff800010776fc8)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/acpi/arm64/iort.c (ffff800011481780)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/acpi/arm64/iort.c:arm_smmu_v3_set_proximity
```
```
In drivers/base/core.c (ffff8000108e6848)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffff80001095146c)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/usb/core/usb.c (ffff800010a11b10)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/of/device.c (ffff800010b6ce2c)
Location: include/linux/device.h:1356
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1365
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/device.h:1365
Inline: True
```
```
In drivers/usb/core/usb.c (0)
Location: include/linux/device.h:1365
Inline: True
```
```
In drivers/of/device.c (0)
Location: include/linux/device.h:1365
Inline: True
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
In arch/powerpc/kernel/pci-common.c (c00000000006bed4)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_device
```
```
In arch/powerpc/platforms/pseries/vio.c (c0000000001017bc)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
```
```
In drivers/pci/probe.c (c000000000857874)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/base/core.c (c00000000097c704)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (c0000000009fe588)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/usb/core/usb.c (c000000000ac8e00)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/of/device.c (c000000000c474d8)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/of/device.c:of_device_add
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1365
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/linux/device.h:1365
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/device.h:1365
Inline: True
```
```
In drivers/usb/core/usb.c (0)
Location: include/linux/device.h:1365
Inline: True
```
```
In drivers/of/device.c (0)
Location: include/linux/device.h:1365
Inline: True
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
In arch/x86/kernel/quirks.c (ffffffff810394ee)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff81570146)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff815daef7)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/base/core.c (ffffffff816c172b)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff81705ba5)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/nvme/host/pci.c (ffffffff8174e431)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In drivers/usb/core/usb.c (ffffffff8179b8dc)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff81028dfe)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8155e8a6)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff815c6537)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/base/core.c (ffffffff8169c9db)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff816d9625)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/nvme/host/pci.c (ffffffff8172e2d1)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In drivers/usb/core/usb.c (ffffffff8178d56c)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff8103934e)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8156f976)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff815dfdf7)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/base/core.c (ffffffff816efbfb)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff81744975)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff817d837c)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
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
In arch/x86/kernel/quirks.c (ffffffff8103a34e)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff81589e56)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/acpi_platform.c (ffffffff815f9cb7)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/base/core.c (ffffffff8170a43b)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_initialize
```
```
In drivers/nvdimm/bus.c (ffffffff8175fdb5)
Location: include/linux/device.h:1356
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff817f261c)
Location: include/linux/device.h:1356
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
</details>
</li>
</ul>

## Differences
