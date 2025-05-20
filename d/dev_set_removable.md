# Function: <code>dev_set_removable</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81ce37d5)
Location: include/linux/device.h:801
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_setup_device
```
```
In drivers/usb/core/hub.c (ffffffff81d14010)
Location: include/linux/device.h:801
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
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
In drivers/pci/probe.c (ffffffff81eaa31c)
Location: include/linux/device.h:876
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_setup_device
```
```
In drivers/usb/core/hub.c (ffffffff81edeb77)
Location: include/linux/device.h:876
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
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
In drivers/pci/probe.c (ffffffff818d667b)
Location: include/linux/device.h:873
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_setup_device
```
```
In drivers/usb/core/hub.c (ffffffff81c18b0a)
Location: include/linux/device.h:873
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
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
In drivers/pci/probe.c (ffffffff819198eb)
Location: include/linux/device.h:999
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_setup_device
```
```
In drivers/usb/core/hub.c (ffffffff81c7fae2)
Location: include/linux/device.h:999
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
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
In drivers/pci/probe.c (ffffffff81961c6b)
Location: include/linux/device.h:1033
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_setup_device
```
```
In drivers/usb/core/hub.c (ffffffff81d344df)
Location: include/linux/device.h:1033
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/mmc/core/bus.c (ffffffff81e6e546)
Location: include/linux/device.h:1033
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
