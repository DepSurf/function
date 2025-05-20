# Function: <code>xhci_get_port_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, __le32 **port_array, u16 wIndex, u32 raw_port_status, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8165d480)
Location: drivers/usb/host/xhci-hub.c:697
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8165d480-ffffffff8165dba5: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, __le32 **port_array, u16 wIndex, u32 raw_port_status, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff816bdbf0)
Location: drivers/usb/host/xhci-hub.c:700
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff816bdbf0-ffffffff816be2a9: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, __le32 **port_array, u16 wIndex, u32 raw_port_status, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff816ebaa0)
Location: drivers/usb/host/xhci-hub.c:700
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff816ebaa0-ffffffff816ec159: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, __le32 **port_array, u16 wIndex, u32 raw_port_status, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817000e0)
Location: drivers/usb/host/xhci-hub.c:838
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817000e0-ffffffff8170078c: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, __le32 **port_array, u16 wIndex, u32 raw_port_status, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8176cd80)
Location: drivers/usb/host/xhci-hub.c:842
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8176cd80-ffffffff8176d42c: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817ada60)
Location: drivers/usb/host/xhci-hub.c:831
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817ada60-ffffffff817ae139: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817d3d30)
Location: drivers/usb/host/xhci-hub.c:997
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817d3d30-ffffffff817d4507: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81814160)
Location: drivers/usb/host/xhci-hub.c:1007
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81814160-ffffffff81814949: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81845320)
Location: drivers/usb/host/xhci-hub.c:1026
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81845320-ffffffff81845b67: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff819187d0)
Location: drivers/usb/host/xhci-hub.c:1029
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff819187d0-ffffffff81918a55: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8191f0f0)
Location: drivers/usb/host/xhci-hub.c:1029
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8191f0f0-ffffffff8191f397: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81902810)
Location: drivers/usb/host/xhci-hub.c:1115
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81902810-ffffffff81902ab9: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1117
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff819a25a0-ffffffff819a299b: xhci_get_port_status (STB_LOCAL)
ffffffff81d21a1b-ffffffff81d21ab2: xhci_get_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1121
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81b00240-ffffffff81b0048b: xhci_get_port_status (STB_LOCAL)
ffffffff81eed6cd-ffffffff81eed6ec: xhci_get_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81c8f180-ffffffff81c8f3cb: xhci_get_port_status (STB_LOCAL)
ffffffff820a5c68-ffffffff820a5c87: xhci_get_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1147
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81cf5ab0-ffffffff81cf5c37: xhci_get_port_status (STB_LOCAL)
ffffffff82127024-ffffffff8212703d: xhci_get_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1148
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81dab3e0-ffffffff81dab567: xhci_get_port_status (STB_LOCAL)
ffffffff8220897b-ffffffff82208994: xhci_get_port_status.cold (STB_LOCAL)
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
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffff800010a83ec8)
Location: drivers/usb/host/xhci-hub.c:1026
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffff800010a83ec8-ffff800010a8472c: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (c0b57390)
Location: drivers/usb/host/xhci-hub.c:1026
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
c0b57390-c0b57afc: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (c000000000b5daf0)
Location: drivers/usb/host/xhci-hub.c:1026
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
c000000000b5daf0-c000000000b5e4fc: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffe000699e6c)
Location: drivers/usb/host/xhci-hub.c:1026
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffe000699e6c-ffffffe00069a668: xhci_get_port_status (STB_LOCAL)
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
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817fd6d0)
Location: drivers/usb/host/xhci-hub.c:1026
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817fd6d0-ffffffff817fdf17: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817c2870)
Location: drivers/usb/host/xhci-hub.c:1026
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817c2870-ffffffff817c30b7: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8183a1a0)
Location: drivers/usb/host/xhci-hub.c:1026
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8183a1a0-ffffffff8183a9e7: xhci_get_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 xhci_get_port_status(struct usb_hcd *hcd, struct xhci_bus_state *bus_state, u16 wIndex, u32 raw_port_status, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81854630)
Location: drivers/usb/host/xhci-hub.c:1026
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81854630-ffffffff81854e77: xhci_get_port_status (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>__le32 **port_array</code>
</li>
<li>
<b>Param reordered. </b>
<code>hcd, bus_state, port_array, wIndex, raw_port_status, flags</code> ➡️ <code>hcd, bus_state, wIndex, raw_port_status, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int flags</code> ➡️ <code>long unsigned int *flags</code>
</li>
</ul>
</details>
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
