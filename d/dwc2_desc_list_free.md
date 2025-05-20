# Function: <code>dwc2_desc_list_free</code>

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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162e4f0)
Location: drivers/usb/dwc2/hcd_ddma.c:113
Inline: True
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
```
**Symbols:**

```
ffffffff8162e4f0-ffffffff8162e5cb: dwc2_desc_list_free.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168eb30)
Location: drivers/usb/dwc2/hcd_ddma.c:122
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff8168eb30-ffffffff8168ebeb: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bcbf0)
Location: drivers/usb/dwc2/hcd_ddma.c:122
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff816bcbf0-ffffffff816bccab: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d0c50)
Location: drivers/usb/dwc2/hcd_ddma.c:122
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff816d0c50-ffffffff816d0d0f: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173d2a0)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff8173d2a0-ffffffff8173d361: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177dc50)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff8177dc50-ffffffff8177dd0b: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a4230)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff817a4230-ffffffff817a4307: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e3510)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff817e3510-ffffffff817e35e5: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818142f0)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff818142f0-ffffffff818143c5: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e5bb0)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff818e5bb0-ffffffff818e5c85: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818ee730)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff818ee730-ffffffff818ee7c6: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d1f30)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff818d1f30-ffffffff818d1fc6: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196c950)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff8196c950-ffffffff8196c9e6: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac6df0)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81ac6df0-ffffffff81ac6e9a: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c51010)
Location: drivers/usb/dwc2/hcd_ddma.c:93
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81c51010-ffffffff81c510ba: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cb8590)
Location: drivers/usb/dwc2/hcd_ddma.c:93
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81cb8590-ffffffff81cb863a: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6d300)
Location: drivers/usb/dwc2/hcd_ddma.c:93
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81d6d300-ffffffff81d6d3aa: dwc2_desc_list_free (STB_LOCAL)
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
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4d548)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffff800010a4d548-ffff800010a4d604: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (c0b1f608)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
c0b1f608-c0b1f6c8: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b14a70)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
c000000000b14a70-c000000000b14b8c: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe000669f74)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffe000669f74-ffffffe00066a012: dwc2_desc_list_free (STB_LOCAL)
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
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cc6d0)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff817cc6d0-ffffffff817cc7a5: dwc2_desc_list_free (STB_LOCAL)
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
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81809170)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81809170-ffffffff81809245: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81823280)
Location: drivers/usb/dwc2/hcd_ddma.c:123
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
```
**Symbols:**

```
ffffffff81823280-ffffffff81823355: dwc2_desc_list_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
