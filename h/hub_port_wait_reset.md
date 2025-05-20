# Function: <code>hub_port_wait_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81605c2d)
Location: drivers/usb/core/hub.c:2713
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816659fc)
Location: drivers/usb/core/hub.c:2710
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8169347c)
Location: drivers/usb/core/hub.c:2629
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a8b35)
Location: drivers/usb/core/hub.c:2657
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81713f35)
Location: drivers/usb/core/hub.c:2657
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81752c86)
Location: drivers/usb/core/hub.c:2689
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8177714b)
Location: drivers/usb/core/hub.c:2702
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b4fdb)
Location: drivers/usb/core/hub.c:2742
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e570b)
Location: drivers/usb/core/hub.c:2786
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hub_port_wait_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b5320)
Location: drivers/usb/core/hub.c:2791
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff818b5320-ffffffff818b567d: hub_port_wait_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hub_port_wait_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c3c70)
Location: drivers/usb/core/hub.c:2809
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff818c3c70-ffffffff818c3fcd: hub_port_wait_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hub_port_wait_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a6df0)
Location: drivers/usb/core/hub.c:2864
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff818a6df0-ffffffff818a724d: hub_port_wait_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hub_port_wait_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193bc80)
Location: drivers/usb/core/hub.c:2868
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff8193bc80-ffffffff8193c0db: hub_port_wait_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hub_port_wait_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a93970)
Location: drivers/usb/core/hub.c:2870
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff81a93970-ffffffff81a93def: hub_port_wait_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hub_port_wait_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c15bc0)
Location: drivers/usb/core/hub.c:2846
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff81c15bc0-ffffffff81c1603f: hub_port_wait_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hub_port_wait_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7c9d0)
Location: drivers/usb/core/hub.c:2866
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff81c7c9d0-ffffffff81c7ce5c: hub_port_wait_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hub_port_wait_reset(struct usb_hub *hub, int port1, struct usb_device *udev, unsigned int delay, bool warm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d31620)
Location: drivers/usb/core/hub.c:2870
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff81d31620-ffffffff81d31a17: hub_port_wait_reset (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a145a8)
Location: drivers/usb/core/hub.c:2786
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aec630)
Location: drivers/usb/core/hub.c:2786
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acc4a0)
Location: drivers/usb/core/hub.c:2786
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000639608)
Location: drivers/usb/core/hub.c:2786
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179daeb)
Location: drivers/usb/core/hub.c:2786
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178f76b)
Location: drivers/usb/core/hub.c:2786
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817da58b)
Location: drivers/usb/core/hub.c:2786
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f481b)
Location: drivers/usb/core/hub.c:2786
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
```
</details>
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
