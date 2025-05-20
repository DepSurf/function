# Function: <code>usb_hub_to_struct_hub</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81603976)
Location: drivers/usb/core/hub.c:118
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:find_port_owner
  - drivers/usb/core/hub.c:recursively_mark_NOTATTACHED
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:hub_ioctl
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_kick_hub_wq
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_hub_release_all_ports
  - drivers/usb/core/hub.c:usb_device_is_owned
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
Direct callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff816055f0-ffffffff81605628: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8166bb46)
Location: drivers/usb/core/hub.c:120
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_enable_lpm
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff81665390-ffffffff816653c8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81699846)
Location: drivers/usb/core/hub.c:123
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_enable_lpm
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff81692eb0-ffffffff81692ee8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816aeb86)
Location: drivers/usb/core/hub.c:123
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_get_hub_port_acpi_handle
  - drivers/usb/core/hub.c:usb_hub_adjust_deviceremovable
  - drivers/usb/core/hub.c:usb_hub_find_child
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_enable_lpm
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff816a8580-ffffffff816a85b8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8171a175)
Location: drivers/usb/core/hub.c:123
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff81713980-ffffffff817139b8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81758f15)
Location: drivers/usb/core/hub.c:126
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff817526f0-ffffffff81752728: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8177d485)
Location: drivers/usb/core/hub.c:127
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff81776b70-ffffffff81776ba8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b9fe5)
Location: drivers/usb/core/hub.c:129
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff817b4c60-ffffffff817b4c98: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817ea835)
Location: drivers/usb/core/hub.c:131
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff817e5390-ffffffff817e53c8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b9c85)
Location: drivers/usb/core/hub.c:133
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
  - drivers/usb/core/hub.c:usb_set_lpm_parameters
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff818b5af0-ffffffff818b5b28: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c8565)
Location: drivers/usb/core/hub.c:133
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
  - drivers/usb/core/hub.c:usb_set_lpm_parameters
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff818c4440-ffffffff818c4478: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818abbb5)
Location: drivers/usb/core/hub.c:137
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
  - drivers/usb/core/hub.c:usb_set_lpm_parameters
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:__each_hub
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff818a76c0-ffffffff818a76f8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81940bd5)
Location: drivers/usb/core/hub.c:137
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
  - drivers/usb/core/hub.c:usb_set_lpm_parameters
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/usb.c:__each_hub
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff8193c550-ffffffff8193c588: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a98de5)
Location: drivers/usb/core/hub.c:137
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff81a94290-ffffffff81a942d8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1cd15)
Location: drivers/usb/core/hub.c:141
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:disable_show
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff81c16580-ffffffff81c165c8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c83c25)
Location: drivers/usb/core/hub.c:141
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:disable_show
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff81c7d390-ffffffff81c7d3d8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d38625)
Location: drivers/usb/core/hub.c:153
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:disable_show
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff81d31f30-ffffffff81d31f78: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a1a364)
Location: drivers/usb/core/hub.c:131
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffff800010a140e8-ffff800010a14138: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0af2148)
Location: drivers/usb/core/hub.c:131
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
c0aec1d0-c0aec218: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ad3528)
Location: drivers/usb/core/hub.c:131
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
c000000000acbe10-c000000000acbe58: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063e9a4)
Location: drivers/usb/core/hub.c:131
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
**Symbols:**

```
ffffffe000639226-ffffffe000639264: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817a2c15)
Location: drivers/usb/core/hub.c:131
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff8179d770-ffffffff8179d7a8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81794a55)
Location: drivers/usb/core/hub.c:131
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff8178f3f0-ffffffff8178f428: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817df6b5)
Location: drivers/usb/core/hub.c:131
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff817da210-ffffffff817da248: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct usb_hub *usb_hub_to_struct_hub(struct usb_device *hdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f99a5)
Location: drivers/usb/core/hub.c:131
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
  - drivers/usb/core/hub.c:usb_remove_device
  - drivers/usb/core/hub.c:usb_wakeup_notification
  - drivers/usb/core/hub.c:usb_kick_hub_wq
Direct callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:match_location
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/usb-acpi.c:usb_acpi_set_power_state
```
**Symbols:**

```
ffffffff817f44a0-ffffffff817f44d8: usb_hub_to_struct_hub (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
