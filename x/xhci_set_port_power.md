# Function: <code>xhci_set_port_power</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff816ffc70)
Location: drivers/usb/host/xhci-hub.c:570
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff816ffc70-ffffffff816ffd5b: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8176c8d0)
Location: drivers/usb/host/xhci-hub.c:571
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8176c8d0-ffffffff8176c9bb: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817ad5a0)
Location: drivers/usb/host/xhci-hub.c:558
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817ad5a0-ffffffff817ad69c: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817d3870)
Location: drivers/usb/host/xhci-hub.c:558
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817d3870-ffffffff817d396c: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81813bb0)
Location: drivers/usb/host/xhci-hub.c:559
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81813bb0-ffffffff81813cef: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81844d70)
Location: drivers/usb/host/xhci-hub.c:568
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81844d70-ffffffff81844eaf: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81917fb0)
Location: drivers/usb/host/xhci-hub.c:568
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81917fb0-ffffffff819180eb: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8191e8d0)
Location: drivers/usb/host/xhci-hub.c:568
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff8191e8d0-ffffffff8191ea0b: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81901fe0)
Location: drivers/usb/host/xhci-hub.c:654
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81901fe0-ffffffff8190211b: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff819a19c0)
Location: drivers/usb/host/xhci-hub.c:655
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff819a19c0-ffffffff819a1af8: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81aff730)
Location: drivers/usb/host/xhci-hub.c:655
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81aff730-ffffffff81aff881: xhci_set_port_power (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81c8e480)
Location: drivers/usb/host/xhci-hub.c:669
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81c8e480-ffffffff81c8e5d1: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct xhci_port *port, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81cf4a30)
Location: drivers/usb/host/xhci-hub.c:676
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81cf4a30-ffffffff81cf4b49: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct xhci_port *port, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81daa320)
Location: drivers/usb/host/xhci-hub.c:676
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81daa320-ffffffff81daa439: xhci_set_port_power (STB_LOCAL)
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
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffff800010a836f8)
Location: drivers/usb/host/xhci-hub.c:568
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffff800010a836f8-ffff800010a838ec: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (c0b56d38)
Location: drivers/usb/host/xhci-hub.c:568
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
c0b56d38-c0b56e70: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (c000000000b5d470)
Location: drivers/usb/host/xhci-hub.c:568
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
c000000000b5d470-c000000000b5d688: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffe000699812)
Location: drivers/usb/host/xhci-hub.c:568
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffe000699812-ffffffe000699996: xhci_set_port_power (STB_LOCAL)
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
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817fd120)
Location: drivers/usb/host/xhci-hub.c:568
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817fd120-ffffffff817fd25f: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817c22c0)
Location: drivers/usb/host/xhci-hub.c:568
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817c22c0-ffffffff817c23ff: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81839bf0)
Location: drivers/usb/host/xhci-hub.c:568
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81839bf0-ffffffff81839d2f: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xhci_set_port_power(struct xhci_hcd *xhci, struct usb_hcd *hcd, u16 index, bool on, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81854040)
Location: drivers/usb/host/xhci-hub.c:568
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81854040-ffffffff8185417f: xhci_set_port_power (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xhci_port *port</code>
</li>
<li>
<b>Param removed. </b>
<code>struct usb_hcd *hcd</code>
</li>
<li>
<b>Param removed. </b>
<code>u16 index</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, hcd, index, on, flags</code> ➡️ <code>xhci, port, on, flags</code>
</li>
</ul>
</details>
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
