# Function: <code>usb_get_intfdata</code>

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
In drivers/usb/core/hub.c (0)
Location: include/linux/usb.h:194
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/usb.h:194
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
In drivers/usb/core/hub.c (0)
Location: include/linux/usb.h:194
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/usb.h:194
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
In drivers/usb/core/hub.c (0)
Location: include/linux/usb.h:194
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/usb.h:194
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
In drivers/usb/core/hub.c (0)
Location: include/linux/usb.h:264
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/usb.h:264
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
In drivers/usb/core/hub.c (ffffffff8171a190)
Location: include/linux/usb.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff817284fe)
Location: include/linux/usb.h:265
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff81758f30)
Location: include/linux/usb.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff81767345)
Location: include/linux/usb.h:265
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff8177d4a0)
Location: include/linux/usb.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff8178b8d5)
Location: include/linux/usb.h:265
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff817ba000)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff817c9ef5)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff817ea850)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff817faa15)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff818b9ca0)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
  - drivers/usb/core/hub.c:usb_set_lpm_parameters
```
```
In drivers/usb/core/devio.c (ffffffff818cacb5)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff818c8580)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
  - drivers/usb/core/hub.c:usb_set_lpm_parameters
```
```
In drivers/usb/core/devio.c (ffffffff818d5da5)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff818abbd0)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
  - drivers/usb/core/hub.c:usb_set_lpm_parameters
```
```
In drivers/usb/core/devio.c (ffffffff818b92e5)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff81940bf0)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
  - drivers/usb/core/hub.c:usb_set_lpm_parameters
```
```
In drivers/usb/core/devio.c (ffffffff8194edc5)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff81a98e00)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff81aa7e85)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff81c1cd30)
Location: include/linux/usb.h:264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff81c2ee75)
Location: include/linux/usb.h:264
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff81c83c40)
Location: include/linux/usb.h:276
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:update_port_device_state
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff81c960d5)
Location: include/linux/usb.h:276
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff81d38640)
Location: include/linux/usb.h:275
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:update_port_device_state
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:usb_hub_release_port
  - drivers/usb/core/hub.c:usb_hub_claim_port
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff81d4abb5)
Location: include/linux/usb.h:275
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffff800010a1a378)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffff800010a2ccfc)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (c0af216c)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (c0b01ad4)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (c000000000ad354c)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (c000000000ae93c8)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffe00063e9b4)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffe00064d478)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff817a2c30)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff817b2df5)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff81794a70)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff817a4825)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff817df6d0)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff817ef895)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
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
In drivers/usb/core/hub.c (ffffffff817f99c0)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:hub_reset_resume
  - drivers/usb/core/hub.c:hub_resume
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_post_reset
  - drivers/usb/core/hub.c:hub_pre_reset
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
```
```
In drivers/usb/core/devio.c (ffffffff81809ad5)
Location: include/linux/usb.h:263
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
</ul>

## Differences
