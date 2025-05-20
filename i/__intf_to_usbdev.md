# Function: <code>__intf_to_usbdev</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c11bd5)
Location: include/linux/usb.h:727
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
```
```
In drivers/usb/core/hub.c (ffffffff81c12365)
Location: include/linux/usb.h:727
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81c1cfe5)
Location: include/linux/usb.h:727
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff81c24074)
Location: include/linux/usb.h:727
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff81c26fa5)
Location: include/linux/usb.h:727
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_match_id
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
```
In drivers/usb/core/sysfs.c (ffffffff81c2e4d5)
Location: include/linux/usb.h:727
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/usb.c (ffffffff81c78995)
Location: include/linux/usb.h:743
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
```
```
In drivers/usb/core/hub.c (ffffffff81c79135)
Location: include/linux/usb.h:743
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81c83ef5)
Location: include/linux/usb.h:743
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff81c8b054)
Location: include/linux/usb.h:743
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff81c8df65)
Location: include/linux/usb.h:743
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_match_id
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
```
In drivers/usb/core/sysfs.c (ffffffff81c95735)
Location: include/linux/usb.h:743
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/usb.c (ffffffff81d2d395)
Location: include/linux/usb.h:735
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
```
```
In drivers/usb/core/hub.c (ffffffff81d2db45)
Location: include/linux/usb.h:735
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81d388f5)
Location: include/linux/usb.h:735
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff81d3faa4)
Location: include/linux/usb.h:735
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff81d42a85)
Location: include/linux/usb.h:735
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_match_id
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
```
In drivers/usb/core/sysfs.c (ffffffff81d4a1f5)
Location: include/linux/usb.h:735
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
