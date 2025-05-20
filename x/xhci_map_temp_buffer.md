# Function: <code>xhci_map_temp_buffer</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_map_temp_buffer(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190cab0)
Location: drivers/usb/host/xhci.c:1270
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff8190cab0-ffffffff8190cbfe: xhci_map_temp_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_map_temp_buffer(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f0010)
Location: drivers/usb/host/xhci.c:1273
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff818f0010-ffffffff818f0168: xhci_map_temp_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_map_temp_buffer(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1282
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff8198cca0-ffffffff8198ce07: xhci_map_temp_buffer (STB_LOCAL)
ffffffff81d1f807-ffffffff81d1f81c: xhci_map_temp_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_map_temp_buffer(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1323
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff81ae8ea0-ffffffff81ae9032: xhci_map_temp_buffer (STB_LOCAL)
ffffffff81eeb3e4-ffffffff81eeb401: xhci_map_temp_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xhci_map_temp_buffer(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1321
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff81c75150-ffffffff81c752e2: xhci_map_temp_buffer (STB_LOCAL)
ffffffff820a5681-ffffffff820a569e: xhci_map_temp_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xhci_map_temp_buffer(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1161
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff81cdc270-ffffffff81cdc3ff: xhci_map_temp_buffer (STB_LOCAL)
ffffffff82126b82-ffffffff82126b97: xhci_map_temp_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xhci_map_temp_buffer(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1208
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff81d91290-ffffffff81d9141f: xhci_map_temp_buffer (STB_LOCAL)
ffffffff82208385-ffffffff8220839a: xhci_map_temp_buffer.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
