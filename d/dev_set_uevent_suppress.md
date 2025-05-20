# Function: <code>dev_set_uevent_suppress</code>

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
In kernel/workqueue.c (ffffffff8109d4ad)
Location: include/linux/device.h:916
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff813cb168)
Location: include/linux/device.h:916
Inline: True
Inline callers:
  - block/genhd.c:add_disk
  - block/genhd.c:add_disk
```
```
In block/partition-generic.c (ffffffff813cd5e3)
Location: include/linux/device.h:916
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff81480917)
Location: include/linux/device.h:916
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_add_finalize
```
```
In drivers/acpi/dock.c (ffffffff81485339)
Location: include/linux/device.h:916
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/base/firmware_class.c (ffffffff8155f935)
Location: include/linux/device.h:916
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
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
In kernel/workqueue.c (ffffffff810a0b49)
Location: include/linux/device.h:932
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff8140f42f)
Location: include/linux/device.h:932
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
```
```
In block/partition-generic.c (ffffffff81411a24)
Location: include/linux/device.h:932
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff814cf34c)
Location: include/linux/device.h:932
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add_finalize
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff814d3ec3)
Location: include/linux/device.h:932
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/base/firmware_class.c (ffffffff815b3f1a)
Location: include/linux/device.h:932
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
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
In kernel/workqueue.c (ffffffff810a5c19)
Location: include/linux/device.h:1041
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff8142a7cc)
Location: include/linux/device.h:1041
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
```
```
In block/partition-generic.c (ffffffff8142cdb3)
Location: include/linux/device.h:1041
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff814f12b6)
Location: include/linux/device.h:1041
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_add_finalize
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff814f6512)
Location: include/linux/device.h:1041
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/base/firmware_class.c (ffffffff815e31c8)
Location: include/linux/device.h:1041
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
```
In net/core/net-sysfs.c (ffffffff817d2226)
Location: include/linux/device.h:1041
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810a2c85)
Location: include/linux/device.h:1045
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff81438a90)
Location: include/linux/device.h:1045
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
```
```
In block/partition-generic.c (ffffffff8143a0c4)
Location: include/linux/device.h:1045
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff814fef0c)
Location: include/linux/device.h:1045
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff81504b1c)
Location: include/linux/device.h:1045
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff815746a4)
Location: include/linux/device.h:1045
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_class.c (ffffffff815f8077)
Location: include/linux/device.h:1045
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
```
In net/core/net-sysfs.c (ffffffff817f1606)
Location: include/linux/device.h:1045
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810a95b5)
Location: include/linux/device.h:1043
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff814649db)
Location: include/linux/device.h:1043
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
```
```
In block/partition-generic.c (ffffffff814660e4)
Location: include/linux/device.h:1043
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff81540f0b)
Location: include/linux/device.h:1043
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff81546e3c)
Location: include/linux/device.h:1043
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff815d7824)
Location: include/linux/device.h:1043
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_class.c (ffffffff81660040)
Location: include/linux/device.h:1043
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
```
In net/core/net-sysfs.c (ffffffff8186cbe6)
Location: include/linux/device.h:1043
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810afce2)
Location: include/linux/device.h:1088
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff814982f2)
Location: include/linux/device.h:1088
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (ffffffff81499a8e)
Location: include/linux/device.h:1088
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff81576dd4)
Location: include/linux/device.h:1088
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff8157cefd)
Location: include/linux/device.h:1088
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff8161059b)
Location: include/linux/device.h:1088
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8169bb28)
Location: include/linux/device.h:1088
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
```
In net/core/net-sysfs.c (ffffffff818bd4f6)
Location: include/linux/device.h:1088
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810b8e52)
Location: include/linux/device.h:1141
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff814b2414)
Location: include/linux/device.h:1141
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (ffffffff814b3d3a)
Location: include/linux/device.h:1141
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff8158e9c7)
Location: include/linux/device.h:1141
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff81594bdd)
Location: include/linux/device.h:1141
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff8162d39b)
Location: include/linux/device.h:1141
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bc3ca)
Location: include/linux/device.h:1141
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
```
In net/core/net-sysfs.c (ffffffff818e48c6)
Location: include/linux/device.h:1141
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810be953)
Location: include/linux/device.h:1164
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff814e07a7)
Location: include/linux/device.h:1164
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (ffffffff814e228a)
Location: include/linux/device.h:1164
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff815bf731)
Location: include/linux/device.h:1164
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff815c5c4d)
Location: include/linux/device.h:1164
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff81660fce)
Location: include/linux/device.h:1164
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816f6a2f)
Location: include/linux/device.h:1164
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
```
In net/core/net-sysfs.c (ffffffff81933f06)
Location: include/linux/device.h:1164
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810c4eff)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff814f9c0b)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (ffffffff814fb64a)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff815e09f1)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff815e6e7d)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff8168361e)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8171ae22)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
```
In drivers/usb/core/devio.c (ffffffff817faac4)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff81966a26)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810cc91f)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff8155a238)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
```
```
In block/partitions/core.c (ffffffff8155d5c7)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff8168bccb)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff8169269a)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff81734969)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817d6a06)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/usb/core/devio.c (ffffffff818cad64)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff81a3a156)
Location: include/linux/device.h:713
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810c7a9f)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff8157600b)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
```
```
In block/partitions/core.c (ffffffff81579338)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff816a9b4e)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff816b014a)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff817507a9)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817eb5ae)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/usb/core/devio.c (ffffffff818d5e54)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff81a3c6d9)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810c952f)
Location: include/linux/device.h:687
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff8157de78)
Location: include/linux/device.h:687
Inline: True
Inline callers:
  - block/genhd.c:register_disk
  - block/genhd.c:register_disk
```
```
In block/partitions/core.c (ffffffff81581326)
Location: include/linux/device.h:687
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff8168c374)
Location: include/linux/device.h:687
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff8169272a)
Location: include/linux/device.h:687
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff81734629)
Location: include/linux/device.h:687
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817cfd6e)
Location: include/linux/device.h:687
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/usb/core/devio.c (ffffffff818b9394)
Location: include/linux/device.h:687
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff81a234e9)
Location: include/linux/device.h:687
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810dc22f)
Location: include/linux/device.h:704
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff815e3a83)
Location: include/linux/device.h:704
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
```
```
In block/partitions/core.c (ffffffff815e66a6)
Location: include/linux/device.h:704
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff81701be8)
Location: include/linux/device.h:704
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff8170827a)
Location: include/linux/device.h:704
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff817b4f89)
Location: include/linux/device.h:704
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8185a57e)
Location: include/linux/device.h:704
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/usb/core/devio.c (ffffffff8194ee74)
Location: include/linux/device.h:704
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff81ad7ae9)
Location: include/linux/device.h:704
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810f597f)
Location: include/linux/device.h:779
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff81693501)
Location: include/linux/device.h:779
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
```
```
In block/partitions/core.c (ffffffff816955c9)
Location: include/linux/device.h:779
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff8182f86c)
Location: include/linux/device.h:779
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff818365da)
Location: include/linux/device.h:779
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff818f0e8d)
Location: include/linux/device.h:779
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff819a0a8e)
Location: include/linux/device.h:779
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/block/loop.c (ffffffff819b793a)
Location: include/linux/device.h:779
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/usb/core/devio.c (ffffffff81aa7f44)
Location: include/linux/device.h:779
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff81c58859)
Location: include/linux/device.h:779
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff81117eaf)
Location: include/linux/device.h:776
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff817521c6)
Location: include/linux/device.h:776
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
```
```
In block/partitions/core.c (ffffffff81754769)
Location: include/linux/device.h:776
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff819628f3)
Location: include/linux/device.h:776
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff8196a5fa)
Location: include/linux/device.h:776
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff81a48fcd)
Location: include/linux/device.h:776
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81b126af)
Location: include/linux/device.h:776
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/block/loop.c (ffffffff81b2cc7a)
Location: include/linux/device.h:776
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/usb/core/devio.c (ffffffff81c2ef54)
Location: include/linux/device.h:776
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff81e0e719)
Location: include/linux/device.h:776
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff811250cf)
Location: include/linux/device.h:902
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff8178e361)
Location: include/linux/device.h:902
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
```
```
In block/partitions/core.c (ffffffff8179086b)
Location: include/linux/device.h:902
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff819a8d08)
Location: include/linux/device.h:902
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff819b0bba)
Location: include/linux/device.h:902
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff81a9320a)
Location: include/linux/device.h:902
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81b6099f)
Location: include/linux/device.h:902
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/block/loop.c (ffffffff81b7d042)
Location: include/linux/device.h:902
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/usb/core/devio.c (ffffffff81c961ba)
Location: include/linux/device.h:902
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff81e81b59)
Location: include/linux/device.h:902
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff8112f8ce)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff817d0bfc)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
  - block/genhd.c:device_add_disk
```
```
In block/partitions/core.c (ffffffff817d40f0)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff819f1747)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff819fb0cf)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff81ae5c89)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81bb43de)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/base/devcoredump.c (ffffffff81bccf41)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/loop.c (ffffffff81bd0fcd)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/usb/core/devio.c (ffffffff81d4ac9a)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/dev.c (ffffffff81ef6c16)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_change_net_namespace
```
```
In net/core/net-sysfs.c (ffffffff81f42b39)
Location: include/linux/device.h:934
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffff8000101233c4)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffff8000105fb714)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (ffff8000105fd600)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffff80001076d308)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffff800010774034)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffff80001084f754)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffff80001090e6e0)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
```
In drivers/usb/core/devio.c (ffff800010a2c444)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffff800010c0c18c)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (c0376cc8)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (c07a66e8)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (c07a84dc)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/tty/tty_io.c (c095b0e0)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (c09f7558)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
```
In drivers/usb/core/devio.c (c0b01b90)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (c0d246cc)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (c00000000016d338)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (c000000000794934)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (c000000000796ee0)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/tty/tty_io.c (c0000000008f1da8)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (c0000000009aef5c)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
```
```
In drivers/usb/core/devio.c (c000000000ae9514)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (c000000000cf7450)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffe0000dbb9c)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffe0004377d2)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (ffffffe0004391c4)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/tty/tty_io.c (ffffffe00052e210)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffe000592d72)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
```
In drivers/usb/core/devio.c (ffffffe00064d526)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffe00078954c)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810bf26f)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff814f21eb)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (ffffffff814f3c2a)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff815d2df1)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/tty/tty_io.c (ffffffff8164909e)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816e1152)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
```
In drivers/usb/core/devio.c (ffffffff817b2ea4)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff819069f6)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810ada8f)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff814e271b)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (ffffffff814e413a)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff815bc9b1)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/tty/tty_io.c (ffffffff816294fe)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bb792)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
```
In drivers/usb/core/devio.c (ffffffff817a48d4)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff818c0826)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810be7cf)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff814ee27b)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (ffffffff814efcba)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff815d4cd1)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff815db15d)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff8167745e)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8170e822)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
```
In drivers/usb/core/devio.c (ffffffff817ef944)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff81957a26)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
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
In kernel/workqueue.c (ffffffff810c6b3f)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:workqueue_sysfs_register
```
```
In block/genhd.c (ffffffff8150730b)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
```
```
In block/partition-generic.c (ffffffff81508d4a)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:add_partition
```
```
In drivers/acpi/scan.c (ffffffff815eeb91)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
```
```
In drivers/acpi/dock.c (ffffffff815f501d)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/acpi/dock.c:acpi_dock_add
```
```
In drivers/tty/tty_io.c (ffffffff81691c9e)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81729442)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
```
In drivers/usb/core/devio.c (ffffffff81809b84)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:claimintf
  - drivers/usb/core/devio.c:claimintf
```
```
In net/core/net-sysfs.c (ffffffff81979b06)
Location: include/linux/device.h:1406
Inline: True
Inline callers:
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
</details>
</li>
</ul>

## Differences
