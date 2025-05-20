# Function: <code>xhci_cleanup_stalled_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81651d30)
Location: drivers/usb/host/xhci.c:2925
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff81651d30-ffffffff81651f36: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816b2610)
Location: drivers/usb/host/xhci.c:2904
Inline: False
```
**Symbols:**

```
ffffffff816b2610-ffffffff816b281c: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816e07c0)
Location: drivers/usb/host/xhci.c:2893
Inline: False
```
**Symbols:**

```
ffffffff816e07c0-ffffffff816e09cc: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f4450)
Location: drivers/usb/host/xhci.c:2833
Inline: False
```
**Symbols:**

```
ffffffff816f4450-ffffffff816f462b: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81760710)
Location: drivers/usb/host/xhci.c:2849
Inline: False
```
**Symbols:**

```
ffffffff81760710-ffffffff817608eb: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817a1140)
Location: drivers/usb/host/xhci.c:2975
Inline: False
```
**Symbols:**

```
ffffffff817a1140-ffffffff817a1328: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c7400)
Location: drivers/usb/host/xhci.c:2992
Inline: False
```
**Symbols:**

```
ffffffff817c7400-ffffffff817c75e8: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3023
Inline: False
```
**Symbols:**

```
ffffffff818083a4-ffffffff818083f6: xhci_cleanup_stalled_ring.cold (STB_LOCAL)
ffffffff81806790-ffffffff81806928: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3032
Inline: False
```
**Symbols:**

```
ffffffff8183928b-ffffffff818392dd: xhci_cleanup_stalled_ring.cold (STB_LOCAL)
ffffffff81837640-ffffffff818377d8: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81909de0)
Location: drivers/usb/host/xhci.c:3035
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
```
**Symbols:**

```
ffffffff81909de0-ffffffff81909ecd: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81912640)
Location: drivers/usb/host/xhci.c:3169
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
```
**Symbols:**

```
ffffffff81912640-ffffffff8191272d: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a756a8)
Location: drivers/usb/host/xhci.c:3032
Inline: False
```
**Symbols:**

```
ffff800010a756a8-ffff800010a75898: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b49170)
Location: drivers/usb/host/xhci.c:3032
Inline: False
```
**Symbols:**

```
c0b49170-c0b49378: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b4b9b0)
Location: drivers/usb/host/xhci.c:3032
Inline: False
```
**Symbols:**

```
c000000000b4b9b0-c000000000b4bc1c: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068d752)
Location: drivers/usb/host/xhci.c:3032
Inline: False
```
**Symbols:**

```
ffffffe00068d752-ffffffe00068d900: xhci_cleanup_stalled_ring (STB_GLOBAL)
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
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3032
Inline: False
```
**Symbols:**

```
ffffffff817f163b-ffffffff817f168d: xhci_cleanup_stalled_ring.cold (STB_LOCAL)
ffffffff817ef9f0-ffffffff817efb88: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3032
Inline: False
```
**Symbols:**

```
ffffffff817b67d1-ffffffff817b6823: xhci_cleanup_stalled_ring.cold (STB_LOCAL)
ffffffff817b4b00-ffffffff817b4c98: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3032
Inline: False
```
**Symbols:**

```
ffffffff8182e10b-ffffffff8182e15d: xhci_cleanup_stalled_ring.cold (STB_LOCAL)
ffffffff8182c4c0-ffffffff8182c658: xhci_cleanup_stalled_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xhci_cleanup_stalled_ring(struct xhci_hcd *xhci, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3032
Inline: False
```
**Symbols:**

```
ffffffff818481f1-ffffffff81848243: xhci_cleanup_stalled_ring.cold (STB_LOCAL)
ffffffff818464b0-ffffffff81846648: xhci_cleanup_stalled_ring (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int stream_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, ep_index, td</code> ➡️ <code>xhci, ep_index, stream_id, td</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int slot_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, ep_index, stream_id, td</code> ➡️ <code>xhci, slot_id, ep_index, stream_id, td</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
