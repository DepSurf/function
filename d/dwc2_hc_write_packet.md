# Function: <code>dwc2_hc_write_packet</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81621b00)
Location: drivers/usb/dwc2/core.c:1629
Inline: True
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/core.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff81621b00-ffffffff81621bac: dwc2_hc_write_packet.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816862e0)
Location: drivers/usb/dwc2/hcd.c:1237
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff816862e0-ffffffff81686389: dwc2_hc_write_packet.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b4520)
Location: drivers/usb/dwc2/hcd.c:1267
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff816b4520-ffffffff816b45c9: dwc2_hc_write_packet.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816c88b0)
Location: drivers/usb/dwc2/hcd.c:1284
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff816c88b0-ffffffff816c8959: dwc2_hc_write_packet.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81734db0)
Location: drivers/usb/dwc2/hcd.c:1290
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff81734db0-ffffffff81734e59: dwc2_hc_write_packet.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81773b00)
Location: drivers/usb/dwc2/hcd.c:1325
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff81773b00-ffffffff81773ba9: dwc2_hc_write_packet.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817986d0)
Location: drivers/usb/dwc2/hcd.c:1318
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff817986d0-ffffffff817987aa: dwc2_hc_write_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817d7960)
Location: drivers/usb/dwc2/hcd.c:1128
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff817d7960-ffffffff817d7a3a: dwc2_hc_write_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818087f0)
Location: drivers/usb/dwc2/hcd.c:1128
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff818087f0-ffffffff818088ca: dwc2_hc_write_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818d9510)
Location: drivers/usb/dwc2/hcd.c:1128
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff818d9510-ffffffff818d95f2: dwc2_hc_write_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e3460)
Location: drivers/usb/dwc2/hcd.c:1128
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff818e3460-ffffffff818e3542: dwc2_hc_write_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c6730)
Location: drivers/usb/dwc2/hcd.c:1126
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff818c6730-ffffffff818c6812: dwc2_hc_write_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1126
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff8195efc0-ffffffff8195f0ed: dwc2_hc_write_packet (STB_LOCAL)
ffffffff81d1a85b-ffffffff81d1a8ad: dwc2_hc_write_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1122
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff81ab9420-ffffffff81ab9565: dwc2_hc_write_packet (STB_LOCAL)
ffffffff81ee5998-ffffffff81ee59ea: dwc2_hc_write_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1093
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff81c427a0-ffffffff81c428e5: dwc2_hc_write_packet (STB_LOCAL)
ffffffff820a12f6-ffffffff820a1348: dwc2_hc_write_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1093
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff81ca9d70-ffffffff81ca9eb5: dwc2_hc_write_packet (STB_LOCAL)
ffffffff821228c9-ffffffff8212291b: dwc2_hc_write_packet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1093
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff81d5ea20-ffffffff81d5eb65: dwc2_hc_write_packet (STB_LOCAL)
ffffffff822040a0-ffffffff822040f2: dwc2_hc_write_packet.cold (STB_LOCAL)
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
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a408a8)
Location: drivers/usb/dwc2/hcd.c:1128
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffff800010a408a8-ffff800010a409f4: dwc2_hc_write_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b13234)
Location: drivers/usb/dwc2/hcd.c:1128
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
c0b13234-c0b13388: dwc2_hc_write_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b01340)
Location: drivers/usb/dwc2/hcd.c:1128
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
c000000000b01340-c000000000b014cc: dwc2_hc_write_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe00065c582)
Location: drivers/usb/dwc2/hcd.c:1128
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffe00065c582-ffffffe00065c772: dwc2_hc_write_packet (STB_LOCAL)
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
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817c0bd0)
Location: drivers/usb/dwc2/hcd.c:1128
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff817c0bd0-ffffffff817c0caa: dwc2_hc_write_packet (STB_LOCAL)
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
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817fd670)
Location: drivers/usb/dwc2/hcd.c:1128
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff817fd670-ffffffff817fd74a: dwc2_hc_write_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dwc2_hc_write_packet(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81817780)
Location: drivers/usb/dwc2/hcd.c:1128
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hc_continue_transfer
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer
```
**Symbols:**

```
ffffffff81817780-ffffffff8181785a: dwc2_hc_write_packet (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
