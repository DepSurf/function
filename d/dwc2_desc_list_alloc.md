# Function: <code>dwc2_desc_list_alloc</code>

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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e602)
Location: drivers/usb/dwc2/hcd_ddma.c:87
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168f25d)
Location: drivers/usb/dwc2/hcd_ddma.c:87
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bd31d)
Location: drivers/usb/dwc2/hcd_ddma.c:87
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d136d)
Location: drivers/usb/dwc2/hcd_ddma.c:87
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173d9dd)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177e360)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a49ef)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e3c2f)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81814a11)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dwc2_desc_list_alloc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e5c90)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff818e5c90-ffffffff818e5ee1: dwc2_desc_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dwc2_desc_list_alloc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818ef7a0)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff818ef7a0-ffffffff818ef992: dwc2_desc_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_desc_list_alloc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d2ec0)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff818d2ec0-ffffffff818d30b3: dwc2_desc_list_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_desc_list_alloc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff8196d960-ffffffff8196db5f: dwc2_desc_list_alloc (STB_LOCAL)
ffffffff81d1e386-ffffffff81d1e3a2: dwc2_desc_list_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_desc_list_alloc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81ac7f40-ffffffff81ac8145: dwc2_desc_list_alloc (STB_LOCAL)
ffffffff81ee9e08-ffffffff81ee9e23: dwc2_desc_list_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_desc_list_alloc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: drivers/usb/dwc2/hcd_ddma.c:58
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81c52290-ffffffff81c52495: dwc2_desc_list_alloc (STB_LOCAL)
ffffffff820a4e8b-ffffffff820a4ea6: dwc2_desc_list_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_desc_list_alloc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: drivers/usb/dwc2/hcd_ddma.c:58
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81cb9850-ffffffff81cb9a52: dwc2_desc_list_alloc (STB_LOCAL)
ffffffff821263bf-ffffffff821263d3: dwc2_desc_list_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_desc_list_alloc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: drivers/usb/dwc2/hcd_ddma.c:58
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81d6e5c0-ffffffff81d6e7c2: dwc2_desc_list_alloc (STB_LOCAL)
ffffffff82207bc8-ffffffff82207bdc: dwc2_desc_list_alloc.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4dbe4)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (c0b1fce8)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (c000000000b153e0)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066a658)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817ccdf1)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81809891)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818239a1)
Location: drivers/usb/dwc2/hcd_ddma.c:88
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
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
