# Function: <code>interface_to_usbdev</code>

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
In drivers/usb/core/hub.c (ffffffff8160bcec)
Location: include/linux/usb.h:627
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/usb.h:627
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81611eaf)
Location: include/linux/usb.h:627
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
```
```
In drivers/usb/core/driver.c (ffffffff81613a77)
Location: include/linux/usb.h:627
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_match_one_id
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (0)
Location: include/linux/usb.h:627
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
In drivers/usb/core/hub.c (ffffffff8166b88c)
Location: include/linux/usb.h:623
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8166bdfb)
Location: include/linux/usb.h:623
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff81671e0f)
Location: include/linux/usb.h:623
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff8167418e)
Location: include/linux/usb.h:623
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_match_one_id
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff8167940e)
Location: include/linux/usb.h:623
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
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
In drivers/usb/core/hub.c (ffffffff816995b5)
Location: include/linux/usb.h:623
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81699afb)
Location: include/linux/usb.h:623
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff8169fabf)
Location: include/linux/usb.h:623
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff816a1e1e)
Location: include/linux/usb.h:623
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_match_one_id
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff816a70ee)
Location: include/linux/usb.h:623
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
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
In drivers/usb/core/hub.c (ffffffff816ae8e5)
Location: include/linux/usb.h:694
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff816aee30)
Location: include/linux/usb.h:694
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff816b4cff)
Location: include/linux/usb.h:694
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff816b6cee)
Location: include/linux/usb.h:694
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_match_one_id
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff816bc44f)
Location: include/linux/usb.h:694
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
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
In drivers/usb/core/hub.c (ffffffff81719ef5)
Location: include/linux/usb.h:695
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8171a434)
Location: include/linux/usb.h:695
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff8172016f)
Location: include/linux/usb.h:695
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff8172257e)
Location: include/linux/usb.h:695
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_match_one_id
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff81727e1f)
Location: include/linux/usb.h:695
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
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
In drivers/usb/core/hub.c (ffffffff817523b2)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817591a9)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff8175eaec)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (ffffffff81760c79)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_match_one_id
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff81766bf5)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/hub.c (ffffffff81776832)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff8177d719)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff8178326c)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (ffffffff8178565f)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_match_one_id
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff8178b175)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/hub.c (ffffffff817b4692)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817bbb29)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff817c196c)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (ffffffff817c3b7f)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817c9775)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/hub.c (ffffffff817e4dc2)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817ec359)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff817f22ec)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (ffffffff817f463f)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817fa2b5)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/hub.c (ffffffff818b3a15)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818bb965)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff818c1ad4)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff818c4205)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
```
In drivers/usb/core/sysfs.c (ffffffff818ca4a5)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/usb.c (ffffffff818c0665)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
```
```
In drivers/usb/core/hub.c (ffffffff818c2385)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818c8745)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff818cdda4)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff818d00f5)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
```
In drivers/usb/core/sysfs.c (ffffffff818d55f5)
Location: include/linux/usb.h:715
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/usb.c (ffffffff818a38e5)
Location: include/linux/usb.h:717
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
```
```
In drivers/usb/core/hub.c (ffffffff818a5d65)
Location: include/linux/usb.h:717
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818abd95)
Location: include/linux/usb.h:717
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff818b13e4)
Location: include/linux/usb.h:717
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff818b3725)
Location: include/linux/usb.h:717
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
```
In drivers/usb/core/sysfs.c (ffffffff818b8bb5)
Location: include/linux/usb.h:717
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/usb.c (ffffffff819384a5)
Location: include/linux/usb.h:710
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
```
```
In drivers/usb/core/hub.c (ffffffff8193abc5)
Location: include/linux/usb.h:710
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81940d85)
Location: include/linux/usb.h:710
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff81946634)
Location: include/linux/usb.h:710
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff81948bb5)
Location: include/linux/usb.h:710
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
```
In drivers/usb/core/sysfs.c (ffffffff8194e685)
Location: include/linux/usb.h:710
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/usb.c (ffffffff81a8fd65)
Location: include/linux/usb.h:710
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_intf_get_dma_device
```
```
In drivers/usb/core/hub.c (ffffffff81a90465)
Location: include/linux/usb.h:710
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81a99075)
Location: include/linux/usb.h:710
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff81a9ee34)
Location: include/linux/usb.h:710
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/driver.c (ffffffff81aa1705)
Location: include/linux/usb.h:710
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
In drivers/usb/core/sysfs.c (ffffffff81aa7635)
Location: include/linux/usb.h:710
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
```
</details>
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
In drivers/usb/core/hub.c (ffff800010a136ec)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffff800010a1b40c)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffff800010a227cc)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (ffff800010a259cc)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_match_one_id
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffff800010a2b7e0)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/hub.c (c0aea294)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (c0af3380)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (c0af9500)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (c0afb79c)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_match_one_id
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (c0b011fc)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/hub.c (c000000000acb8c0)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (c000000000ad4a00)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (c000000000add390)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (c000000000ae0284)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (c000000000ae8730)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/hub.c (ffffffe00063912a)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffe00063f9ac)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffe000645418)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (ffffffe0006474b2)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_match_one_id
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffe00064cc3a)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/hub.c (ffffffff8179d1a2)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817a4739)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff817aa6cc)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (ffffffff817aca1f)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817b2695)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/hub.c (ffffffff8178ee32)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817962a9)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff8179c0cc)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (ffffffff8179e41f)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817a40c5)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/hub.c (ffffffff817d9c42)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817e11d9)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff817e716c)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (ffffffff817e94bf)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff817ef135)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
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
In drivers/usb/core/hub.c (ffffffff817f28f2)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817fb519)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_free_streams
  - drivers/usb/core/hcd.c:usb_alloc_streams
```
```
In drivers/usb/core/message.c (ffffffff8180152c)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/message.c:__usb_queue_reset_device
  - drivers/usb/core/message.c:usb_if_uevent
  - drivers/usb/core/message.c:usb_release_interface
  - drivers/usb/core/message.c:create_intf_ep_devs
```
```
In drivers/usb/core/driver.c (ffffffff818039ef)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_uevent
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/sysfs.c (ffffffff81809375)
Location: include/linux/usb.h:714
Inline: True
Inline callers:
  - drivers/usb/core/sysfs.c:usb_create_sysfs_intf_files
  - drivers/usb/core/sysfs.c:modalias_show
```
</details>
</li>
</ul>

## Differences
