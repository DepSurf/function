# Function: <code>dwc2_handle_lpm_intr</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff81770dba)
Location: drivers/usb/dwc2/core_intr.c:556
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff81795ae6)
Location: drivers/usb/dwc2/core_intr.c:556
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff817d54ed)
Location: drivers/usb/dwc2/core_intr.c:568
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff8180639d)
Location: drivers/usb/dwc2/core_intr.c:568
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_lpm_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:566
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818d6110-ffffffff818d62bb: dwc2_handle_lpm_intr (STB_LOCAL)
ffffffff818d70af-ffffffff818d70c3: dwc2_handle_lpm_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_lpm_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:566
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818e02f0-ffffffff818e049b: dwc2_handle_lpm_intr (STB_LOCAL)
ffffffff81c1ed0e-ffffffff81c1ed22: dwc2_handle_lpm_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_lpm_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:593
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff818c3010-ffffffff818c31c8: dwc2_handle_lpm_intr (STB_LOCAL)
ffffffff81c10b1e-ffffffff81c10b32: dwc2_handle_lpm_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_lpm_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:593
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff8195ab50-ffffffff8195ad95: dwc2_handle_lpm_intr (STB_LOCAL)
ffffffff81d18ced-ffffffff81d18d9b: dwc2_handle_lpm_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_lpm_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:593
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81ab49d0-ffffffff81ab4c20: dwc2_handle_lpm_intr (STB_LOCAL)
ffffffff81ee3e92-ffffffff81ee3f62: dwc2_handle_lpm_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_lpm_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:563
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81c3d220-ffffffff81c3d47d: dwc2_handle_lpm_intr (STB_LOCAL)
ffffffff8209ff8d-ffffffff820a004c: dwc2_handle_lpm_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_lpm_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:563
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81ca4600-ffffffff81ca485d: dwc2_handle_lpm_intr (STB_LOCAL)
ffffffff82121543-ffffffff82121602: dwc2_handle_lpm_intr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_handle_lpm_intr(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (0)
Location: drivers/usb/dwc2/core_intr.c:563
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
**Symbols:**

```
ffffffff81d59250-ffffffff81d594ad: dwc2_handle_lpm_intr (STB_LOCAL)
ffffffff82202d1a-ffffffff82202dd9: dwc2_handle_lpm_intr.cold (STB_LOCAL)
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
In drivers/usb/dwc2/core_intr.c (ffff800010a3d97c)
Location: drivers/usb/dwc2/core_intr.c:568
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (c0b10768)
Location: drivers/usb/dwc2/core_intr.c:568
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (c000000000afd3c0)
Location: drivers/usb/dwc2/core_intr.c:568
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffe0006598a4)
Location: drivers/usb/dwc2/core_intr.c:568
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff817be77d)
Location: drivers/usb/dwc2/core_intr.c:568
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff817fb21d)
Location: drivers/usb/dwc2/core_intr.c:568
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
In drivers/usb/dwc2/core_intr.c (ffffffff818153eb)
Location: drivers/usb/dwc2/core_intr.c:568
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
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
