# Function: <code>usb_device_supports_lpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81605630)
Location: drivers/usb/core/hub.c:125
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81605630-ffffffff816056f7: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816653d0)
Location: drivers/usb/core/hub.c:127
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff816653d0-ffffffff816654a2: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81692ef0)
Location: drivers/usb/core/hub.c:130
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81692ef0-ffffffff81692fc2: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a85c0)
Location: drivers/usb/core/hub.c:130
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff816a85c0-ffffffff816a867d: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817139c0)
Location: drivers/usb/core/hub.c:130
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817139c0-ffffffff81713a7d: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81752730)
Location: drivers/usb/core/hub.c:133
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81752730-ffffffff817527ee: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81776bb0)
Location: drivers/usb/core/hub.c:134
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81776bb0-ffffffff81776c6e: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b4cc2)
Location: drivers/usb/core/hub.c:136
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817ba2af-ffffffff817ba304: usb_device_supports_lpm.cold (STB_LOCAL)
ffffffff817b4ca0-ffffffff817b4d1b: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e53f2)
Location: drivers/usb/core/hub.c:138
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817eaaff-ffffffff817eab54: usb_device_supports_lpm.cold (STB_LOCAL)
ffffffff817e53d0-ffffffff817e544b: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b5b52)
Location: drivers/usb/core/hub.c:140
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff818ba0ad-ffffffff818ba102: usb_device_supports_lpm.cold (STB_LOCAL)
ffffffff818b5b30-ffffffff818b5bab: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c44a2)
Location: drivers/usb/core/hub.c:140
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81c1abd3-ffffffff81c1ac28: usb_device_supports_lpm.cold (STB_LOCAL)
ffffffff818c4480-ffffffff818c44fb: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a7722)
Location: drivers/usb/core/hub.c:144
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81c0ca19-ffffffff81c0ca6e: usb_device_supports_lpm.cold (STB_LOCAL)
ffffffff818a7700-ffffffff818a777b: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193c5b2)
Location: drivers/usb/core/hub.c:144
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81d1399c-ffffffff81d139f1: usb_device_supports_lpm.cold (STB_LOCAL)
ffffffff8193c590-ffffffff8193c60b: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:144
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81ede747-ffffffff81ede789: usb_device_supports_lpm.cold (STB_LOCAL)
ffffffff81a942e0-ffffffff81a9437b: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c165e0)
Location: drivers/usb/core/hub.c:148
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81c165e0-ffffffff81c166c8: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7d3f0)
Location: drivers/usb/core/hub.c:148
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81c7d3f0-ffffffff81c7d4d8: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d31f90)
Location: drivers/usb/core/hub.c:160
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81d31f90-ffffffff81d32084: usb_device_supports_lpm (STB_GLOBAL)
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
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a14138)
Location: drivers/usb/core/hub.c:138
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffff800010a14138-ffff800010a1421c: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aec218)
Location: drivers/usb/core/hub.c:138
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
c0aec218-c0aec2f8: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acbe60)
Location: drivers/usb/core/hub.c:138
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
c000000000acbe60-c000000000acbf94: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000639264)
Location: drivers/usb/core/hub.c:138
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffe000639264-ffffffe000639330: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179d7d2)
Location: drivers/usb/core/hub.c:138
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817a2edf-ffffffff817a2f34: usb_device_supports_lpm.cold (STB_LOCAL)
ffffffff8179d7b0-ffffffff8179d82b: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178f452)
Location: drivers/usb/core/hub.c:138
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81794d1f-ffffffff81794d74: usb_device_supports_lpm.cold (STB_LOCAL)
ffffffff8178f430-ffffffff8178f4ab: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817da272)
Location: drivers/usb/core/hub.c:138
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817df97f-ffffffff817df9d4: usb_device_supports_lpm.cold (STB_LOCAL)
ffffffff817da250-ffffffff817da2cb: usb_device_supports_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_device_supports_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f4502)
Location: drivers/usb/core/hub.c:138
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817f9c6f-ffffffff817f9cc4: usb_device_supports_lpm.cold (STB_LOCAL)
ffffffff817f44e0-ffffffff817f455b: usb_device_supports_lpm (STB_GLOBAL)
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
