# Function: <code>dwc2_set_param_phy_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_set_param_phy_type(struct dwc2_hsotg *hsotg, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff816241e0)
Location: drivers/usb/dwc2/core.c:2643
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_set_parameters
```
**Symbols:**

```
ffffffff816241e0-ffffffff816242cd: dwc2_set_param_phy_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dwc2_set_param_phy_type(struct dwc2_hsotg *hsotg, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81682880)
Location: drivers/usb/dwc2/core.c:915
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_set_parameters
```
**Symbols:**

```
ffffffff81682880-ffffffff81682978: dwc2_set_param_phy_type (STB_GLOBAL)
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
In drivers/usb/dwc2/params.c (ffffffff816b18de)
Location: drivers/usb/dwc2/params.c:677
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
In drivers/usb/dwc2/params.c (ffffffff816c6a7b)
Location: drivers/usb/dwc2/params.c:182
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
In drivers/usb/dwc2/params.c (ffffffff81732e4b)
Location: drivers/usb/dwc2/params.c:194
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
In drivers/usb/dwc2/params.c (ffffffff817731c1)
Location: drivers/usb/dwc2/params.c:195
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
In drivers/usb/dwc2/params.c (ffffffff817983c1)
Location: drivers/usb/dwc2/params.c:201
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
In drivers/usb/dwc2/params.c (ffffffff817d6f42)
Location: drivers/usb/dwc2/params.c:214
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
In drivers/usb/dwc2/params.c (ffffffff81807dd2)
Location: drivers/usb/dwc2/params.c:214
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
In drivers/usb/dwc2/params.c (ffffffff818d8445)
Location: drivers/usb/dwc2/params.c:247
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
In drivers/usb/dwc2/params.c (ffffffff818e2945)
Location: drivers/usb/dwc2/params.c:248
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
In drivers/usb/dwc2/params.c (ffffffff818c615f)
Location: drivers/usb/dwc2/params.c:263
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
In drivers/usb/dwc2/params.c (ffffffff8195d9b6)
Location: drivers/usb/dwc2/params.c:263
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
In drivers/usb/dwc2/params.c (ffffffff81ab7bda)
Location: drivers/usb/dwc2/params.c:330
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
In drivers/usb/dwc2/params.c (ffffffff81c4081e)
Location: drivers/usb/dwc2/params.c:304
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
In drivers/usb/dwc2/params.c (ffffffff81ca7df2)
Location: drivers/usb/dwc2/params.c:325
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
In drivers/usb/dwc2/params.c (ffffffff81d5ca82)
Location: drivers/usb/dwc2/params.c:356
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
In drivers/usb/dwc2/params.c (ffff800010a3fc3c)
Location: drivers/usb/dwc2/params.c:214
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
In drivers/usb/dwc2/params.c (c0b127bc)
Location: drivers/usb/dwc2/params.c:214
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
In drivers/usb/dwc2/params.c (c000000000b0040c)
Location: drivers/usb/dwc2/params.c:214
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
In drivers/usb/dwc2/params.c (ffffffe00065ba28)
Location: drivers/usb/dwc2/params.c:214
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
In drivers/usb/dwc2/params.c (ffffffff817c01b2)
Location: drivers/usb/dwc2/params.c:214
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
In drivers/usb/dwc2/params.c (ffffffff817fcc52)
Location: drivers/usb/dwc2/params.c:214
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
In drivers/usb/dwc2/params.c (ffffffff81816d62)
Location: drivers/usb/dwc2/params.c:214
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
