# Function: <code>usb_set_device_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81604510)
Location: drivers/usb/core/hub.c:2007
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
```
**Symbols:**

```
ffffffff81604510-ffffffff8160463d: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81664200)
Location: drivers/usb/core/hub.c:2004
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81664200-ffffffff81664332: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81691dd0)
Location: drivers/usb/core/hub.c:1923
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81691dd0-ffffffff81691f02: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a7260)
Location: drivers/usb/core/hub.c:1945
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff816a7260-ffffffff816a73ba: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81712640)
Location: drivers/usb/core/hub.c:1945
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81712640-ffffffff8171279a: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817512d0)
Location: drivers/usb/core/hub.c:1969
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff817512d0-ffffffff8175144e: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81775730)
Location: drivers/usb/core/hub.c:1980
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81775730-ffffffff817758ae: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b3830)
Location: drivers/usb/core/hub.c:2018
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff817b3830-ffffffff817b399b: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e3f60)
Location: drivers/usb/core/hub.c:2029
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff817e3f60-ffffffff817e40cb: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b4626)
Location: drivers/usb/core/hub.c:2036
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:register_root_hub
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff818b2940-ffffffff818b2aa8: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c2f8d)
Location: drivers/usb/core/hub.c:2036
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:register_root_hub
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff818c12b0-ffffffff818c1418: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a605d)
Location: drivers/usb/core/hub.c:2043
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:register_root_hub
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff818a4590-ffffffff818a46f9: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193aebd)
Location: drivers/usb/core/hub.c:2046
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:register_root_hub
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81939240-ffffffff819393a9: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a92abd)
Location: drivers/usb/core/hub.c:2046
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:register_root_hub
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81a90cd0-ffffffff81a90e6a: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c14c76)
Location: drivers/usb/core/hub.c:2056
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:register_root_hub
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81c12cc0-ffffffff81c12e5a: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7ba76)
Location: drivers/usb/core/hub.c:2070
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:register_root_hub
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81c79c90-ffffffff81c79e00: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d306c6)
Location: drivers/usb/core/hub.c:2108
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/hcd.c:register_root_hub
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81d2e690-ffffffff81d2e800: usb_set_device_state (STB_GLOBAL)
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
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a13b90)
Location: drivers/usb/core/hub.c:2029
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffff800010a13b90-ffff800010a13d24: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aeaca8)
Location: drivers/usb/core/hub.c:2029
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
c0aeaca8-c0aeae34: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000aca420)
Location: drivers/usb/core/hub.c:2029
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
c000000000aca420-c000000000aca658: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000637964)
Location: drivers/usb/core/hub.c:2029
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffe000637964-ffffffe000637ab8: usb_set_device_state (STB_GLOBAL)
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
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179c340)
Location: drivers/usb/core/hub.c:2029
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff8179c340-ffffffff8179c4ab: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178dfd0)
Location: drivers/usb/core/hub.c:2029
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff8178dfd0-ffffffff8178e13b: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817d8de0)
Location: drivers/usb/core/hub.c:2029
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff817d8de0-ffffffff817d8f4b: usb_set_device_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void usb_set_device_state(struct usb_device *udev, enum usb_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f3150)
Location: drivers/usb/core/hub.c:2029
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:hcd_bus_resume
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff817f3150-ffffffff817f32bb: usb_set_device_state (STB_GLOBAL)
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
