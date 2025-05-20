# Function: <code>dwc2_ovr_avalid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/drd.c (ffffffff818e1f10)
Location: drivers/usb/dwc2/drd.c:33
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff818e1f10-ffffffff818e1f6f: dwc2_ovr_avalid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/drd.c (ffffffff818c5220)
Location: drivers/usb/dwc2/drd.c:33
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff818c5220-ffffffff818c527f: dwc2_ovr_avalid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/drd.c (ffffffff8195d0f5)
Location: drivers/usb/dwc2/drd.c:34
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:41
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff81ab6d00-ffffffff81ab6da9: dwc2_ovr_avalid (STB_LOCAL)
ffffffff81ee49a9-ffffffff81ee49d9: dwc2_ovr_avalid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:41
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff81c3f790-ffffffff81c3f839: dwc2_ovr_avalid (STB_LOCAL)
ffffffff820a09b6-ffffffff820a09e6: dwc2_ovr_avalid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:42
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff81ca6d10-ffffffff81ca6db9: dwc2_ovr_avalid (STB_LOCAL)
ffffffff82121f7e-ffffffff82121fae: dwc2_ovr_avalid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:42
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff81d5b960-ffffffff81d5ba09: dwc2_ovr_avalid (STB_LOCAL)
ffffffff82203755-ffffffff82203785: dwc2_ovr_avalid.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
