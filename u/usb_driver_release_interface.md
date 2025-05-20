# Function: <code>usb_driver_release_interface</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81614ee0)
Location: drivers/usb/core/driver.c:573
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:releaseintf
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_disconnect_claim
```
**Symbols:**

```
ffffffff81614ee0-ffffffff81614f59: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81674e90)
Location: drivers/usb/core/driver.c:583
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff81674e90-ffffffff81674f09: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816a2b20)
Location: drivers/usb/core/driver.c:586
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff816a2b20-ffffffff816a2b99: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816b7cd0)
Location: drivers/usb/core/driver.c:586
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff816b7cd0-ffffffff816b7d4a: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817235a0)
Location: drivers/usb/core/driver.c:586
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff817235a0-ffffffff8172361a: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81762240)
Location: drivers/usb/core/driver.c:586
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff81762240-ffffffff817622b9: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81786850)
Location: drivers/usb/core/driver.c:583
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff81786850-ffffffff817868c9: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817c4d30)
Location: drivers/usb/core/driver.c:578
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff817c4d30-ffffffff817c4db4: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817f56d0)
Location: drivers/usb/core/driver.c:578
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff817f56d0-ffffffff817f5754: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818c5884)
Location: drivers/usb/core/driver.c:613
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
Direct callers:
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff818c4d30-ffffffff818c4db4: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818d1754)
Location: drivers/usb/core/driver.c:613
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
Direct callers:
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff818d0c10-ffffffff818d0c94: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818b4d74)
Location: drivers/usb/core/driver.c:609
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
Direct callers:
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff818b4140-ffffffff818b41c4: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8194a2a1)
Location: drivers/usb/core/driver.c:609
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
Direct callers:
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff81949670-ffffffff819496f4: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81aa2f01)
Location: drivers/usb/core/driver.c:609
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
Direct callers:
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff81aa24d0-ffffffff81aa2568: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c289e1)
Location: drivers/usb/core/driver.c:609
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
Direct callers:
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff81c27eb0-ffffffff81c27f48: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c8f9ad)
Location: drivers/usb/core/driver.c:609
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
Direct callers:
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff81c8ee60-ffffffff81c8eefb: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81d4455d)
Location: drivers/usb/core/driver.c:612
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
Direct callers:
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff81d439e0-ffffffff81d43a7b: usb_driver_release_interface (STB_GLOBAL)
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
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffff800010a265b8)
Location: drivers/usb/core/driver.c:578
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffff800010a265b8-ffff800010a2664c: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c0afc6e0)
Location: drivers/usb/core/driver.c:578
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
c0afc6e0-c0afc778: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c000000000ae1c60)
Location: drivers/usb/core/driver.c:578
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
c000000000ae1c60-c000000000ae1d20: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffe00064849a)
Location: drivers/usb/core/driver.c:578
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffe00064849a-ffffffe000648526: usb_driver_release_interface (STB_GLOBAL)
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
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817adab0)
Location: drivers/usb/core/driver.c:578
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff817adab0-ffffffff817adb34: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8179f4b0)
Location: drivers/usb/core/driver.c:578
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff8179f4b0-ffffffff8179f534: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817ea550)
Location: drivers/usb/core/driver.c:578
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff817ea550-ffffffff817ea5d4: usb_driver_release_interface (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void usb_driver_release_interface(struct usb_driver *driver, struct usb_interface *iface);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81804790)
Location: drivers/usb/core/driver.c:578
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_forced_unbind_intf
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:releaseintf
```
**Symbols:**

```
ffffffff81804790-ffffffff81804814: usb_driver_release_interface (STB_GLOBAL)
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
