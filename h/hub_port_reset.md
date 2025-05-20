# Function: <code>hub_port_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816059e0)
Location: drivers/usb/core/hub.c:2794
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff816059e0-ffffffff81606031: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81665780)
Location: drivers/usb/core/hub.c:2791
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81665780-ffffffff81665d99: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81693200)
Location: drivers/usb/core/hub.c:2717
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81693200-ffffffff81693824: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a8890)
Location: drivers/usb/core/hub.c:2745
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff816a8890-ffffffff816a8f20: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81713c90)
Location: drivers/usb/core/hub.c:2748
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81713c90-ffffffff81714338: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81752a00)
Location: drivers/usb/core/hub.c:2788
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81752a00-ffffffff817530e8: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81776e80)
Location: drivers/usb/core/hub.c:2801
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81776e80-ffffffff81777543: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2841
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff817b4f20-ffffffff817b5565: hub_port_reset (STB_LOCAL)
ffffffff817ba339-ffffffff817ba3ac: hub_port_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2885
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff817e5650-ffffffff817e5c95: hub_port_reset (STB_LOCAL)
ffffffff817eab89-ffffffff817eabfc: hub_port_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2890
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff818b5680-ffffffff818b5aed: hub_port_reset (STB_LOCAL)
ffffffff818ba03f-ffffffff818ba0ad: hub_port_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2908
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff818c3fd0-ffffffff818c443d: hub_port_reset (STB_LOCAL)
ffffffff81c1ab65-ffffffff81c1abd3: hub_port_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2963
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff818a7250-ffffffff818a76bb: hub_port_reset (STB_LOCAL)
ffffffff81c0c9ab-ffffffff81c0ca19: hub_port_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2967
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff8193c0e0-ffffffff8193c54d: hub_port_reset (STB_LOCAL)
ffffffff81d1392e-ffffffff81d1399c: hub_port_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2969
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81a93df0-ffffffff81a94287: hub_port_reset (STB_LOCAL)
ffffffff81ede6dc-ffffffff81ede747: hub_port_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c16050)
Location: drivers/usb/core/hub.c:2945
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81c16050-ffffffff81c16561: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7ce70)
Location: drivers/usb/core/hub.c:2965
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81c7ce70-ffffffff81c7d372: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d31a30)
Location: drivers/usb/core/hub.c:2967
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81d31a30-ffffffff81d31f1c: hub_port_reset (STB_LOCAL)
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
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a144b0)
Location: drivers/usb/core/hub.c:2885
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffff800010a144b0-ffff800010a14b28: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aec538)
Location: drivers/usb/core/hub.c:2885
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
c0aec538-c0aeccf0: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acc310)
Location: drivers/usb/core/hub.c:2885
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
c000000000acc310-c000000000accba4: hub_port_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000639574)
Location: drivers/usb/core/hub.c:2885
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffe000639574-ffffffe000639c1e: hub_port_reset (STB_LOCAL)
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
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2885
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff8179da30-ffffffff8179e075: hub_port_reset (STB_LOCAL)
ffffffff817a2f69-ffffffff817a2fdc: hub_port_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2885
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff8178f6b0-ffffffff8178fcf5: hub_port_reset (STB_LOCAL)
ffffffff81794da9-ffffffff81794e1c: hub_port_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2885
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff817da4d0-ffffffff817dab15: hub_port_reset (STB_LOCAL)
ffffffff817dfa09-ffffffff817dfa7c: hub_port_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hub_port_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2885
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff817f4760-ffffffff817f4da5: hub_port_reset (STB_LOCAL)
ffffffff817f9cf9-ffffffff817f9d6c: hub_port_reset.cold (STB_LOCAL)
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
