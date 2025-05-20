# Function: <code>xhci_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8165c5d0)
Location: drivers/usb/host/xhci-ring.c:2686
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff8165c5d0-ffffffff8165d0c1: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816bcdd0)
Location: drivers/usb/host/xhci-ring.c:2715
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff816bcdd0-ffffffff816bd83e: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816eace0)
Location: drivers/usb/host/xhci-ring.c:2617
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff816eace0-ffffffff816eb6ec: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816ff110)
Location: drivers/usb/host/xhci-ring.c:2715
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff816ff110-ffffffff816ffbec: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8176bd00)
Location: drivers/usb/host/xhci-ring.c:2719
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff8176bd00-ffffffff8176c846: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817ad0e0)
Location: drivers/usb/host/xhci-ring.c:2638
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff817ad0e0-ffffffff817ad577: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d33b0)
Location: drivers/usb/host/xhci-ring.c:2702
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff817d33b0-ffffffff817d384b: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2748
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff81813ac6-ffffffff81813ba1: xhci_irq.cold (STB_LOCAL)
ffffffff81812970-ffffffff81812d89: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2785
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff81844cab-ffffffff81844d68: xhci_irq.cold (STB_LOCAL)
ffffffff81843bd0-ffffffff81843f95: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2831
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff819175fd-ffffffff81917639: xhci_irq.cold (STB_LOCAL)
ffffffff81916810-ffffffff8191697b: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2838
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff81c22508-ffffffff81c22544: xhci_irq.cold (STB_LOCAL)
ffffffff8191dda0-ffffffff8191df0b: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3014
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff81c146ba-ffffffff81c146f6: xhci_irq.cold (STB_LOCAL)
ffffffff81900710-ffffffff81900866: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3079
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff81d21831-ffffffff81d2186e: xhci_irq.cold (STB_LOCAL)
ffffffff8199fe80-ffffffff819a000d: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3013
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff81eed483-ffffffff81eed4b4: xhci_irq.cold (STB_LOCAL)
ffffffff81afd540-ffffffff81afd6cf: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c8c1d0)
Location: drivers/usb/host/xhci-ring.c:3015
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff81c8c1d0-ffffffff81c8c3b6: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cf2d50)
Location: drivers/usb/host/xhci-ring.c:3034
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff81cf2d50-ffffffff81cf2f44: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da8690)
Location: drivers/usb/host/xhci-ring.c:3077
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff81da8690-ffffffff81da888e: xhci_irq (STB_GLOBAL)
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
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a82cb0)
Location: drivers/usb/host/xhci-ring.c:2785
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffff800010a82cb0-ffff800010a831b4: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b56544)
Location: drivers/usb/host/xhci-ring.c:2785
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
c0b56544-c0b56a38: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b5c5c0)
Location: drivers/usb/host/xhci-ring.c:2785
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
c000000000b5c5c0-c000000000b5cc88: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000699116)
Location: drivers/usb/host/xhci-ring.c:2785
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffe000699116-ffffffe00069958e: xhci_irq (STB_GLOBAL)
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
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2785
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff817fd05b-ffffffff817fd118: xhci_irq.cold (STB_LOCAL)
ffffffff817fbf80-ffffffff817fc345: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2785
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff817c21fb-ffffffff817c22b8: xhci_irq.cold (STB_LOCAL)
ffffffff817c1120-ffffffff817c14e5: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2785
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff81839b2b-ffffffff81839be8: xhci_irq.cold (STB_LOCAL)
ffffffff81838a50-ffffffff81838e15: xhci_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t xhci_irq(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2785
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_msi_irq
```
**Symbols:**

```
ffffffff81853f7e-ffffffff8185403b: xhci_irq.cold (STB_LOCAL)
ffffffff81852ea0-ffffffff8185327e: xhci_irq (STB_GLOBAL)
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
