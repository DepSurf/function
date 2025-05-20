# Function: <code>usb_wakeup_enabled_descendants</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b769f)
Location: drivers/usb/core/hub.c:3179
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff817b3270-ffffffff817b32c6: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e7e5f)
Location: drivers/usb/core/hub.c:3223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff817e39a0-ffffffff817e39f6: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b733f)
Location: drivers/usb/core/hub.c:3237
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff818b2440-ffffffff818b2496: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c5c4f)
Location: drivers/usb/core/hub.c:3255
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff818c0dd0-ffffffff818c0e26: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a8f2f)
Location: drivers/usb/core/hub.c:3310
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff818a40c0-ffffffff818a4116: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193de3f)
Location: drivers/usb/core/hub.c:3314
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff81938d30-ffffffff81938d86: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a95e47)
Location: drivers/usb/core/hub.c:3320
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff81a906b0-ffffffff81a9071a: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1856d)
Location: drivers/usb/core/hub.c:3339
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff81c125f0-ffffffff81c1265a: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7f54d)
Location: drivers/usb/core/hub.c:3359
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff81c79370-ffffffff81c793da: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d33f3d)
Location: drivers/usb/core/hub.c:3361
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff81d2dd70-ffffffff81d2ddda: usb_wakeup_enabled_descendants (STB_GLOBAL)
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
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a170ac)
Location: drivers/usb/core/hub.c:3223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffff800010a12070-ffff800010a120d0: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aef184)
Location: drivers/usb/core/hub.c:3223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
c0aea598-c0aea5f8: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acfc18)
Location: drivers/usb/core/hub.c:3223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
c000000000ac9430-c000000000ac949c: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063bf8e)
Location: drivers/usb/core/hub.c:3223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffe000637ab8-ffffffe000637b04: usb_wakeup_enabled_descendants (STB_GLOBAL)
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
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817a023f)
Location: drivers/usb/core/hub.c:3223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff8179bd80-ffffffff8179bdd6: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81791eaf)
Location: drivers/usb/core/hub.c:3223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
```
**Symbols:**

```
ffffffff8178da10-ffffffff8178da66: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817dccdf)
Location: drivers/usb/core/hub.c:3223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff817d8820-ffffffff817d8876: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int usb_wakeup_enabled_descendants(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f6faf)
Location: drivers/usb/core/hub.c:3223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
```
**Symbols:**

```
ffffffff817f2b90-ffffffff817f2be6: usb_wakeup_enabled_descendants (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
