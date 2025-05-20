# Function: <code>dwc_handle_gpwrdn_disc_det</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg *hsotg, u32 gpwrdn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff818c31d0)
Location: drivers/usb/dwc2/core_intr.c:689
Inline: False
```
**Symbols:**

```
ffffffff818c31d0-ffffffff818c33a3: dwc_handle_gpwrdn_disc_det (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg *hsotg, u32 gpwrdn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff8195a6d8)
Location: drivers/usb/dwc2/core_intr.c:689
Inline: True
```
**Symbols:**

```
ffffffff8195a430-ffffffff8195a768: dwc_handle_gpwrdn_disc_det (STB_LOCAL)
ffffffff81d18a97-ffffffff81d18c56: dwc_handle_gpwrdn_disc_det.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg *hsotg, u32 gpwrdn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff81ab44e1)
Location: drivers/usb/dwc2/core_intr.c:689
Inline: True
```
**Symbols:**

```
ffffffff81ab42f0-ffffffff81ab457a: dwc_handle_gpwrdn_disc_det (STB_LOCAL)
ffffffff81ee3b68-ffffffff81ee3de4: dwc_handle_gpwrdn_disc_det.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg *hsotg, u32 gpwrdn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff81c3ccf1)
Location: drivers/usb/dwc2/core_intr.c:659
Inline: True
```
**Symbols:**

```
ffffffff81c3cb00-ffffffff81c3cd8a: dwc_handle_gpwrdn_disc_det (STB_LOCAL)
ffffffff8209fc78-ffffffff8209fef4: dwc_handle_gpwrdn_disc_det.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg *hsotg, u32 gpwrdn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff81ca40f1)
Location: drivers/usb/dwc2/core_intr.c:659
Inline: True
```
**Symbols:**

```
ffffffff81ca3f00-ffffffff81ca418a: dwc_handle_gpwrdn_disc_det (STB_LOCAL)
ffffffff8212122e-ffffffff821214aa: dwc_handle_gpwrdn_disc_det.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dwc_handle_gpwrdn_disc_det(struct dwc2_hsotg *hsotg, u32 gpwrdn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core_intr.c (ffffffff81d58d41)
Location: drivers/usb/dwc2/core_intr.c:659
Inline: True
```
**Symbols:**

```
ffffffff81d58b50-ffffffff81d58dda: dwc_handle_gpwrdn_disc_det (STB_LOCAL)
ffffffff82202a05-ffffffff82202c81: dwc_handle_gpwrdn_disc_det.cold (STB_LOCAL)
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
