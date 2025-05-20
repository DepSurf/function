# Function: <code>dwc2_ovr_bvalid</code>

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
int dwc2_ovr_bvalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/drd.c (ffffffff818e1eb0)
Location: drivers/usb/dwc2/drd.c:51
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff818e1eb0-ffffffff818e1f0d: dwc2_ovr_bvalid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_ovr_bvalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/drd.c (ffffffff818c51c0)
Location: drivers/usb/dwc2/drd.c:51
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff818c51c0-ffffffff818c521d: dwc2_ovr_bvalid (STB_LOCAL)
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
In drivers/usb/dwc2/drd.c (ffffffff8195d055)
Location: drivers/usb/dwc2/drd.c:53
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
int dwc2_ovr_bvalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:63
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff81ab6db0-ffffffff81ab6e5a: dwc2_ovr_bvalid (STB_LOCAL)
ffffffff81ee49d9-ffffffff81ee4a09: dwc2_ovr_bvalid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_ovr_bvalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:63
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff81c3f850-ffffffff81c3f8fa: dwc2_ovr_bvalid (STB_LOCAL)
ffffffff820a09e6-ffffffff820a0a16: dwc2_ovr_bvalid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_ovr_bvalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:64
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff81ca6dd0-ffffffff81ca6e7a: dwc2_ovr_bvalid (STB_LOCAL)
ffffffff82121fae-ffffffff82121fde: dwc2_ovr_bvalid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_ovr_bvalid(struct dwc2_hsotg *hsotg, bool valid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:64
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
**Symbols:**

```
ffffffff81d5ba20-ffffffff81d5baca: dwc2_ovr_bvalid (STB_LOCAL)
ffffffff82203785-ffffffff822037b5: dwc2_ovr_bvalid.cold (STB_LOCAL)
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
