# Function: <code>dwc2_set_param_speed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_set_param_speed(struct dwc2_hsotg *hsotg, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816242d0)
Location: drivers/usb/dwc2/core.c:2696
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_set_parameters
```
**Symbols:**

```
ffffffff816242d0-ffffffff81624379: dwc2_set_param_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dwc2_set_param_speed(struct dwc2_hsotg *hsotg, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81682980)
Location: drivers/usb/dwc2/core.c:968
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_set_parameters
```
**Symbols:**

```
ffffffff81682980-ffffffff81682a2b: dwc2_set_param_speed (STB_GLOBAL)
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
In drivers/usb/dwc2/params.c (ffffffff816b1939)
Location: drivers/usb/dwc2/params.c:730
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_set_parameters
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
In drivers/usb/dwc2/params.c (ffffffff816c6aa6)
Location: drivers/usb/dwc2/params.c:202
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
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
In drivers/usb/dwc2/params.c (ffffffff81732e6e)
Location: drivers/usb/dwc2/params.c:214
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_init_params
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
In drivers/usb/dwc2/params.c (ffffffff817731db)
Location: drivers/usb/dwc2/params.c:215
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
In drivers/usb/dwc2/params.c (ffffffff817983db)
Location: drivers/usb/dwc2/params.c:221
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
In drivers/usb/dwc2/params.c (ffffffff817d6f62)
Location: drivers/usb/dwc2/params.c:234
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
In drivers/usb/dwc2/params.c (ffffffff81807df2)
Location: drivers/usb/dwc2/params.c:234
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff818d8463)
Location: drivers/usb/dwc2/params.c:267
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff818e2963)
Location: drivers/usb/dwc2/params.c:268
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff818c617e)
Location: drivers/usb/dwc2/params.c:283
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
In drivers/usb/dwc2/params.c (ffffffff8195d98c)
Location: drivers/usb/dwc2/params.c:283
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81ab80f2)
Location: drivers/usb/dwc2/params.c:350
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81c40fb5)
Location: drivers/usb/dwc2/params.c:324
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81ca8561)
Location: drivers/usb/dwc2/params.c:345
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/params.c (ffffffff81d5d1f1)
Location: drivers/usb/dwc2/params.c:376
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_check_params
  - drivers/usb/dwc2/params.c:dwc2_set_default_params
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
In drivers/usb/dwc2/params.c (ffff800010a3fc58)
Location: drivers/usb/dwc2/params.c:234
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
In drivers/usb/dwc2/params.c (c0b127d4)
Location: drivers/usb/dwc2/params.c:234
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
In drivers/usb/dwc2/params.c (c000000000b00434)
Location: drivers/usb/dwc2/params.c:234
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
In drivers/usb/dwc2/params.c (ffffffe00065ba3c)
Location: drivers/usb/dwc2/params.c:234
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
In drivers/usb/dwc2/params.c (ffffffff817c01d2)
Location: drivers/usb/dwc2/params.c:234
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
In drivers/usb/dwc2/params.c (ffffffff817fcc72)
Location: drivers/usb/dwc2/params.c:234
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
In drivers/usb/dwc2/params.c (ffffffff81816d82)
Location: drivers/usb/dwc2/params.c:234
Inline: True
Inline callers:
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/usb/dwc2/params.c:dwc2_check_params
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
</ul>
