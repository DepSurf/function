# Function: <code>usb_disable_interface</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816123f0)
Location: drivers/usb/core/message.c:1122
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff816123f0-ffffffff81612448: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81672390)
Location: drivers/usb/core/message.c:1119
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff81672390-ffffffff816723e8: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816a0040)
Location: drivers/usb/core/message.c:1122
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff816a0040-ffffffff816a0098: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816b5210)
Location: drivers/usb/core/message.c:1120
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff816b5210-ffffffff816b5269: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81720aa0)
Location: drivers/usb/core/message.c:1159
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff81720aa0-ffffffff81720af9: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8175f8b0)
Location: drivers/usb/core/message.c:1184
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff8175f8b0-ffffffff8175f906: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81783e90)
Location: drivers/usb/core/message.c:1185
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff81783e90-ffffffff81783ee6: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817c21d0)
Location: drivers/usb/core/message.c:1187
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff817c21d0-ffffffff817c2226: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817f2b50)
Location: drivers/usb/core/message.c:1187
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff817f2b50-ffffffff817f2ba6: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818c2a53)
Location: drivers/usb/core/message.c:1195
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff818c25b0-ffffffff818c2690: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818ced73)
Location: drivers/usb/core/message.c:1336
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff818ce8d0-ffffffff818ce9b0: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818b23a3)
Location: drivers/usb/core/message.c:1342
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff818b1f00-ffffffff818b1fe0: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81947693)
Location: drivers/usb/core/message.c:1342
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff81947150-ffffffff81947249: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81aa0b85)
Location: drivers/usb/core/message.c:1342
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff81a9fa70-ffffffff81a9fb76: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c2615b)
Location: drivers/usb/core/message.c:1343
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff81c24e80-ffffffff81c24f86: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c8d110)
Location: drivers/usb/core/message.c:1338
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff81c8be00-ffffffff81c8bf06: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d41c31)
Location: drivers/usb/core/message.c:1339
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff81d408e0-ffffffff81d409e6: usb_disable_interface (STB_GLOBAL)
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
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffff800010a23518)
Location: drivers/usb/core/message.c:1187
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffff800010a23518-ffff800010a23598: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c0af9b24)
Location: drivers/usb/core/message.c:1187
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
c0af9b24-c0af9b84: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c000000000addef0)
Location: drivers/usb/core/message.c:1187
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
c000000000addef0-c000000000addf94: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffe000645c28)
Location: drivers/usb/core/message.c:1187
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffe000645c28-ffffffe000645c8e: usb_disable_interface (STB_GLOBAL)
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
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817aaf30)
Location: drivers/usb/core/message.c:1187
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff817aaf30-ffffffff817aaf86: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8179c930)
Location: drivers/usb/core/message.c:1187
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff8179c930-ffffffff8179c986: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817e79d0)
Location: drivers/usb/core/message.c:1187
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff817e79d0-ffffffff817e7a26: usb_disable_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void usb_disable_interface(struct usb_device *dev, struct usb_interface *intf, bool reset_hardware);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81801c20)
Location: drivers/usb/core/message.c:1187
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
```
**Symbols:**

```
ffffffff81801c20-ffffffff81801c76: usb_disable_interface (STB_GLOBAL)
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
