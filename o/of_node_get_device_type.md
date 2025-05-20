# Function: <code>of_node_get_device_type</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/of/device.c (ffff800010b6cedc)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_get_modalias
```
```
In drivers/of/address.c (ffff800010b729cc)
Location: include/linux/of.h:1022
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
In drivers/of/device.c (c0c4feb4)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_get_modalias
```
```
In drivers/of/address.c (c0c566a8)
Location: include/linux/of.h:1022
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
In arch/powerpc/kernel/cacheinfo.c (c00000000002aaa8)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_online
```
```
In arch/powerpc/kernel/setup-common.c (c00000000002fdc0)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:check_legacy_ioport
```
```
In arch/powerpc/kernel/legacy_serial.c (c0000000000687e8)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - arch/powerpc/kernel/legacy_serial.c:of_node_is_type
```
```
In arch/powerpc/kernel/isa-bridge.c (c00000000006b8d0)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - arch/powerpc/kernel/isa-bridge.c:isa_bridge_notify
```
```
In arch/powerpc/kernel/pci_of_scan.c (c00000000006f220)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
```
```
In arch/powerpc/mm/numa.c (c0000000000a27f0)
Location: include/linux/of.h:1022
Inline: True
```
```
In arch/powerpc/platforms/pseries/setup.c (c0000000000eeb34)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:of_node_is_type
```
```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fafa8)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_notifier
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_memory_notifier
```
```
In arch/powerpc/platforms/pseries/vio.c (c000000000101024)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_find_node
  - arch/powerpc/platforms/pseries/vio.c:vio_find_node
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
```
```
In drivers/of/device.c (c000000000c475c8)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_get_modalias
```
```
In drivers/of/address.c (c000000000c50ed4)
Location: include/linux/of.h:1022
Inline: True
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
In drivers/of/device.c (ffffffe000721d4a)
Location: include/linux/of.h:1022
Inline: True
Inline callers:
  - drivers/of/device.c:of_device_uevent
  - drivers/of/device.c:of_device_get_modalias
```
```
In drivers/of/address.c (ffffffe0007265c0)
Location: include/linux/of.h:1022
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
