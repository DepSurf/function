# Function: <code>dwc2_hc_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_hc_init(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81622960)
Location: drivers/usb/dwc2/core.c:1295
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff81622960-ffffffff81622be9: dwc2_hc_init (STB_GLOBAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff816865b3)
Location: drivers/usb/dwc2/hcd.c:813
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff816b47ed)
Location: drivers/usb/dwc2/hcd.c:843
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff816c8b74)
Location: drivers/usb/dwc2/hcd.c:860
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff8173507a)
Location: drivers/usb/dwc2/hcd.c:866
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff81775582)
Location: drivers/usb/dwc2/hcd.c:883
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff8179ab22)
Location: drivers/usb/dwc2/hcd.c:876
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff817d9ce8)
Location: drivers/usb/dwc2/hcd.c:686
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff8180ab7c)
Location: drivers/usb/dwc2/hcd.c:686
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_hc_init(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818daa40)
Location: drivers/usb/dwc2/hcd.c:686
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff818daa40-ffffffff818dad2e: dwc2_hc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_hc_init(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e47d0)
Location: drivers/usb/dwc2/hcd.c:686
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff818e47d0-ffffffff818e4abe: dwc2_hc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_hc_init(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c7680)
Location: drivers/usb/dwc2/hcd.c:684
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff818c7680-ffffffff818c7983: dwc2_hc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_init(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:684
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff8195f3a0-ffffffff8195f7ef: dwc2_hc_init (STB_LOCAL)
ffffffff81d1a9e0-ffffffff81d1ab1c: dwc2_hc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_init(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:680
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff81ab9830-ffffffff81ab9c79: dwc2_hc_init (STB_LOCAL)
ffffffff81ee5b54-ffffffff81ee5cb1: dwc2_hc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_init(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:651
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff81c42bf0-ffffffff81c43051: dwc2_hc_init (STB_LOCAL)
ffffffff820a14b2-ffffffff820a1608: dwc2_hc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_init(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:651
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff81caa360-ffffffff81caa7c0: dwc2_hc_init (STB_LOCAL)
ffffffff82122ad9-ffffffff82122c2f: dwc2_hc_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_init(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:651
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff81d5f010-ffffffff81d5f470: dwc2_hc_init (STB_LOCAL)
ffffffff822042b0-ffffffff82204406: dwc2_hc_init.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffff800010a4142c)
Location: drivers/usb/dwc2/hcd.c:686
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (c0b13b70)
Location: drivers/usb/dwc2/hcd.c:686
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (c000000000b01f34)
Location: drivers/usb/dwc2/hcd.c:686
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffe00065d38c)
Location: drivers/usb/dwc2/hcd.c:686
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff817c2f5c)
Location: drivers/usb/dwc2/hcd.c:686
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff817ff9fc)
Location: drivers/usb/dwc2/hcd.c:686
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff81819b0c)
Location: drivers/usb/dwc2/hcd.c:686
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
