# Function: <code>choose_devnum</code>

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
In drivers/usb/core/hub.c (ffffffff81609b92)
Location: drivers/usb/core/hub.c:2077
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff816696f0)
Location: drivers/usb/core/hub.c:2074
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff81697420)
Location: drivers/usb/core/hub.c:1993
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff816ac85c)
Location: drivers/usb/core/hub.c:2015
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff81717d0c)
Location: drivers/usb/core/hub.c:2015
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff81756b83)
Location: drivers/usb/core/hub.c:2039
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff8177b023)
Location: drivers/usb/core/hub.c:2050
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff817b8d2d)
Location: drivers/usb/core/hub.c:2088
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff817e957d)
Location: drivers/usb/core/hub.c:2099
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void choose_devnum(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b3df0)
Location: drivers/usb/core/hub.c:2106
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff818b3df0-ffffffff818b3ea0: choose_devnum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void choose_devnum(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c2760)
Location: drivers/usb/core/hub.c:2106
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff818c2760-ffffffff818c2810: choose_devnum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818aa39a)
Location: drivers/usb/core/hub.c:2113
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193f2b7)
Location: drivers/usb/core/hub.c:2116
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a97364)
Location: drivers/usb/core/hub.c:2116
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1a01a)
Location: drivers/usb/core/hub.c:2126
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c8103a)
Location: drivers/usb/core/hub.c:2141
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d35aca)
Location: drivers/usb/core/hub.c:2163
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffff800010a18984)
Location: drivers/usb/core/hub.c:2099
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (c0af0d24)
Location: drivers/usb/core/hub.c:2099
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (c000000000ad1c1c)
Location: drivers/usb/core/hub.c:2099
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffe00063d6f2)
Location: drivers/usb/core/hub.c:2099
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff817a195d)
Location: drivers/usb/core/hub.c:2099
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff81793797)
Location: drivers/usb/core/hub.c:2099
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff817de3fd)
Location: drivers/usb/core/hub.c:2099
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
In drivers/usb/core/hub.c (ffffffff817f856e)
Location: drivers/usb/core/hub.c:2099
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
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
</ul>
