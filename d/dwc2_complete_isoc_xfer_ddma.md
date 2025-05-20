# Function: <code>dwc2_complete_isoc_xfer_ddma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162f3b5)
Location: drivers/usb/dwc2/hcd_ddma.c:860
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168ffce)
Location: drivers/usb/dwc2/hcd_ddma.c:960
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816be07e)
Location: drivers/usb/dwc2/hcd_ddma.c:960
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d2073)
Location: drivers/usb/dwc2/hcd_ddma.c:959
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173e6f5)
Location: drivers/usb/dwc2/hcd_ddma.c:960
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177f041)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a5817)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e4a1f)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818158df)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_complete_isoc_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e53b0)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff818e53b0-ffffffff818e578b: dwc2_complete_isoc_xfer_ddma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_complete_isoc_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818eefc0)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff818eefc0-ffffffff818ef331: dwc2_complete_isoc_xfer_ddma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_complete_isoc_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d2790)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff818d2790-ffffffff818d2afd: dwc2_complete_isoc_xfer_ddma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dwc2_complete_isoc_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196d0e0)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8196d0e0-ffffffff8196d452: dwc2_complete_isoc_xfer_ddma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dwc2_complete_isoc_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac7620)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81ac7620-ffffffff81ac79b2: dwc2_complete_isoc_xfer_ddma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dwc2_complete_isoc_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c518e0)
Location: drivers/usb/dwc2/hcd_ddma.c:931
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81c518e0-ffffffff81c51c72: dwc2_complete_isoc_xfer_ddma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dwc2_complete_isoc_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cb8ea0)
Location: drivers/usb/dwc2/hcd_ddma.c:931
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81cb8ea0-ffffffff81cb9238: dwc2_complete_isoc_xfer_ddma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dwc2_complete_isoc_xfer_ddma(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, enum dwc2_halt_status halt_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6dc10)
Location: drivers/usb/dwc2/hcd_ddma.c:931
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81d6dc10-ffffffff81d6dfa8: dwc2_complete_isoc_xfer_ddma (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4ea54)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (c0b20b20)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b166f8)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066b392)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cdcbf)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8180a75f)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8182486f)
Location: drivers/usb/dwc2/hcd_ddma.c:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
