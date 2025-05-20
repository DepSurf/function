# Function: <code>usb_control_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81610ee0)
Location: drivers/usb/core/message.c:131
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff81610ee0-ffffffff81611002: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81670af0)
Location: drivers/usb/core/message.c:132
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff81670af0-ffffffff81670c0f: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8169e7a0)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff8169e7a0-ffffffff8169e8bf: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816b39b0)
Location: drivers/usb/core/message.c:134
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff816b39b0-ffffffff816b3ad0: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8171f160)
Location: drivers/usb/core/message.c:134
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff8171f160-ffffffff8171f297: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8175def0)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff8175def0-ffffffff8175e027: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817824c0)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff817824c0-ffffffff817825f7: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817c0980)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff817c0980-ffffffff817c0ac0: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817f1300)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff817f1300-ffffffff817f1440: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818c0c40)
Location: drivers/usb/core/message.c:136
Inline: False
Direct callers:
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
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
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
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
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
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff818c0c40-ffffffff818c0d7e: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818ccd30)
Location: drivers/usb/core/message.c:136
Inline: False
Direct callers:
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
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
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
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
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
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff818ccd30-ffffffff818cce6e: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818b0340)
Location: drivers/usb/core/message.c:136
Inline: False
Direct callers:
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
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_req_set_sel
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
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
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:do_proc_control
```
**Symbols:**

```
ffffffff818b0340-ffffffff818b0480: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff819455a0)
Location: drivers/usb/core/message.c:136
Inline: False
Direct callers:
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
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_req_set_sel
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
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
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
```
**Symbols:**

```
ffffffff819455a0-ffffffff819456e0: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81a9dc40)
Location: drivers/usb/core/message.c:136
Inline: False
Direct callers:
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
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_req_set_sel
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
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
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
```
**Symbols:**

```
ffffffff81a9dc40-ffffffff81a9dd9a: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c22d10)
Location: drivers/usb/core/message.c:136
Inline: False
Direct callers:
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
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
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
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
```
**Symbols:**

```
ffffffff81c22d10-ffffffff81c22e6a: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c89c90)
Location: drivers/usb/core/message.c:136
Inline: False
Direct callers:
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
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:get_bMaxPacketSize0
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
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
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
  - drivers/usb/core/message.c:usb_control_msg_send
```
**Symbols:**

```
ffffffff81c89c90-ffffffff81c89dea: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d3e680)
Location: drivers/usb/core/message.c:137
Inline: False
Direct callers:
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
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:get_bMaxPacketSize0
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
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
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/message.c:usb_control_msg_recv
  - drivers/usb/core/message.c:usb_control_msg_send
```
**Symbols:**

```
ffffffff81d3e680-ffffffff81d3e807: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffff800010a21740)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffff800010a21740-ffff800010a21874: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c0af813c)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
c0af813c-c0af8270: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c000000000adb8a0)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_enable_link_state
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
c000000000adb8a0-c000000000adba38: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffe0006442b6)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_enable_link_state
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffe0006442b6-ffffffe0006443ae: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817a96e0)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff817a96e0-ffffffff817a9820: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8179b0e0)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff8179b0e0-ffffffff8179b220: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817e6180)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff817e6180-ffffffff817e62c0: usb_control_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int usb_control_msg(struct usb_device *dev, unsigned int pipe, __u8 request, __u8 requesttype, __u16 value, __u16 index, void *data, __u16 size, int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818003e0)
Location: drivers/usb/core/message.c:135
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_set_device_initiated_lpm
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_hub_status
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_tt_work
  - drivers/usb/core/hub.c:hub_ext_port_status
  - drivers/usb/core/hub.c:set_port_feature
  - drivers/usb/core/hub.c:usb_clear_port_feature
  - drivers/usb/core/hub.c:clear_hub_feature
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_clear_halt
  - drivers/usb/core/message.c:usb_get_status
  - drivers/usb/core/message.c:usb_set_isoch_delay
  - drivers/usb/core/message.c:usb_get_string
  - drivers/usb/core/message.c:usb_get_descriptor
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
```
**Symbols:**

```
ffffffff818003e0-ffffffff81800520: usb_control_msg (STB_GLOBAL)
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
