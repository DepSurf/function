# Function: <code>usb_hub_create_port_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff8161f330)
Location: drivers/usb/core/port.c:401
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff8161f330-ffffffff8161f664: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff8167fcc0)
Location: drivers/usb/core/port.c:482
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff8167fcc0-ffffffff81680014: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff816ada00)
Location: drivers/usb/core/port.c:482
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff816ada00-ffffffff816add51: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff816c2ba0)
Location: drivers/usb/core/port.c:482
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff816c2ba0-ffffffff816c2ee0: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff8172e970)
Location: drivers/usb/core/port.c:473
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff8172e970-ffffffff8172ecb0: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff8176da90)
Location: drivers/usb/core/port.c:506
Inline: False
```
**Symbols:**

```
ffffffff8176da90-ffffffff8176ddc7: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81792110)
Location: drivers/usb/core/port.c:516
Inline: False
```
**Symbols:**

```
ffffffff81792110-ffffffff81792443: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/port.c (0)
Location: drivers/usb/core/port.c:525
Inline: False
```
**Symbols:**

```
ffffffff817d0ef4-ffffffff817d0f08: usb_hub_create_port_device.cold (STB_LOCAL)
ffffffff817d0a50-ffffffff817d0d8b: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/port.c (0)
Location: drivers/usb/core/port.c:531
Inline: False
```
**Symbols:**

```
ffffffff81801dc5-ffffffff81801dd9: usb_hub_create_port_device.cold (STB_LOCAL)
ffffffff81801950-ffffffff81801c8b: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/port.c (0)
Location: drivers/usb/core/port.c:531
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff818d2536-ffffffff818d254a: usb_hub_create_port_device.cold (STB_LOCAL)
ffffffff818d2280-ffffffff818d24d2: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/port.c (0)
Location: drivers/usb/core/port.c:531
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81c1ea73-ffffffff81c1ea87: usb_hub_create_port_device.cold (STB_LOCAL)
ffffffff818dc660-ffffffff818dc8b2: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/port.c (0)
Location: drivers/usb/core/port.c:531
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81c10904-ffffffff81c10918: usb_hub_create_port_device.cold (STB_LOCAL)
ffffffff818bf840-ffffffff818bfb5e: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/port.c (0)
Location: drivers/usb/core/port.c:531
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81d17c35-ffffffff81d17c49: usb_hub_create_port_device.cold (STB_LOCAL)
ffffffff81955eb0-ffffffff819561ce: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/port.c (0)
Location: drivers/usb/core/port.c:558
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81ee2acf-ffffffff81ee2aff: usb_hub_create_port_device.cold (STB_LOCAL)
ffffffff81aafa20-ffffffff81aafd5d: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81c37a40)
Location: drivers/usb/core/port.c:669
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81c37a40-ffffffff81c37d9b: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81c9ed90)
Location: drivers/usb/core/port.c:680
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81c9ed90-ffffffff81c9f148: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff81d53990)
Location: drivers/usb/core/port.c:696
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81d53990-ffffffff81d53d96: usb_hub_create_port_device (STB_GLOBAL)
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
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffff800010a35db8)
Location: drivers/usb/core/port.c:531
Inline: False
```
**Symbols:**

```
ffff800010a35db8-ffff800010a36100: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (c0b092f0)
Location: drivers/usb/core/port.c:531
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
c0b092f0-c0b09600: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (c000000000af3df0)
Location: drivers/usb/core/port.c:531
Inline: False
```
**Symbols:**

```
c000000000af3df0-c000000000af4258: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffe00065333a)
Location: drivers/usb/core/port.c:531
Inline: False
```
**Symbols:**

```
ffffffe00065333a-ffffffe00065360e: usb_hub_create_port_device (STB_GLOBAL)
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
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/port.c (0)
Location: drivers/usb/core/port.c:531
Inline: False
```
**Symbols:**

```
ffffffff817ba1a5-ffffffff817ba1b9: usb_hub_create_port_device.cold (STB_LOCAL)
ffffffff817b9d30-ffffffff817ba06b: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/port.c (0)
Location: drivers/usb/core/port.c:531
Inline: False
```
**Symbols:**

```
ffffffff817abbd5-ffffffff817abbe9: usb_hub_create_port_device.cold (STB_LOCAL)
ffffffff817ab760-ffffffff817aba9b: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/port.c (0)
Location: drivers/usb/core/port.c:531
Inline: False
```
**Symbols:**

```
ffffffff817f6c45-ffffffff817f6c59: usb_hub_create_port_device.cold (STB_LOCAL)
ffffffff817f67d0-ffffffff817f6b0b: usb_hub_create_port_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_hub_create_port_device(struct usb_hub *hub, int port1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/port.c (0)
Location: drivers/usb/core/port.c:531
Inline: False
```
**Symbols:**

```
ffffffff81810e85-ffffffff81810e99: usb_hub_create_port_device.cold (STB_LOCAL)
ffffffff81810a10-ffffffff81810d4b: usb_hub_create_port_device (STB_GLOBAL)
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
