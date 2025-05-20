# Function: <code>xhci_endpoint_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164aa30)
Location: drivers/usb/host/xhci.c:2974
Inline: False
```
**Symbols:**

```
ffffffff8164aa30-ffffffff8164aa88: xhci_endpoint_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ab4a0)
Location: drivers/usb/host/xhci.c:2953
Inline: False
```
**Symbols:**

```
ffffffff816ab4a0-ffffffff816ab4f4: xhci_endpoint_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816d95c0)
Location: drivers/usb/host/xhci.c:2942
Inline: False
```
**Symbols:**

```
ffffffff816d95c0-ffffffff816d9614: xhci_endpoint_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816eda40)
Location: drivers/usb/host/xhci.c:2882
Inline: False
```
**Symbols:**

```
ffffffff816eda40-ffffffff816eda94: xhci_endpoint_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175a230)
Location: drivers/usb/host/xhci.c:2898
Inline: False
```
**Symbols:**

```
ffffffff8175a230-ffffffff8175a284: xhci_endpoint_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179ba30)
Location: drivers/usb/host/xhci.c:3026
Inline: False
```
**Symbols:**

```
ffffffff8179ba30-ffffffff8179bcbd: xhci_endpoint_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c1df0)
Location: drivers/usb/host/xhci.c:3043
Inline: False
```
**Symbols:**

```
ffffffff817c1df0-ffffffff817c207d: xhci_endpoint_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3074
Inline: False
```
**Symbols:**

```
ffffffff818017a0-ffffffff81801a07: xhci_endpoint_reset (STB_LOCAL)
ffffffff818079df-ffffffff81807a21: xhci_endpoint_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3125
Inline: False
```
**Symbols:**

```
ffffffff81832840-ffffffff81832b3a: xhci_endpoint_reset (STB_LOCAL)
ffffffff818388e7-ffffffff81838918: xhci_endpoint_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3128
Inline: False
```
**Symbols:**

```
ffffffff81905f30-ffffffff8190626e: xhci_endpoint_reset (STB_LOCAL)
ffffffff8190b2ec-ffffffff8190b31e: xhci_endpoint_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3262
Inline: False
```
**Symbols:**

```
ffffffff8190e6e0-ffffffff8190ea1e: xhci_endpoint_reset (STB_LOCAL)
ffffffff81c20d19-ffffffff81c20d4b: xhci_endpoint_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3181
Inline: False
```
**Symbols:**

```
ffffffff818f1bd0-ffffffff818f1f52: xhci_endpoint_reset (STB_LOCAL)
ffffffff81c12d41-ffffffff81c12d73: xhci_endpoint_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3193
Inline: False
```
**Symbols:**

```
ffffffff8198ed40-ffffffff8198f136: xhci_endpoint_reset (STB_LOCAL)
ffffffff81d1faa7-ffffffff81d1fad7: xhci_endpoint_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3229
Inline: False
```
**Symbols:**

```
ffffffff81aeb1c0-ffffffff81aeb5de: xhci_endpoint_reset (STB_LOCAL)
ffffffff81eeb646-ffffffff81eeb677: xhci_endpoint_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c77700)
Location: drivers/usb/host/xhci.c:3227
Inline: False
```
**Symbols:**

```
ffffffff81c77700-ffffffff81c77b59: xhci_endpoint_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cde7e0)
Location: drivers/usb/host/xhci.c:3067
Inline: False
```
**Symbols:**

```
ffffffff81cde7e0-ffffffff81cdec40: xhci_endpoint_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d99450)
Location: drivers/usb/host/xhci.c:3100
Inline: False
```
**Symbols:**

```
ffffffff81d99450-ffffffff81d998ec: xhci_endpoint_reset (STB_LOCAL)
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
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a6f200)
Location: drivers/usb/host/xhci.c:3125
Inline: False
```
**Symbols:**

```
ffff800010a6f200-ffff800010a6f554: xhci_endpoint_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b43084)
Location: drivers/usb/host/xhci.c:3125
Inline: False
```
**Symbols:**

```
c0b43084-c0b433a4: xhci_endpoint_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b43240)
Location: drivers/usb/host/xhci.c:3125
Inline: False
```
**Symbols:**

```
c000000000b43240-c000000000b436ac: xhci_endpoint_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000687f7c)
Location: drivers/usb/host/xhci.c:3125
Inline: False
```
**Symbols:**

```
ffffffe000687f7c-ffffffe00068829a: xhci_endpoint_reset (STB_LOCAL)
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
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3125
Inline: False
```
**Symbols:**

```
ffffffff817eac20-ffffffff817eaf1a: xhci_endpoint_reset (STB_LOCAL)
ffffffff817f0c97-ffffffff817f0cc8: xhci_endpoint_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3125
Inline: False
```
**Symbols:**

```
ffffffff817afd30-ffffffff817b002a: xhci_endpoint_reset (STB_LOCAL)
ffffffff817b5e2d-ffffffff817b5e5e: xhci_endpoint_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3125
Inline: False
```
**Symbols:**

```
ffffffff818276c0-ffffffff818279ba: xhci_endpoint_reset (STB_LOCAL)
ffffffff8182d767-ffffffff8182d798: xhci_endpoint_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xhci_endpoint_reset(struct usb_hcd *hcd, struct usb_host_endpoint *host_ep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3125
Inline: False
```
**Symbols:**

```
ffffffff81841660-ffffffff8184195a: xhci_endpoint_reset (STB_LOCAL)
ffffffff81847850-ffffffff81847881: xhci_endpoint_reset.cold (STB_LOCAL)
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
<b>Param added. </b>
<code>struct usb_host_endpoint *host_ep</code>
</li>
<li>
<b>Param removed. </b>
<code>struct usb_host_endpoint *ep</code>
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
