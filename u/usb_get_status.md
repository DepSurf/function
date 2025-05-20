# Function: <code>usb_get_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816111c0)
Location: drivers/usb/core/message.c:942
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff816111c0-ffffffff81611274: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81670dc0)
Location: drivers/usb/core/message.c:939
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81670dc0-ffffffff81670e74: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8169ea70)
Location: drivers/usb/core/message.c:942
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff8169ea70-ffffffff8169eb24: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816b3c80)
Location: drivers/usb/core/message.c:940
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff816b3c80-ffffffff816b3d28: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8171f450)
Location: drivers/usb/core/message.c:945
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff8171f450-ffffffff8171f55b: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8175e200)
Location: drivers/usb/core/message.c:970
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff8175e200-ffffffff8175e302: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817827d0)
Location: drivers/usb/core/message.c:971
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff817827d0-ffffffff817828d2: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817c0c70)
Location: drivers/usb/core/message.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff817c0c70-ffffffff817c0d79: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817f15f0)
Location: drivers/usb/core/message.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff817f15f0-ffffffff817f16f9: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818c0f30)
Location: drivers/usb/core/message.c:981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff818c0f30-ffffffff818c1038: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818cd020)
Location: drivers/usb/core/message.c:1121
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff818cd020-ffffffff818cd128: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818b0640)
Location: drivers/usb/core/message.c:1127
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff818b0640-ffffffff818b0749: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff819458a0)
Location: drivers/usb/core/message.c:1127
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff819458a0-ffffffff819459a9: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81a9dfc0)
Location: drivers/usb/core/message.c:1127
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff81a9dfc0-ffffffff81a9e0d0: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c230c0)
Location: drivers/usb/core/message.c:1128
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff81c230c0-ffffffff81c231d0: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c8a040)
Location: drivers/usb/core/message.c:1123
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff81c8a040-ffffffff81c8a150: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d3ea60)
Location: drivers/usb/core/message.c:1124
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:finish_port_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff81d3ea60-ffffffff81d3eb70: usb_get_status (STB_GLOBAL)
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
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffff800010a21ab0)
Location: drivers/usb/core/message.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffff800010a21ab0-ffff800010a21bd4: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c0af845c)
Location: drivers/usb/core/message.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
c0af845c-c0af8578: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c000000000adbd30)
Location: drivers/usb/core/message.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
c000000000adbd30-c000000000adbf14: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffe000644578)
Location: drivers/usb/core/message.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffe000644578-ffffffe00064466a: usb_get_status (STB_GLOBAL)
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
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817a99d0)
Location: drivers/usb/core/message.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff817a99d0-ffffffff817a9ad9: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8179b3d0)
Location: drivers/usb/core/message.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff8179b3d0-ffffffff8179b4d9: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817e6470)
Location: drivers/usb/core/message.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff817e6470-ffffffff817e6579: usb_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int usb_get_status(struct usb_device *dev, int recip, int type, int target, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff818006d0)
Location: drivers/usb/core/message.c:973
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_suspend_both
```
**Symbols:**

```
ffffffff818006d0-ffffffff818007d9: usb_get_status (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int recip</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, type, target, data</code> ➡️ <code>dev, recip, type, target, data</code>
</li>
</ul>
</details>
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
