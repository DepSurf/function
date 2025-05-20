# Function: <code>xhci_move_dequeue_past_td</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:553
Inline: True
```
**Symbols:**

```
ffffffff818fe210-ffffffff818fe598: xhci_move_dequeue_past_td.constprop.0 (STB_LOCAL)
ffffffff81c13fb3-ffffffff81c1404a: xhci_move_dequeue_past_td.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_move_dequeue_past_td(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:566
Inline: False
```
**Symbols:**

```
ffffffff8199e040-ffffffff8199e4e3: xhci_move_dequeue_past_td (STB_LOCAL)
ffffffff81d212e8-ffffffff81d2137f: xhci_move_dequeue_past_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_move_dequeue_past_td(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:566
Inline: False
```
**Symbols:**

```
ffffffff81afb400-ffffffff81afb8e4: xhci_move_dequeue_past_td (STB_LOCAL)
ffffffff81eecec4-ffffffff81eecf53: xhci_move_dequeue_past_td.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_move_dequeue_past_td(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c89c60)
Location: drivers/usb/host/xhci-ring.c:566
Inline: False
```
**Symbols:**

```
ffffffff81c89c60-ffffffff81c8a1d7: xhci_move_dequeue_past_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_move_dequeue_past_td(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81ceda90)
Location: drivers/usb/host/xhci-ring.c:620
Inline: False
```
**Symbols:**

```
ffffffff81ceda90-ffffffff81cedf7b: xhci_move_dequeue_past_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_move_dequeue_past_td(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da3860)
Location: drivers/usb/host/xhci-ring.c:628
Inline: False
```
**Symbols:**

```
ffffffff81da3860-ffffffff81da3d62: xhci_move_dequeue_past_td (STB_LOCAL)
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
