# Function: <code>__create_pipe</code>

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
Location: include/linux/usb.h:1816
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81612a6d)
Location: include/linux/usb.h:1816
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/usb.h:1816
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
In drivers/usb/core/hub.c (ffffffff81666b3a)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff81672f3a)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff8167e0f1)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff8169482d)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff816a0bea)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff816abe75)
Location: include/linux/usb.h:1813
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff816a9cf2)
Location: include/linux/usb.h:1884
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff816b6020)
Location: include/linux/usb.h:1884
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff816c0ed0)
Location: include/linux/usb.h:1884
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff81715142)
Location: include/linux/usb.h:1901
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff817218b6)
Location: include/linux/usb.h:1901
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff8172c90e)
Location: include/linux/usb.h:1901
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff81753f04)
Location: include/linux/usb.h:1920
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff81760639)
Location: include/linux/usb.h:1920
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff8176ac0e)
Location: include/linux/usb.h:1920
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff81778377)
Location: include/linux/usb.h:1920
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff81784c64)
Location: include/linux/usb.h:1920
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff8178f19e)
Location: include/linux/usb.h:1920
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff817b629d)
Location: include/linux/usb.h:1920
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff817c2e24)
Location: include/linux/usb.h:1920
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff817cd5f9)
Location: include/linux/usb.h:1920
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff817e69cd)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff817f37a4)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff817fe4f5)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff818b6773)
Location: include/linux/usb.h:1932
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_req_set_sel
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_handle_remote_wakeup
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
```
```
In drivers/usb/core/message.c (ffffffff818c32f1)
Location: include/linux/usb.h:1932
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff818ccb94)
Location: include/linux/usb.h:1932
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff818c509c)
Location: include/linux/usb.h:1947
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_req_set_sel
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:hub_handle_remote_wakeup
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
```
```
In drivers/usb/core/message.c (ffffffff818cef7c)
Location: include/linux/usb.h:1947
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
```
```
In drivers/usb/core/devio.c (ffffffff818d7d8c)
Location: include/linux/usb.h:1947
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:proc_clearhalt
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
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
In drivers/usb/core/hub.c (ffffffff818a837c)
Location: include/linux/usb.h:1956
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_req_set_sel
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
```
```
In drivers/usb/core/message.c (ffffffff818b256b)
Location: include/linux/usb.h:1956
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
```
```
In drivers/usb/core/devio.c (ffffffff818bcfd3)
Location: include/linux/usb.h:1956
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
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
In drivers/usb/core/hub.c (ffffffff8193d21a)
Location: include/linux/usb.h:1949
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_req_set_sel
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
```
```
In drivers/usb/core/message.c (ffffffff8194785b)
Location: include/linux/usb.h:1949
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
```
```
In drivers/usb/core/devio.c (ffffffff81952fee)
Location: include/linux/usb.h:1949
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
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
In drivers/usb/core/hub.c (ffffffff81a94f16)
Location: include/linux/usb.h:1940
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_req_set_sel
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
```
```
In drivers/usb/core/message.c (ffffffff81aa01d8)
Location: include/linux/usb.h:1940
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
```
```
In drivers/usb/core/devio.c (ffffffff81aac60b)
Location: include/linux/usb.h:1940
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
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
In drivers/usb/core/hub.c (ffffffff81c1750a)
Location: include/linux/usb.h:1970
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
```
```
In drivers/usb/core/message.c (ffffffff81c2566d)
Location: include/linux/usb.h:1970
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
```
```
In drivers/usb/core/devio.c (ffffffff81c33be1)
Location: include/linux/usb.h:1970
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
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
In drivers/usb/core/hub.c (ffffffff81c7e533)
Location: include/linux/usb.h:2009
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
```
```
In drivers/usb/core/message.c (ffffffff81c8c5fd)
Location: include/linux/usb.h:2009
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
  - drivers/usb/core/message.c:usb_control_msg_send
```
```
In drivers/usb/core/devio.c (ffffffff81c9b19b)
Location: include/linux/usb.h:2009
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
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
In drivers/usb/core/hub.c (ffffffff81d32f03)
Location: include/linux/usb.h:1976
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
```
```
In drivers/usb/core/message.c (ffffffff81d410dd)
Location: include/linux/usb.h:1976
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
  - drivers/usb/core/message.c:usb_control_msg_send
```
```
In drivers/usb/core/devio.c (ffffffff81d4fd5c)
Location: include/linux/usb.h:1976
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
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
In drivers/usb/core/hub.c (ffff800010a157f8)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffff800010a2436c)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffff800010a31e80)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (c0aedb30)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (c0afa898)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (c0b05f6c)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (c000000000acdc8c)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_enable_link_state
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (c000000000adf234)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (c000000000aef4dc)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffe00063a9b0)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_enable_link_state
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffe00064695a)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffe00065042c)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff8179edad)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff817abb84)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff817b68d5)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff81790a2d)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff8179d584)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff817a82f5)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff817db84d)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff817e8624)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff817f3375)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
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
In drivers/usb/core/hub.c (ffffffff817f5add)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
```
```
In drivers/usb/core/message.c (ffffffff81802872)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
```
```
In drivers/usb/core/devio.c (ffffffff8180d5f0)
Location: include/linux/usb.h:1925
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
</details>
</li>
</ul>

## Differences
