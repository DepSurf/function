# Function: <code>xhci_unmap_urb_for_dma</code>

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
void xhci_unmap_urb_for_dma(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190c840)
Location: drivers/usb/host/xhci.c:1395
Inline: False
```
**Symbols:**

```
ffffffff8190c840-ffffffff8190c910: xhci_unmap_urb_for_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xhci_unmap_urb_for_dma(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818efd60)
Location: drivers/usb/host/xhci.c:1403
Inline: False
```
**Symbols:**

```
ffffffff818efd60-ffffffff818efe7c: xhci_unmap_urb_for_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xhci_unmap_urb_for_dma(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8198c970)
Location: drivers/usb/host/xhci.c:1412
Inline: False
```
**Symbols:**

```
ffffffff8198c970-ffffffff8198ca89: xhci_unmap_urb_for_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xhci_unmap_urb_for_dma(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ae8bf0)
Location: drivers/usb/host/xhci.c:1453
Inline: False
```
**Symbols:**

```
ffffffff81ae8bf0-ffffffff81ae8d1d: xhci_unmap_urb_for_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_unmap_urb_for_dma(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c74df0)
Location: drivers/usb/host/xhci.c:1451
Inline: False
```
**Symbols:**

```
ffffffff81c74df0-ffffffff81c74f1d: xhci_unmap_urb_for_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_unmap_urb_for_dma(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdbf10)
Location: drivers/usb/host/xhci.c:1291
Inline: False
```
**Symbols:**

```
ffffffff81cdbf10-ffffffff81cdc03d: xhci_unmap_urb_for_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_unmap_urb_for_dma(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d90f30)
Location: drivers/usb/host/xhci.c:1338
Inline: False
```
**Symbols:**

```
ffffffff81d90f30-ffffffff81d9105d: xhci_unmap_urb_for_dma (STB_LOCAL)
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
