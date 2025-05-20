# Function: <code>dwc2_drd_resume</code>

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
void dwc2_drd_resume(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/drd.c (ffffffff818e2280)
Location: drivers/usb/dwc2/drd.c:163
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
```
**Symbols:**

```
ffffffff818e2280-ffffffff818e22eb: dwc2_drd_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_drd_resume(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/drd.c (ffffffff818c55a0)
Location: drivers/usb/dwc2/drd.c:163
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
```
**Symbols:**

```
ffffffff818c55a0-ffffffff818c5611: dwc2_drd_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_drd_resume(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:185
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
```
**Symbols:**

```
ffffffff81d19ae1-ffffffff81d19b82: dwc2_drd_resume.cold (STB_LOCAL)
ffffffff8195d470-ffffffff8195d59f: dwc2_drd_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_drd_resume(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:207
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
```
**Symbols:**

```
ffffffff81ee4b6f-ffffffff81ee4c55: dwc2_drd_resume.cold (STB_LOCAL)
ffffffff81ab73f0-ffffffff81ab75b9: dwc2_drd_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_drd_resume(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:207
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
```
**Symbols:**

```
ffffffff820a0b60-ffffffff820a0c46: dwc2_drd_resume.cold (STB_LOCAL)
ffffffff81c3fef0-ffffffff81c400b8: dwc2_drd_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_drd_resume(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:208
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
```
**Symbols:**

```
ffffffff82122128-ffffffff82122219: dwc2_drd_resume.cold (STB_LOCAL)
ffffffff81ca7470-ffffffff81ca7638: dwc2_drd_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_drd_resume(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:208
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_resume
```
**Symbols:**

```
ffffffff822038ff-ffffffff822039f0: dwc2_drd_resume.cold (STB_LOCAL)
ffffffff81d5c0c0-ffffffff81d5c288: dwc2_drd_resume (STB_GLOBAL)
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
