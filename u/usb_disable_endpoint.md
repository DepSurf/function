# Function: <code>usb_disable_endpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81612340)
Location: drivers/usb/core/message.c:1063
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_disable_interface
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
```
**Symbols:**

```
ffffffff81612340-ffffffff816123e2: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816722e0)
Location: drivers/usb/core/message.c:1060
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff816722e0-ffffffff81672382: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8169ff90)
Location: drivers/usb/core/message.c:1063
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff8169ff90-ffffffff816a0032: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816b5170)
Location: drivers/usb/core/message.c:1061
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff816b5170-ffffffff816b5210: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81720a00)
Location: drivers/usb/core/message.c:1100
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff81720a00-ffffffff81720aa0: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8175f810)
Location: drivers/usb/core/message.c:1125
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff8175f810-ffffffff8175f8af: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81783df0)
Location: drivers/usb/core/message.c:1126
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff81783df0-ffffffff81783e8f: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817c2120)
Location: drivers/usb/core/message.c:1128
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff817c2120-ffffffff817c21c4: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817f2aa0)
Location: drivers/usb/core/message.c:1128
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff817f2aa0-ffffffff817f2b44: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818c2440)
Location: drivers/usb/core/message.c:1136
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff818c2440-ffffffff818c24ec: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818ce760)
Location: drivers/usb/core/message.c:1277
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff818ce760-ffffffff818ce80c: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818b1d90)
Location: drivers/usb/core/message.c:1283
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff818b1d90-ffffffff818b1e3c: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81946fd0)
Location: drivers/usb/core/message.c:1283
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff81946fd0-ffffffff8194708a: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81a9f8c0)
Location: drivers/usb/core/message.c:1283
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff81a9f8c0-ffffffff81a9f99c: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c24cb0)
Location: drivers/usb/core/message.c:1284
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff81c24cb0-ffffffff81c24d8c: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c8bc30)
Location: drivers/usb/core/message.c:1279
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff81c8bc30-ffffffff81c8bd0c: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d40710)
Location: drivers/usb/core/message.c:1280
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
  - drivers/usb/core/message.c:usb_disable_device_endpoints
```
**Symbols:**

```
ffffffff81d40710-ffffffff81d407ec: usb_disable_endpoint (STB_GLOBAL)
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
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffff800010a23458)
Location: drivers/usb/core/message.c:1128
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffff800010a23458-ffff800010a23514: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c0af9a88)
Location: drivers/usb/core/message.c:1128
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
c0af9a88-c0af9b24: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c000000000adde10)
Location: drivers/usb/core/message.c:1128
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
c000000000adde10-c000000000addef0: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffe000645b80)
Location: drivers/usb/core/message.c:1128
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffe000645b80-ffffffe000645c28: usb_disable_endpoint (STB_GLOBAL)
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
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817aae80)
Location: drivers/usb/core/message.c:1128
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff817aae80-ffffffff817aaf24: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8179c880)
Location: drivers/usb/core/message.c:1128
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff8179c880-ffffffff8179c924: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817e7920)
Location: drivers/usb/core/message.c:1128
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff817e7920-ffffffff817e79c4: usb_disable_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void usb_disable_endpoint(struct usb_device *dev, unsigned int epaddr, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81801b70)
Location: drivers/usb/core/message.c:1128
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/hub.c:usb_ep0_reinit
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/message.c:usb_disable_interface
```
**Symbols:**

```
ffffffff81801b70-ffffffff81801c14: usb_disable_endpoint (STB_GLOBAL)
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
