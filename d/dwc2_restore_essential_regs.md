# Function: <code>dwc2_restore_essential_regs</code>

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
In drivers/usb/dwc2/core.c (ffffffff81770179)
Location: drivers/usb/dwc2/core.c:251
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
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
In drivers/usb/dwc2/core.c (ffffffff81794fc1)
Location: drivers/usb/dwc2/core.c:251
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
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
In drivers/usb/dwc2/core.c (ffffffff817d3833)
Location: drivers/usb/dwc2/core.c:251
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
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
In drivers/usb/dwc2/core.c (ffffffff81804703)
Location: drivers/usb/dwc2/core.c:251
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_restore_essential_regs(struct dwc2_hsotg *hsotg, int rmode, int is_host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818d4260)
Location: drivers/usb/dwc2/core.c:251
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
```
**Symbols:**

```
ffffffff818d4260-ffffffff818d445e: dwc2_restore_essential_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_restore_essential_regs(struct dwc2_hsotg *hsotg, int rmode, int is_host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818de580)
Location: drivers/usb/dwc2/core.c:251
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
```
**Symbols:**

```
ffffffff818de580-ffffffff818de77e: dwc2_restore_essential_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_restore_essential_regs(struct dwc2_hsotg *hsotg, int rmode, int is_host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff818c18a0)
Location: drivers/usb/dwc2/core.c:176
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
```
**Symbols:**

```
ffffffff818c18a0-ffffffff818c1aa5: dwc2_restore_essential_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_restore_essential_regs(struct dwc2_hsotg *hsotg, int rmode, int is_host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:176
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
```
**Symbols:**

```
ffffffff81958150-ffffffff8195845d: dwc2_restore_essential_regs (STB_LOCAL)
ffffffff81d17df0-ffffffff81d17ee3: dwc2_restore_essential_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_restore_essential_regs(struct dwc2_hsotg *hsotg, int rmode, int is_host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:176
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
```
**Symbols:**

```
ffffffff81ab1fc0-ffffffff81ab22db: dwc2_restore_essential_regs (STB_LOCAL)
ffffffff81ee2c97-ffffffff81ee2d8a: dwc2_restore_essential_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_restore_essential_regs(struct dwc2_hsotg *hsotg, int rmode, int is_host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:146
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
```
**Symbols:**

```
ffffffff81c3a650-ffffffff81c3a96b: dwc2_restore_essential_regs (STB_LOCAL)
ffffffff8209ee78-ffffffff8209ef6b: dwc2_restore_essential_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_restore_essential_regs(struct dwc2_hsotg *hsotg, int rmode, int is_host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:146
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
```
**Symbols:**

```
ffffffff81ca1a00-ffffffff81ca1d1b: dwc2_restore_essential_regs (STB_LOCAL)
ffffffff82120428-ffffffff8212051b: dwc2_restore_essential_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_restore_essential_regs(struct dwc2_hsotg *hsotg, int rmode, int is_host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/core.c (0)
Location: drivers/usb/dwc2/core.c:146
Inline: False
Direct callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
```
**Symbols:**

```
ffffffff81d56650-ffffffff81d5696b: dwc2_restore_essential_regs (STB_LOCAL)
ffffffff82201bff-ffffffff82201cf2: dwc2_restore_essential_regs.cold (STB_LOCAL)
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
In drivers/usb/dwc2/core.c (ffff800010a3b64c)
Location: drivers/usb/dwc2/core.c:251
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
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
In drivers/usb/dwc2/core.c (c0b0dff8)
Location: drivers/usb/dwc2/core.c:251
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
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
In drivers/usb/dwc2/core.c (c000000000af98fc)
Location: drivers/usb/dwc2/core.c:251
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
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
In drivers/usb/dwc2/core.c (ffffffe000656c8a)
Location: drivers/usb/dwc2/core.c:251
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
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
In drivers/usb/dwc2/core.c (ffffffff817bcae3)
Location: drivers/usb/dwc2/core.c:251
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
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
In drivers/usb/dwc2/core.c (ffffffff817f9583)
Location: drivers/usb/dwc2/core.c:251
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
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
In drivers/usb/dwc2/core.c (ffffffff818137c3)
Location: drivers/usb/dwc2/core.c:251
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_hib_restore_common
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
