# Function: <code>usb_disable_device_endpoints</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void usb_disable_device_endpoints(struct usb_device *dev, int skip_ep0);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818c24f0)
Location: drivers/usb/core/message.c:1213
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff818c24f0-ffffffff818c25a8: usb_disable_device_endpoints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void usb_disable_device_endpoints(struct usb_device *dev, int skip_ep0);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818ce810)
Location: drivers/usb/core/message.c:1354
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff818ce810-ffffffff818ce8c8: usb_disable_device_endpoints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usb_disable_device_endpoints(struct usb_device *dev, int skip_ep0);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818b1e40)
Location: drivers/usb/core/message.c:1360
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff818b1e40-ffffffff818b1ef8: usb_disable_device_endpoints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void usb_disable_device_endpoints(struct usb_device *dev, int skip_ep0);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81947090)
Location: drivers/usb/core/message.c:1360
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81947090-ffffffff81947148: usb_disable_device_endpoints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void usb_disable_device_endpoints(struct usb_device *dev, int skip_ep0);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81a9f9a0)
Location: drivers/usb/core/message.c:1360
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81a9f9a0-ffffffff81a9fa66: usb_disable_device_endpoints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void usb_disable_device_endpoints(struct usb_device *dev, int skip_ep0);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c24da0)
Location: drivers/usb/core/message.c:1361
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81c24da0-ffffffff81c24e66: usb_disable_device_endpoints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void usb_disable_device_endpoints(struct usb_device *dev, int skip_ep0);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c8bd20)
Location: drivers/usb/core/message.c:1356
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81c8bd20-ffffffff81c8bde6: usb_disable_device_endpoints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void usb_disable_device_endpoints(struct usb_device *dev, int skip_ep0);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d40800)
Location: drivers/usb/core/message.c:1357
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_disable_device
```
**Symbols:**

```
ffffffff81d40800-ffffffff81d408c6: usb_disable_device_endpoints (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
