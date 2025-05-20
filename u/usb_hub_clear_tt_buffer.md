# Function: <code>usb_hub_clear_tt_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81603e30)
Location: drivers/usb/core/hub.c:804
Inline: False
```
**Symbols:**

```
ffffffff81603e30-ffffffff81603f4a: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81663b20)
Location: drivers/usb/core/hub.c:806
Inline: False
```
**Symbols:**

```
ffffffff81663b20-ffffffff81663c41: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81691920)
Location: drivers/usb/core/hub.c:809
Inline: False
```
**Symbols:**

```
ffffffff81691920-ffffffff81691a41: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a6e50)
Location: drivers/usb/core/hub.c:818
Inline: False
```
**Symbols:**

```
ffffffff816a6e50-ffffffff816a6f6e: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81712220)
Location: drivers/usb/core/hub.c:818
Inline: False
```
**Symbols:**

```
ffffffff81712220-ffffffff8171233e: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81750f90)
Location: drivers/usb/core/hub.c:826
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff81750f90-ffffffff817510ae: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817753f0)
Location: drivers/usb/core/hub.c:827
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff817753f0-ffffffff8177550e: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:854
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff817ba075-ffffffff817ba092: usb_hub_clear_tt_buffer.cold (STB_LOCAL)
ffffffff817b3560-ffffffff817b365f: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:856
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff817ea8c5-ffffffff817ea8e2: usb_hub_clear_tt_buffer.cold (STB_LOCAL)
ffffffff817e3c90-ffffffff817e3d8f: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:858
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff818b9ee5-ffffffff818b9f02: usb_hub_clear_tt_buffer.cold (STB_LOCAL)
ffffffff818b32c0-ffffffff818b33bf: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:858
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff81c1aa0b-ffffffff81c1aa28: usb_hub_clear_tt_buffer.cold (STB_LOCAL)
ffffffff818c1c30-ffffffff818c1d2f: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:865
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff81c0c851-ffffffff81c0c86e: usb_hub_clear_tt_buffer.cold (STB_LOCAL)
ffffffff818a4d50-ffffffff818a4e52: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:865
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff81d137ee-ffffffff81d1380b: usb_hub_clear_tt_buffer.cold (STB_LOCAL)
ffffffff819399f0-ffffffff81939af2: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:865
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff81ede592-ffffffff81ede5af: usb_hub_clear_tt_buffer.cold (STB_LOCAL)
ffffffff81a91540-ffffffff81a9164c: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c135e0)
Location: drivers/usb/core/hub.c:869
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff81c135e0-ffffffff81c1370f: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7a3e0)
Location: drivers/usb/core/hub.c:869
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff81c7a3e0-ffffffff81c7a513: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d2efd0)
Location: drivers/usb/core/hub.c:889
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff81d2efd0-ffffffff81d2f132: usb_hub_clear_tt_buffer (STB_GLOBAL)
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
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a13d28)
Location: drivers/usb/core/hub.c:856
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffff800010a13d28-ffff800010a13e90: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aea8cc)
Location: drivers/usb/core/hub.c:856
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_handle_tt_clear
```
**Symbols:**

```
c0aea8cc-c0aea9cc: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ac98a0)
Location: drivers/usb/core/hub.c:856
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
c000000000ac98a0-c000000000ac9a10: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000637dd2)
Location: drivers/usb/core/hub.c:856
Inline: False
```
**Symbols:**

```
ffffffe000637dd2-ffffffe000637ee4: usb_hub_clear_tt_buffer (STB_GLOBAL)
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
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:856
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff817a2ca5-ffffffff817a2cc2: usb_hub_clear_tt_buffer.cold (STB_LOCAL)
ffffffff8179c070-ffffffff8179c16f: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:856
Inline: False
```
**Symbols:**

```
ffffffff81794ae5-ffffffff81794b02: usb_hub_clear_tt_buffer.cold (STB_LOCAL)
ffffffff8178dd00-ffffffff8178ddff: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:856
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff817df745-ffffffff817df762: usb_hub_clear_tt_buffer.cold (STB_LOCAL)
ffffffff817d8b10-ffffffff817d8c0f: usb_hub_clear_tt_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_hub_clear_tt_buffer(struct urb *urb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:856
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer
```
**Symbols:**

```
ffffffff817f9a35-ffffffff817f9a52: usb_hub_clear_tt_buffer.cold (STB_LOCAL)
ffffffff817f2e80-ffffffff817f2f7f: usb_hub_clear_tt_buffer (STB_GLOBAL)
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
