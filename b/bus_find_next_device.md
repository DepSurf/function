# Function: <code>bus_find_next_device</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157a535)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff8177b6a2)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff8161f695)
Location: include/linux/device/bus.h:222
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff8183ea22)
Location: include/linux/device/bus.h:222
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff81645dd5)
Location: include/linux/device/bus.h:222
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff8184f0c2)
Location: include/linux/device/bus.h:222
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff81628b55)
Location: include/linux/device/bus.h:222
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff81832562)
Location: include/linux/device/bus.h:222
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff816984e5)
Location: include/linux/device/bus.h:222
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff818be682)
Location: include/linux/device/bus.h:222
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff817b97e5)
Location: include/linux/device/bus.h:226
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff81a0a9f1)
Location: include/linux/device/bus.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff818d4465)
Location: include/linux/device/bus.h:226
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff81b8a171)
Location: include/linux/device/bus.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff819176b5)
Location: include/linux/device/bus.h:206
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff81bde101)
Location: include/linux/device/bus.h:206
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff8195f7c5)
Location: include/linux/device/bus.h:201
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff81c32ec1)
Location: include/linux/device/bus.h:201
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffff8000106dce54)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffff8000109813fc)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (c08789e4)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (c0a53e04)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (c000000000854fd0)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (c000000000a3d3cc)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffe0004b5294)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffe0005e6e24)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff8156ea55)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff8172fd92)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff8155d1b5)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff817091b2)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff8156e285)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff8176eb62)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
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
In drivers/pci/probe.c (ffffffff81588765)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/pci/probe.c:no_pci_devices
```
```
In drivers/scsi/scsi_proc.c (ffffffff8178a302)
Location: include/linux/device.h:236
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_seq_next
  - drivers/scsi/scsi_proc.c:scsi_seq_start
```
</details>
</li>
</ul>

## Differences
