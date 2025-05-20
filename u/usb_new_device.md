# Function: <code>usb_new_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81608540)
Location: drivers/usb/core/hub.c:2459
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81608540-ffffffff816089ea: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81668210)
Location: drivers/usb/core/hub.c:2456
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81668210-ffffffff8166869f: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81695f30)
Location: drivers/usb/core/hub.c:2375
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81695f30-ffffffff816963bf: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816ab340)
Location: drivers/usb/core/hub.c:2403
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff816ab340-ffffffff816ab7ca: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817167a0)
Location: drivers/usb/core/hub.c:2403
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817167a0-ffffffff81716c2a: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817555c0)
Location: drivers/usb/core/hub.c:2431
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817555c0-ffffffff81755a56: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81779af0)
Location: drivers/usb/core/hub.c:2442
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81779af0-ffffffff81779f7c: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2482
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817ba6f1-ffffffff817ba9f5: usb_new_device.cold (STB_LOCAL)
ffffffff817b7950-ffffffff817b7b32: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2493
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817eaf6b-ffffffff817eb26f: usb_new_device.cold (STB_LOCAL)
ffffffff817e8120-ffffffff817e8302: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2500
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff818ba60b-ffffffff818ba889: usb_new_device.cold (STB_LOCAL)
ffffffff818b7670-ffffffff818b7821: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2501
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81c1b131-ffffffff81c1b3af: usb_new_device.cold (STB_LOCAL)
ffffffff818c5f80-ffffffff818c6131: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2508
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81c0cf9f-ffffffff81c0d290: usb_new_device.cold (STB_LOCAL)
ffffffff818a9260-ffffffff818a946d: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2513
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81d13f4c-ffffffff81d1428a: usb_new_device.cold (STB_LOCAL)
ffffffff8193e170-ffffffff8193e37a: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2513
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81edeac9-ffffffff81ededdc: usb_new_device.cold (STB_LOCAL)
ffffffff81a961a0-ffffffff81a9639b: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2522
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:register_root_hub
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff8209e7a0-ffffffff8209e7c1: usb_new_device.cold (STB_LOCAL)
ffffffff81c188f0-ffffffff81c18e07: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2537
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff8211fd33-ffffffff8211fd4d: usb_new_device.cold (STB_LOCAL)
ffffffff81c7f8d0-ffffffff81c7fde1: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2561
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff82201509-ffffffff82201523: usb_new_device.cold (STB_LOCAL)
ffffffff81d342c0-ffffffff81d34816: usb_new_device (STB_GLOBAL)
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
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a173f8)
Location: drivers/usb/core/hub.c:2493
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffff800010a173f8-ffff800010a178cc: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aef480)
Location: drivers/usb/core/hub.c:2493
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
c0aef480-c0aef918: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ad0070)
Location: drivers/usb/core/hub.c:2493
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
c000000000ad0070-c000000000ad0630: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063c278)
Location: drivers/usb/core/hub.c:2493
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffe00063c278-ffffffe00063c6a4: usb_new_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2493
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817a334b-ffffffff817a364f: usb_new_device.cold (STB_LOCAL)
ffffffff817a0500-ffffffff817a06e2: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2493
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff8179518b-ffffffff817951c0: usb_new_device.cold (STB_LOCAL)
ffffffff81792170-ffffffff81792530: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2493
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817dfdeb-ffffffff817e00ef: usb_new_device.cold (STB_LOCAL)
ffffffff817dcfa0-ffffffff817dd182: usb_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_new_device(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2493
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817fa0db-ffffffff817fa3df: usb_new_device.cold (STB_LOCAL)
ffffffff817f7270-ffffffff817f7452: usb_new_device (STB_GLOBAL)
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
