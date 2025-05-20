# Function: <code>touchscreen_apply_prop_to_x_y</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff816d1b7c)
Location: drivers/input/touchscreen/of_touchscreen.c:132
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff816ffa5c)
Location: drivers/input/touchscreen/of_touchscreen.c:132
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8171537c)
Location: drivers/input/touchscreen/of_touchscreen.c:132
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8178659c)
Location: drivers/input/touchscreen/of_touchscreen.c:133
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff817c7645)
Location: drivers/input/touchscreen/of_touchscreen.c:133
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff817eece5)
Location: drivers/input/touchscreen/of_touchscreen.c:153
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8182f8e5)
Location: drivers/input/touchscreen/of_touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff81861215)
Location: drivers/input/touchscreen/of_touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff81933f95)
Location: drivers/input/touchscreen/of_touchscreen.c:148
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff8193b015)
Location: drivers/input/touchscreen/of_touchscreen.c:148
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen.c (ffffffff819183c5)
Location: drivers/input/touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen.c:touchscreen_set_mt_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void touchscreen_apply_prop_to_x_y(const struct touchscreen_properties *prop, unsigned int *x, unsigned int *y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen.c (ffffffff819ba725)
Location: drivers/input/touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_set_mt_pos
Direct callers:
  - drivers/input/touchscreen.c:touchscreen_report_pos
```
**Symbols:**

```
ffffffff819ba620-ffffffff819ba69c: touchscreen_apply_prop_to_x_y (STB_LOCAL)
ffffffff81d2346e-ffffffff81d234c4: touchscreen_apply_prop_to_x_y.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void touchscreen_apply_prop_to_x_y(const struct touchscreen_properties *prop, unsigned int *x, unsigned int *y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen.c (ffffffff81b1a495)
Location: drivers/input/touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_set_mt_pos
Direct callers:
  - drivers/input/touchscreen.c:touchscreen_report_pos
```
**Symbols:**

```
ffffffff81b1a330-ffffffff81b1a3ba: touchscreen_apply_prop_to_x_y (STB_LOCAL)
ffffffff81eef24f-ffffffff81eef2a5: touchscreen_apply_prop_to_x_y.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void touchscreen_apply_prop_to_x_y(const struct touchscreen_properties *prop, unsigned int *x, unsigned int *y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen.c (ffffffff81cac1c5)
Location: drivers/input/touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_set_mt_pos
Direct callers:
  - drivers/input/touchscreen.c:touchscreen_report_pos
```
**Symbols:**

```
ffffffff81cac080-ffffffff81cac10a: touchscreen_apply_prop_to_x_y (STB_LOCAL)
ffffffff820a684b-ffffffff820a68a1: touchscreen_apply_prop_to_x_y.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void touchscreen_apply_prop_to_x_y(const struct touchscreen_properties *prop, unsigned int *x, unsigned int *y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen.c (ffffffff81d137a5)
Location: drivers/input/touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_set_mt_pos
Direct callers:
  - drivers/input/touchscreen.c:touchscreen_report_pos
```
**Symbols:**

```
ffffffff81d13660-ffffffff81d136ea: touchscreen_apply_prop_to_x_y (STB_LOCAL)
ffffffff82127c58-ffffffff82127cae: touchscreen_apply_prop_to_x_y.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void touchscreen_apply_prop_to_x_y(const struct touchscreen_properties *prop, unsigned int *x, unsigned int *y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen.c (ffffffff81dc93d5)
Location: drivers/input/touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen.c:touchscreen_set_mt_pos
Direct callers:
  - drivers/input/touchscreen.c:touchscreen_report_pos
```
**Symbols:**

```
ffffffff81dc9290-ffffffff81dc931a: touchscreen_apply_prop_to_x_y (STB_LOCAL)
ffffffff822095d9-ffffffff8220962f: touchscreen_apply_prop_to_x_y.cold (STB_LOCAL)
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
In drivers/input/touchscreen/of_touchscreen.c (ffff800010aa3b90)
Location: drivers/input/touchscreen/of_touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (c0b833d4)
Location: drivers/input/touchscreen/of_touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (c000000000b848b0)
Location: drivers/input/touchscreen/of_touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffe0006b11e8)
Location: drivers/input/touchscreen/of_touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
```
</details>
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/of_touchscreen.c (ffffffff818553a5)
Location: drivers/input/touchscreen/of_touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
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
In drivers/input/touchscreen/of_touchscreen.c (ffffffff818704d5)
Location: drivers/input/touchscreen/of_touchscreen.c:149
Inline: True
Inline callers:
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_report_pos
  - drivers/input/touchscreen/of_touchscreen.c:touchscreen_set_mt_pos
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
