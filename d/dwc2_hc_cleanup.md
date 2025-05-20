# Function: <code>dwc2_hc_cleanup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81622db0)
Location: drivers/usb/dwc2/core.c:1556
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff81622db0-ffffffff81622df2: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816851a1)
Location: drivers/usb/dwc2/hcd.c:1074
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff81687db0-ffffffff81687e07: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b33cc)
Location: drivers/usb/dwc2/hcd.c:1104
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff816b5fe0-ffffffff816b6037: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816c76a8)
Location: drivers/usb/dwc2/hcd.c:1121
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff816ca300-ffffffff816ca357: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81733b1b)
Location: drivers/usb/dwc2/hcd.c:1127
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff81736840-ffffffff81736897: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81773f31)
Location: drivers/usb/dwc2/hcd.c:1162
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
Direct callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff81776290-ffffffff817762e7: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179b9b0)
Location: drivers/usb/dwc2/hcd.c:1155
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff8179b9b0-ffffffff8179ba1c: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817daaa0)
Location: drivers/usb/dwc2/hcd.c:965
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff817daaa0-ffffffff817dab0c: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8180b9c0)
Location: drivers/usb/dwc2/hcd.c:965
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff8180b9c0-ffffffff8180ba2c: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818dc740)
Location: drivers/usb/dwc2/hcd.c:965
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff818dc740-ffffffff818dc7a9: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e65d0)
Location: drivers/usb/dwc2/hcd.c:965
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_cleanup_channels
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff818e65d0-ffffffff818e6639: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c8023)
Location: drivers/usb/dwc2/hcd.c:963
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff818c89c0-ffffffff818c8a2c: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:963
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff81d1b281-ffffffff81d1b2ab: dwc2_hc_cleanup.cold (STB_LOCAL)
ffffffff819610e0-ffffffff8196118e: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:959
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff81ee6511-ffffffff81ee653b: dwc2_hc_cleanup.cold (STB_LOCAL)
ffffffff81abb4e0-ffffffff81abb5aa: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:930
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff820a1da3-ffffffff820a1dcd: dwc2_hc_cleanup.cold (STB_LOCAL)
ffffffff81c44a00-ffffffff81c44aca: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:930
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff82123376-ffffffff821233a0: dwc2_hc_cleanup.cold (STB_LOCAL)
ffffffff81cabff0-ffffffff81cac0ba: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:930
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_reinit
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff82204b4d-ffffffff82204b77: dwc2_hc_cleanup.cold (STB_LOCAL)
ffffffff81d60ca0-ffffffff81d60d6a: dwc2_hc_cleanup (STB_GLOBAL)
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
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a43e28)
Location: drivers/usb/dwc2/hcd.c:965
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffff800010a43e28-ffff800010a43ed4: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b16708)
Location: drivers/usb/dwc2/hcd.c:965
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
c0b16708-c0b167e0: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b06a40)
Location: drivers/usb/dwc2/hcd.c:965
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
c000000000b06a40-c000000000b06b34: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe00066054a)
Location: drivers/usb/dwc2/hcd.c:965
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffe00066054a-ffffffe00066060a: dwc2_hc_cleanup (STB_GLOBAL)
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
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817c3da0)
Location: drivers/usb/dwc2/hcd.c:965
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff817c3da0-ffffffff817c3e0c: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81800840)
Location: drivers/usb/dwc2/hcd.c:965
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff81800840-ffffffff818008ac: dwc2_hc_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dwc2_hc_cleanup(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8181a950)
Location: drivers/usb/dwc2/hcd.c:965
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_start
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
  - drivers/usb/dwc2/hcd_intr.c:dwc2_release_channel
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_release_channel_ddma
```
**Symbols:**

```
ffffffff8181a950-ffffffff8181a9bc: dwc2_hc_cleanup (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
