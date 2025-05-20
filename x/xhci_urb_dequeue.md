# Function: <code>xhci_urb_dequeue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164bcc0)
Location: drivers/usb/host/xhci.c:1528
Inline: False
```
**Symbols:**

```
ffffffff8164bcc0-ffffffff8164c08c: xhci_urb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ac6a0)
Location: drivers/usb/host/xhci.c:1494
Inline: False
```
**Symbols:**

```
ffffffff816ac6a0-ffffffff816aca10: xhci_urb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816da7d0)
Location: drivers/usb/host/xhci.c:1497
Inline: False
```
**Symbols:**

```
ffffffff816da7d0-ffffffff816dab1b: xhci_urb_dequeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816eeb50)
Location: drivers/usb/host/xhci.c:1429
Inline: False
```
**Symbols:**

```
ffffffff816eeb50-ffffffff816eef25: xhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175b3a0)
Location: drivers/usb/host/xhci.c:1435
Inline: False
```
**Symbols:**

```
ffffffff8175b3a0-ffffffff8175b778: xhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179bcc0)
Location: drivers/usb/host/xhci.c:1546
Inline: False
```
**Symbols:**

```
ffffffff8179bcc0-ffffffff8179c12d: xhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c2080)
Location: drivers/usb/host/xhci.c:1563
Inline: False
```
**Symbols:**

```
ffffffff817c2080-ffffffff817c24ed: xhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1588
Inline: False
```
**Symbols:**

```
ffffffff81801a10-ffffffff81801eb0: xhci_urb_dequeue (STB_LOCAL)
ffffffff81807a21-ffffffff81807a58: xhci_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1597
Inline: False
```
**Symbols:**

```
ffffffff81832c40-ffffffff818330e0: xhci_urb_dequeue (STB_LOCAL)
ffffffff81838918-ffffffff8183894f: xhci_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1600
Inline: False
```
**Symbols:**

```
ffffffff81906270-ffffffff819066c2: xhci_urb_dequeue (STB_LOCAL)
ffffffff8190b31e-ffffffff8190b359: xhci_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1735
Inline: False
```
**Symbols:**

```
ffffffff8190ea20-ffffffff8190ee59: xhci_urb_dequeue (STB_LOCAL)
ffffffff81c20d4b-ffffffff81c20d86: xhci_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1735
Inline: False
```
**Symbols:**

```
ffffffff818f1f60-ffffffff818f2398: xhci_urb_dequeue (STB_LOCAL)
ffffffff81c12d73-ffffffff81c12db0: xhci_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1747
Inline: False
```
**Symbols:**

```
ffffffff8198f140-ffffffff8198f5e7: xhci_urb_dequeue (STB_LOCAL)
ffffffff81d1fad7-ffffffff81d1fb14: xhci_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1788
Inline: False
```
**Symbols:**

```
ffffffff81aeb5e0-ffffffff81aebaa0: xhci_urb_dequeue (STB_LOCAL)
ffffffff81eeb677-ffffffff81eeb6b4: xhci_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c77b70)
Location: drivers/usb/host/xhci.c:1786
Inline: False
```
**Symbols:**

```
ffffffff81c77b70-ffffffff81c78073: xhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdec50)
Location: drivers/usb/host/xhci.c:1626
Inline: False
```
**Symbols:**

```
ffffffff81cdec50-ffffffff81cdf173: xhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d93bd0)
Location: drivers/usb/host/xhci.c:1663
Inline: False
```
**Symbols:**

```
ffffffff81d93bd0-ffffffff81d940f3: xhci_urb_dequeue (STB_LOCAL)
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
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a700c0)
Location: drivers/usb/host/xhci.c:1597
Inline: False
```
**Symbols:**

```
ffff800010a700c0-ffff800010a705fc: xhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b434b0)
Location: drivers/usb/host/xhci.c:1597
Inline: False
```
**Symbols:**

```
c0b434b0-c0b43948: xhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b445c0)
Location: drivers/usb/host/xhci.c:1597
Inline: False
```
**Symbols:**

```
c000000000b445c0-c000000000b44c3c: xhci_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe0006883a2)
Location: drivers/usb/host/xhci.c:1597
Inline: False
```
**Symbols:**

```
ffffffe0006883a2-ffffffe000688782: xhci_urb_dequeue (STB_LOCAL)
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
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1597
Inline: False
```
**Symbols:**

```
ffffffff817eb020-ffffffff817eb4c0: xhci_urb_dequeue (STB_LOCAL)
ffffffff817f0cc8-ffffffff817f0cff: xhci_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1597
Inline: False
```
**Symbols:**

```
ffffffff817b0130-ffffffff817b05d0: xhci_urb_dequeue (STB_LOCAL)
ffffffff817b5e5e-ffffffff817b5e95: xhci_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1597
Inline: False
```
**Symbols:**

```
ffffffff81827ac0-ffffffff81827f60: xhci_urb_dequeue (STB_LOCAL)
ffffffff8182d798-ffffffff8182d7cf: xhci_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_urb_dequeue(struct usb_hcd *hcd, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1597
Inline: False
```
**Symbols:**

```
ffffffff81841a60-ffffffff81841f1d: xhci_urb_dequeue (STB_LOCAL)
ffffffff81847881-ffffffff818478b8: xhci_urb_dequeue.cold (STB_LOCAL)
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
