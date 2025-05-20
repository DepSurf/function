# Function: <code>usb_hcd_map_urb_for_dma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8160d270)
Location: drivers/usb/core/hcd.c:1509
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff8160d270-ffffffff8160d7a5: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8166ce00)
Location: drivers/usb/core/hcd.c:1505
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff8166ce00-ffffffff8166d36b: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8169ab00)
Location: drivers/usb/core/hcd.c:1506
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff8169ab00-ffffffff8169b062: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff816afeb0)
Location: drivers/usb/core/hcd.c:1509
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff816afeb0-ffffffff816b04cb: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8171b430)
Location: drivers/usb/core/hcd.c:1498
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff8171b430-ffffffff8171b9dd: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8175a1f0)
Location: drivers/usb/core/hcd.c:1500
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff8175a1f0-ffffffff8175a789: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8177e770)
Location: drivers/usb/core/hcd.c:1498
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff8177e770-ffffffff8177ecbc: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:1400
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff817bf0ce-ffffffff817bf0e7: usb_hcd_map_urb_for_dma.cold (STB_LOCAL)
ffffffff817bcd00-ffffffff817bd23a: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817ed700)
Location: drivers/usb/core/hcd.c:1397
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff817ed700-ffffffff817edd78: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bcc90)
Location: drivers/usb/core/hcd.c:1398
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff818bcc90-ffffffff818bd25c: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818c9990)
Location: drivers/usb/core/hcd.c:1399
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff818c9990-ffffffff818c9e43: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818aca00)
Location: drivers/usb/core/hcd.c:1399
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff818aca00-ffffffff818acea8: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:1406
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff81d158f0-ffffffff81d15949: usb_hcd_map_urb_for_dma.cold (STB_LOCAL)
ffffffff81941a50-ffffffff81941f37: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:1406
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff81ee09ee-ffffffff81ee0a49: usb_hcd_map_urb_for_dma.cold (STB_LOCAL)
ffffffff81a9b070-ffffffff81a9b531: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:1407
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff8209e8a9-ffffffff8209e904: usb_hcd_map_urb_for_dma.cold (STB_LOCAL)
ffffffff81c1fec0-ffffffff81c20386: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:1411
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff8211fe3f-ffffffff8211fe92: usb_hcd_map_urb_for_dma.cold (STB_LOCAL)
ffffffff81c86e40-ffffffff81c87309: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:1386
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff82201615-ffffffff82201668: usb_hcd_map_urb_for_dma.cold (STB_LOCAL)
ffffffff81d3b8a0-ffffffff81d3bd69: usb_hcd_map_urb_for_dma (STB_GLOBAL)
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
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1c710)
Location: drivers/usb/core/hcd.c:1397
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffff800010a1c710-ffff800010a1cb78: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af5684)
Location: drivers/usb/core/hcd.c:1397
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
c0af5684-c0af5c20: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad7b40)
Location: drivers/usb/core/hcd.c:1397
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
c000000000ad7b40-c000000000ad8324: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe0006413ba)
Location: drivers/usb/core/hcd.c:1397
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffe0006413ba-ffffffe00064184a: usb_hcd_map_urb_for_dma (STB_GLOBAL)
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
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817a5ae0)
Location: drivers/usb/core/hcd.c:1397
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff817a5ae0-ffffffff817a6158: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81798010)
Location: drivers/usb/core/hcd.c:1397
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff81798010-ffffffff81798688: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817e2580)
Location: drivers/usb/core/hcd.c:1397
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff817e2580-ffffffff817e2bf8: usb_hcd_map_urb_for_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int usb_hcd_map_urb_for_dma(struct usb_hcd *hcd, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817fd2d0)
Location: drivers/usb/core/hcd.c:1397
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/host/xhci.c:xhci_map_urb_for_dma
```
**Symbols:**

```
ffffffff817fd2d0-ffffffff817fd948: usb_hcd_map_urb_for_dma (STB_GLOBAL)
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
