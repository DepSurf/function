# Function: <code>dwc2_assign_and_init_hc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81628050)
Location: drivers/usb/dwc2/hcd.c:766
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff81628050-ffffffff81628784: dwc2_assign_and_init_hc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81686390)
Location: drivers/usb/dwc2/hcd.c:2627
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff81686390-ffffffff81686a64: dwc2_assign_and_init_hc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b45d0)
Location: drivers/usb/dwc2/hcd.c:2658
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff816b45d0-ffffffff816b4c93: dwc2_assign_and_init_hc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816c8960)
Location: drivers/usb/dwc2/hcd.c:2671
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff816c8960-ffffffff816c8ff6: dwc2_assign_and_init_hc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81734e60)
Location: drivers/usb/dwc2/hcd.c:2677
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff81734e60-ffffffff8173550e: dwc2_assign_and_init_hc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81775330)
Location: drivers/usb/dwc2/hcd.c:2768
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff81775330-ffffffff81775bbf: dwc2_assign_and_init_hc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179a8d0)
Location: drivers/usb/dwc2/hcd.c:2758
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff8179a8d0-ffffffff8179b1d4: dwc2_assign_and_init_hc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2578
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff817d9a80-ffffffff817da303: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff817dea38-ffffffff817deaa0: dwc2_assign_and_init_hc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2578
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff8180a910-ffffffff8180b225: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff8180f972-ffffffff8180f9cb: dwc2_assign_and_init_hc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2578
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff818dad30-ffffffff818db039: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff818e0587-ffffffff818e05da: dwc2_assign_and_init_hc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2579
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff818e4ac0-ffffffff818e4f00: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff81c1f5f5-ffffffff81c1f651: dwc2_assign_and_init_hc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2577
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff818c7990-ffffffff818c7dcd: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff81c11486-ffffffff81c114d9: dwc2_assign_and_init_hc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2577
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff8195f7f0-ffffffff8195fcb5: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff81d1ab1c-ffffffff81d1ac1a: dwc2_assign_and_init_hc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2573
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff81ab9c80-ffffffff81aba11c: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff81ee5cb1-ffffffff81ee5dad: dwc2_assign_and_init_hc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2544
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff81c43070-ffffffff81c4354d: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff820a1608-ffffffff820a16ba: dwc2_assign_and_init_hc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2544
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff81caa7d0-ffffffff81caaca9: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff82122c2f-ffffffff82122ce1: dwc2_assign_and_init_hc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2544
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff81d5f480-ffffffff81d5f959: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff82204406-ffffffff822044b8: dwc2_assign_and_init_hc.cold (STB_LOCAL)
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
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a411f0)
Location: drivers/usb/dwc2/hcd.c:2578
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffff800010a411f0-ffff800010a41b80: dwc2_assign_and_init_hc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b13870)
Location: drivers/usb/dwc2/hcd.c:2578
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
c0b13870-c0b142d4: dwc2_assign_and_init_hc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b01c80)
Location: drivers/usb/dwc2/hcd.c:2578
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
c000000000b01c80-c000000000b02a18: dwc2_assign_and_init_hc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe00065d170)
Location: drivers/usb/dwc2/hcd.c:2578
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffe00065d170-ffffffe00065db7a: dwc2_assign_and_init_hc (STB_LOCAL)
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
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2578
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff817c2cf0-ffffffff817c3605: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff817c7d52-ffffffff817c7dab: dwc2_assign_and_init_hc.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2578
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff817ff790-ffffffff818000a5: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff818047f2-ffffffff8180484b: dwc2_assign_and_init_hc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_assign_and_init_hc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2578
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
**Symbols:**

```
ffffffff818198a0-ffffffff8181a1b5: dwc2_assign_and_init_hc (STB_LOCAL)
ffffffff8181e902-ffffffff8181e95b: dwc2_assign_and_init_hc.cold (STB_LOCAL)
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
